FROM java:8-jre
WORKDIR /usr/src
ENV MYSQL_URL=jdbc:mysql://localhost:3306/test
ENV MY_SQL_USER=root
ENV MY_SQL_PASSWORD=root123
ADD ./target/kubdocker201-0.0.1-SNAPSHOT.jar /usr/src/kubdocker201-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","kubdocker201-0.0.1-SNAPSHOT.jar"]
