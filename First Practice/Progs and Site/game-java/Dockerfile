FROM openjdk:alpine

LABEL version = "1.0.1"

WORKDIR /javaPR1

COPY . /javaPR1/

RUN javac game.java

CMD [ "java" , "game" ] 