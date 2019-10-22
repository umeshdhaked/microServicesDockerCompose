FROM openjdk:latest
WORKDIR usr/src
ADD ./target/netflixzuul-0.0.1-SNAPSHOT.jar /usr/src/netflixzuul-0.0.1-SNAPSHOT.jar
EXPOSE 8088
ENTRYPOINT ["java","-jar","/usr/src/netflixzuul-0.0.1-SNAPSHOT.jar"]