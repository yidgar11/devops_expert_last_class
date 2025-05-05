FROM python:3.12-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENV AWS_DEFAULT_REGION=us-east-1

CMD ["python3", "app.py"]