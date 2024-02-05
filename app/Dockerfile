FROM ubuntu:latest
COPY ./src /app
WORKDIR /app
RUN apt update && apt install -y python3
RUN apt install -y python3-pip
RUN pip install -r requirements.txt
ENTRYPOINT ["python3", "app.py"]
CMD ["1"]
