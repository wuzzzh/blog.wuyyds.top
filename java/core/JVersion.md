---
title: Java 主要版本特性汇总
---

## Java17

- Free Java License
- JDK 17 将取代 JDK 11 成为下一个长期支持版本
- Spring 6 和 Spring Boot 3 需要 JDK17
- 移除实验性的 AOT 和 JIT 编译器
- 恢复始终执行严格模式 (Always-Strict) 的浮点定义

## Java11

- 增加一些符串处理方法
- 用于 Lambda 参数的局部变量语法
- Http Client 重写，支持 HTTP/1.1 和 HTTP/2 ，也支持 websockets
- 可运行单一 Java 源码文件，如：java Test.java
- ZGC：可伸缩低延迟垃圾收集器
- 支持 TLS 1.3 协议

## Java8

- lambada 表达式
- 函数式接口
- 方法引用
- 默认方法
- Stream API 对元素流进行函数式操作
- Optional 解决 NullPointerException
- Date Time API
- 重复注解 @Repeatable
- Base64
- 使用元空间 Metaspace 代替持久代（PermGen space）

## Java 5

- 泛型(本质是参数化类型，解决不确定具体对象类型的问题)
- 增强的 for 循环（for-each）
- 自动装箱和自动拆箱(包装类型有：Integer,Double,Float,Long,Short,Character 和 Boolean)
- 类型安全的枚举(enum)
- 可变长度参数
- 静态引入（import static）
- 元数据（注解）
- 线程并发库（java.util.concurrent）
