FROM python:latest
RUN pwd
WORKDIR /app
COPY requirements.txt /app
RUN pip3 install -r requirements.txt --no-cache-dir
COPY . /app
#ENTRYPOINT ["python3"]
CMD ["app.py"]
