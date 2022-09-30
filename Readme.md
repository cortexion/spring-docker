<groupId>com.example</groupId>
<artifactId>spring-boot</artifactId>
<version>0.0.1-SNAPSHOT</version>

inside target (git bash):
$ ./mvnw package && java -jar target/spring-boot-0.0.1-SNAPSHOT.jar

root level:
mvn spring-boot:run

docker build -t springio/gs-spring-boot-docker . && docker run -p 8080:8080 springio/gs-spring-boot-docker