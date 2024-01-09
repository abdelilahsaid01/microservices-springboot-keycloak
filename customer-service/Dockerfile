# Use an official OpenJDK runtime as a base image
FROM openjdk:17-oracle

# Set the working directory inside the container
WORKDIR /app

# Copy the packaged JAR file into the container at the defined working directory
COPY target/*.jar /app/customer-service.jar

# Expose the port that the application will run on
#EXPOSE 8080

# Specify the command to run your application
CMD ["java", "-jar", "customer-service.jar"]
