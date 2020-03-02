# Spring Boot参考文档










## 4. Spring Boot功能






# 4.1. SpringApplication

SpringApplication类用于从main()方法启动Spring应用程序。很多情况下，可以委托给SpringApplication.run静态方法：

```java
public static void main(String[] args) {
    SpringApplication.run(MySpringConfiguration.class, args);
}
```

输出信息：

```
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::   v2.2.2.RELEASE

2019-04-31 13:09:54.117  INFO 56603 --- [main] o.s.b.s.app.SampleApplication: Starting SampleApplication v0.1.0 on mycomputer with PID 56603 (/apps/myapp.jar started by pwebb)
2019-04-31 13:09:54.166  INFO 56603 --- [main] ationConfigServletWebServerApplicationContext: Refreshing org.springframework.boot.web.servlet.context.AnnotationConfigServletWebServerApplicationContext@6e5a8246: startup date [Wed Jul 31 00:08:16 PDT 2013]; root of context hierarchy
2019-04-01 13:09:56.912  INFO 41370 --- [main] .t.TomcatServletWebServerFactory: Server initialized with port: 8080
2019-04-01 13:09:57.501  INFO 41370 --- [main] o.s.b.s.app.SampleApplication: Started SampleApplication in 2.992 seconds (JVM running for 3.658)
```










































































