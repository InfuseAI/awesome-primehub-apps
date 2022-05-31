FROM python:3.9.13-slim

EXPOSE 8501

WORKDIR /streamlit

RUN pip install --upgrade pip
RUN pip install streamlit==1.9.2

ENTRYPOINT [ "streamlit" ]