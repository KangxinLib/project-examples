FROM gcr.io/distroless/java17-debian11

WORKDIR /home/nonroot

COPY ./target/multi2-3.7-SNAPSHOT.jar ./app.jar

# COPY ./contrast_security.yaml ./contrast_security.yaml

# COPY ./contrast.jar ./contrast.jar

# ENV JAVA_TOOL_OPTIONS="-javaagent:contrast.jar -Dcontrast.config.path=contrast_security.yaml -Dcontrast.log=/home/nonroot/contrast.log"

CMD ["app.jar"]

