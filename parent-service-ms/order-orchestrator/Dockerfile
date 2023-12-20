FROM eclipse-temurin:17-jdk
WORKDIR /opt
ENV PORT 8083
EXPOSE 8083
COPY target/*.jar /opt/app.jar
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar