# syntax=docker/dockerfile:1
FROM python:3.8-slim as base

RUN apt-get update && \
    apt-get install ca-certificates openssl wget docker.io -y

# Add gitlab.com as known host for dp publish command
RUN mkdir /root/.ssh && \
    ssh-keyscan -t rsa gitlab.com >> ~/.ssh/known_hosts

# Update python and install packages
COPY requirements.txt ./
RUN pip install --upgrade pip setuptools wheel --no-cache-dir \
  -r requirements.txt

ENTRYPOINT ["python"]

CMD ["--version"]