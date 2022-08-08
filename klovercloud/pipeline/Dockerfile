FROM openjdk:8-jdk-alpine
# VOLUME /tmp
# ADD build/libs/test-app-0.1.0.jar app.jar
ARG NEXUS_USER
ENV NEXUS_USER $NEXUS_USER
EXPOSE 8080
EXPOSE 8081

# HEALTHCHECK --interval=5s \
#             --timeout=5s \
#             CMD curl -f http://127.0.0.1:8080 || exit 1

# ENV JAVA_OPTS=""
# ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -Dspring.profiles.active=$SPRING_PROFILE -jar /app.jar
