FROM maven:3-openjdk-8-slim
WORKDIR /app
RUN mvn test
RUN mvn -B -DskipTests clean package