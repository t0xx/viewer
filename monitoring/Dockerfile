FROM java:8
ADD target/monitoring-0.0.1-SNAPSHOT.jar monitoring.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/monitoring.jar"]