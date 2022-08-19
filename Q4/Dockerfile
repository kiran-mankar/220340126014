FROM python:3.10.6-alpine3.16

LABEL maintainer="220340126014/kiran"

# sets working directory inside container
WORKDIR /usr/src/pythoncodes

# copy from host to container directory
COPY factorial.py /usr/src/pythoncodes

CMD ["python3", "factorial.py"]

# sudo docker build -t factorialNum:k1 .
# sudo docker run -it factorialNum:k1
# or sudo docker run --name fact -it factorialNum:v1

