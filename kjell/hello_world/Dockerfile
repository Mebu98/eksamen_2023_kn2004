FROM python:3-alpine

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . ./

ENTRYPOINT ["python3", "app.py"]