FROM tomcat:8.5.47-jdk8-openjdk

WORKDIR /app

COPY ./target/multi3-3.7-SNAPSHOT.war /usr/local/tomcat/webapps

# COPY ./contrast_security.yaml ./contrast_security.yaml

# COPY ./contrast.jar ./contrast.jar

# ENV JAVA_TOOL_OPTIONS="-javaagent:contrast.jar -Dcontrast.config.path=contrast_security.yaml -Dcontrast.log=/home/nonroot/contrast.log"

# CMD ["java", "-jar", "app.war"]

