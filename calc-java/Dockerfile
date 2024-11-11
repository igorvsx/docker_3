FROM openjdk:17-jdk-slim

WORKDIR /app

COPY calc.java /app

RUN javac calc.java

CMD ["java", "calc"]