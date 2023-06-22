FROM openjdk

WORKDIR /backend_app

RUN mvn clean install

COPY ./target/GreenCommute*.jar backend.jar

# COPY ./target/ja

EXPOSE 8080

ENTRYPOINT [ "java","-jar","backend.jar" ]