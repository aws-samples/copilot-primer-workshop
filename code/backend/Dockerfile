FROM python:3.7.10-buster
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY app.py app.py
EXPOSE 10000
CMD ["python3", "app.py"]
