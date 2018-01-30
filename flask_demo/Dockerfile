FROM registry.docker-cn.com/library/ubuntu:latest
MAINTAINER zq feng "zq.feng@outlook.com"

RUN apt-get update
RUN apt-get install -y python3 python3-dev python3-pip
RUN mkdir /livesites
COPY . /livesites/
WORKDIR /livesites

RUN pip3 install -r requirments.txt

EXPOSE 5000

CMD ["python3", "run.py"]
