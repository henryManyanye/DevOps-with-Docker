FROM amazoncorretto:8

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

RUN <<EOF
./mvnw package
EOF

CMD java -jar ./target/docker-example-1.1.3.jar



