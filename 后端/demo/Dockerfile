# 使用官方 OpenJDK 镜像作为基础镜像
FROM openjdk:17-jdk-alpine

# 将本地的 JAR 文件复制到容器中
# F:\Users\ancestorHZE\Desktop\homework\网络应用开发\myGPT\后端\demo\target\demo-0.0.1-SNAPSHOT.jar
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# 设置容器启动时执行的命令
ENTRYPOINT ["java","-jar","/app.jar"]

# 暴露应用端口
EXPOSE 8080