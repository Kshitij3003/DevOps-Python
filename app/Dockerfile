FROM python:3.9

WORKDIR /app

COPY requirements.txt .

RUN pip install --upgrade pip -r requirements.txt

COPY . /app

EXPOSE 5000

CMD ["python", "main.py"]
