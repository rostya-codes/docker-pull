FROM python:3.11.9-alpine

WORKDIR /app

ENV PYTHONUNBUFFERED=1

RUN pip3 install --upgrade pip

COPY requirements.txt .

RUN pip3 install --no-cache-dir -r requirements.txt

COPY . .

CMD ["python", "app.py"]