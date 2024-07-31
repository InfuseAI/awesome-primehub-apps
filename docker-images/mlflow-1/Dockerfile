FROM python:3.11.9-slim

RUN pip install PyMySQL==1.1.1 && \
    pip install psycopg2-binary==2.9.9 && \
    pip install mlflow[extras]==1.30.1

ENTRYPOINT ["mlflow", "server"]
