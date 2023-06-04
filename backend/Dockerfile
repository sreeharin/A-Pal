FROM python:slim
ENV PYTHONUNBUFFERED=1
ENV PYTHONDONTWRITEBYTECODE=1

WORKDIR /a-pal

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .
