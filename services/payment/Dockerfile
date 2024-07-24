# Use a base image with OpenJDK
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the built JAR file from your local machine to the container
COPY target/payment-service.jar /app/payment-service.jar

# Expose the port on which the application will run
EXPOSE 8060

# Define the command to run the application
ENTRYPOINT ["java", "-jar", "/app/payment-service.jar"]
