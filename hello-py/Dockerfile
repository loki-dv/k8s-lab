FROM python:3.11-slim

WORKDIR /usr/src/app
COPY . .
RUN pip install -r requirements.txt

EXPOSE 80

ENTRYPOINT ["python", "/usr/src/app/app.py"]
