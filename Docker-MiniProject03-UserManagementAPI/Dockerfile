FROM openjdk:17
EXPOSE 8082
COPY target/sb-mysql-app.jar  sb-mysql-app.jar
COPY src/main/java/org/sun/user_registration_body.txt /app/src/main/java/org/sun/
ENTRYPOINT ["java","-jar","/sb-mysql-app.jar"]
