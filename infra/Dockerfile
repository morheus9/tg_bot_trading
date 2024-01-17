FROM python:3.11.4-alpine3.18

COPY requirements.txt .
RUN pip install -r requirements.txt
COPY ../. .
EXPOSE 8000

CMD ["python3", "src/main.py"]
