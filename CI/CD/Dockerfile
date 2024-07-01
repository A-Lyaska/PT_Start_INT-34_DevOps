FROM python:3.11

WORKDIR /app

COPY server.py .

RUN pip install -r requirements.txt

EXPOSE 8080

CMD ["python", "server.py"]
