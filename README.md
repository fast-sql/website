
![logo](logo_s.jpg)

# 简介
FastSQL一个基于spring-jdbc的简单ORM框架，它支持sql构建、sql执行、命名参数绑定、查询结果自动映射和通用DAO。结合了Hibernate/JPA快速开发和Mybatis高效执行的优点。

FastSQL可以完全满足你控制欲，可以用Java代码清晰又方便地写出sql语句并执行。 



# 如何安装

要使用 FastSQL， 只需将 fastsql-x.x.x.jar 文件置于 classpath 中即可（x.x.x为对应的版本号，下同）。

如果使用 Maven 来构建项目，则需将下面的 dependency 代码置于 pom.xml 文件中：

```xml
<dependency>
    <groupId>top.fastsql</groupId>
    <artifactId>fastsql</artifactId>
    <version>x.x.x</version>
</dependency>
```

如果使用 Gradle 来构建项目，则需将下面的代码置于 build.gradle 文件的 dependencies 代码块中：

```groovy
compile 'top.fastsql:fastsql:x.x.x'
```

# 教程

[https://github.com/fast-sql/FastSQL](https://github.com/fast-sql/FastSQL)

