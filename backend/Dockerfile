FROM eclipse-temurin:17-jdk-jammy
WORKDIR /app
#COPY .mvn/ .mvn
#COPY mvnw pom.xml ./
COPY . .

RUN ./mvnw dependency:resolve
CMD ["./mvnw", "spring-boot:run"]