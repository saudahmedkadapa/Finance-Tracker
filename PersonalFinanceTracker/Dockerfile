# Use a JDK base image
FROM openjdk:8

# Set working directory
WORKDIR /app

# Copy JAR file and rename it to app.jar
COPY target/PersonalFinanceTracker-0.0.1-SNAPSHOT.jar app.jar

# Expose backend port (e.g., 8080)
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "app.jar"]
