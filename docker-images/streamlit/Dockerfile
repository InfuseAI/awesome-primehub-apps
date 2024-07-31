FROM python:3.11.9-slim

EXPOSE 8501

WORKDIR /streamlit

RUN pip install --upgrade pip
RUN pip install streamlit==1.37.0

ENTRYPOINT [ "streamlit" ]
