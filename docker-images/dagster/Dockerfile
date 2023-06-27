# Base Docker image
FROM python:3.10

# Configure work directory
WORKDIR /opt/dagster/app

# Install dagster and related python package.
COPY requirements.txt /opt/dagster/app
RUN pip install -r requirements.txt

# Example Code from official website.
COPY hello-dagster.py /opt/dagster/app

# Dagster daemon shell script
COPY dagster-daemon.sh /opt/dagster/app

# Environment Variable
ENV DAGSTER_HOME=/opt/dagster/app

# Start the service
ENTRYPOINT ["dagit", "-f", "/opt/dagster/app/hello-dagster.py", "-h", "0.0.0.0", "-p", "3000"]