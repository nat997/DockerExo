FROM ubuntu

RUN apt-get update && apt-get install -y python3 python3-pip

WORKDIR /home/user

COPY app.py .

CMD [ "python3", "app.py" ]