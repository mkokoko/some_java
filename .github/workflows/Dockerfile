FROM maven:3-openjdk-8-slim
WORKDIR /app
COPY . .
RUN mvn test
RUN mvn -B -DskipTests clean package