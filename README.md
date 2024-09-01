# Spring Boot Hello World



**Spring Boot 2.x Web服务 简单输出 Hello World!**

## 如何运行

> 注：下面命令需要在`spring-boot-hello-world`目录中运行

直接运行

```
mvn spring-boot:run
```

访问服务
```
curl http://localhost:8080
```


生成jar包，含单元测试，并运行jar包

```
mvn clean install
java -jar target/spring-boot-hello-world-1.0.2.jar
```
直接生成jar包，并跳过单元测试

```
mvn clean package -DskipTests
```

  


## 单元测试



> 注：下面命令需要在`spring-boot-hello-world`目录中运行

- 运行所有测试用例

  ```
  mvn test
  ```

- 运行特定测试类

  ```
  mvn -Dtest=HelloWorldControllerTest test
  # 或
  mvn -Dtest=HelloWorldApplicationTests test
  ```
