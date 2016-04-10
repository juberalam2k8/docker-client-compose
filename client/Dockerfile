FROM java:openjdk-8

COPY SimpleClient.java /home/SimpleClient.java

WORKDIR /home

RUN javac SimpleClient.java

CMD ["java", "SimpleClient"]