FROM maven:3-openjdk-17

WORKDIR /usr/src/mymaven

COPY bin .

ENTRYPOINT ["mvn"]

CMD ["clean", "install", "compile", "package", "spring-boot:run"]
