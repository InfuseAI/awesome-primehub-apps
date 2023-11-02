FROM python:3.9.13-slim

RUN pip install PyMySQL==1.0.2 && \   
    pip install psycopg2-binary==2.9.3 && \
    pip install mlflow[extras]==2.6.0

ENTRYPOINT ["mlflow", "server"]