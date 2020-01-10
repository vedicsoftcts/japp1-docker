FROM openjdk:8
COPY * japp1/
WORKDIR japp1
RUN mkdir -p bin
RUN javac -d bin ./JAPP1.java
WORKDIR bin
CMD ["java","japp1.JAPP1"]
