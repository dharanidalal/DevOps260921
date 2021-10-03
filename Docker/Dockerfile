FROM ubuntu:18.04
RUN apt update -y && apt install python3 -y && apt install python3-pip -y
RUN pip3 install flask
COPY . /tmp
EXPOSE 8080
CMD ["python3", "/tmp/app.py"]
