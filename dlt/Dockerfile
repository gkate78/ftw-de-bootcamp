FROM python:3.9-slim

WORKDIR /var/dlt/pipelines
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

