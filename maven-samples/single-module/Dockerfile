# Use a base image with Java installed
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the application's JAR file to the container
COPY target/single-module-project.jar /app/single-module-project.jar

# Expose the port the application will run on (if needed)
EXPOSE 8080

# Command to run the JAR file
CMD ["java", "-jar", "/app/single-module-project.jar"]
