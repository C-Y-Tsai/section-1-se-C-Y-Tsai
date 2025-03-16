FROM python:3.11-slim

WORKDIR /app

COPY web/ /app/
COPY web/requirements.txt /app/

RUN pip install -r /app/requirements.txt

CMD ["python", "/app/main.py"]
