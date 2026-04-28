# Use Java 17
FROM eclipse-temurin:17-jre-alpine

# Set working directory
WORKDIR /app

# Copy the jar file
COPY target/*.jar eureka-server.jar

# Expose port
EXPOSE 8761

# Run the jar
ENTRYPOINT ["java", "-jar", "eureka-server.jar"]