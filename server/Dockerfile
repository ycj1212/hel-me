FROM python:3.9

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /opt/project
COPY requirements.txt /opt/project/
RUN pip install -r requirements.txt
COPY . /opt/project/