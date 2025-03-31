FROM python:3.11.11-slim

RUN pip install PyMySQL==1.1.1 && \
    pip install psycopg2-binary==2.9.10 && \
    pip install mlflow[extras]==2.20.3

ENTRYPOINT ["mlflow", "server"]
