FROM python:3.10.9-buster
ENV LANG C.UTF-8
ENV TZ Asia/Tokyo
WORKDIR /app
COPY requirements.txt /app
RUN pip install --upgrade pip 
RUN pip install -r /app/requirements.txt
