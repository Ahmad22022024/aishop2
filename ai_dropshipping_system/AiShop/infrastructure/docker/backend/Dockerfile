FROM python:3.11-slim

WORKDIR /app

COPY ../../backend/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY ../../backend /app

CMD ["python", "src/main.py"]
