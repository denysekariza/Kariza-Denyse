# Use OpenJDK 17 base image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy all files from the current directory into /app
COPY . /app

# Compile Java files into 'out' directory
RUN javac -d out *.java

# Run the main class from the package
CMD ["java", "-cp", "out", "TaxEnforcementManagementSystem"]

