# Use the official image as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the executable JAR file to the container
COPY target/*.jar app.jar

# Make port 8080 available to the world outside this container
EXPOSE 8888

# Run the JAR file
ENTRYPOINT ["java","-jar","app.jar"]
