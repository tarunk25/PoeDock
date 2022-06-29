FROM openjdk:8
COPY . /src/java
WORKDIR /src/java
RUN ["javac", "Sort.java"]
ENTRYPOINT ["java", "Sort"]
