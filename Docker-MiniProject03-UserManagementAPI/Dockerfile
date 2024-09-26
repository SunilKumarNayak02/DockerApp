FROM openjdk:17
EXPOSE 8082
COPY target/jrtp03-mini-usermgmt-app.jar jrtp03-mini-usermgmt-app.jar
ENTRYPOINT ["java","-jar","/jrtp03-mini-usermgmt-app.jar"]

# Add this line to your Dockerfile to verify connectivity during container startup
RUN ping -c 1 mysqldb || echo "Connectivity check to mysqldb failed"