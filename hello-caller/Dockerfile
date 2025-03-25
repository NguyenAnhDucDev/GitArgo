# Sử dụng image base từ OpenJDK
FROM openjdk:17-jdk-slim

# Cài đặt thư viện cần thiết
WORKDIR /app

# Copy jar file vào container
COPY target/hello-caller.jar /app/hello-caller.jar

# Cấu hình cổng ứng dụng
EXPOSE 8081

# Chạy ứng dụng
CMD ["java", "-jar", "/app/hello-caller.jar"]
