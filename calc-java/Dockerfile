FROM openjdk:11

LABEL version="buildJavaAboba"

WORKDIR /app

COPY calc.java /app/

RUN javac calc.java

CMD ["java", "calc"]
