FROM ubuntu-jdk

ENV version=aws-db-usage

ENV dbuser=postgres
ENV dbpass=
ENV jdbcurl=

WORKDIR /usr/local/bin

ADD target/pma-app.jar .

ENTRYPOINT ["java", "-jar", "pma-app.jar"]
