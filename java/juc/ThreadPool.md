---
title: Java 线程池
---

## 介绍

## 使用

## 实践

- 注意优雅关闭线程池

  > 项目重新部署会直接关闭JVM，如果线程池未正常关闭，会丢失任务。
  >
  > 使用Spring的ThreadPoolTaskExecutor ，Spring会注册一个ShutdownHook，在JVM关闭时会调用Bean的销毁方法。
  >
  > 在 ThreadPoolTaskExecutor 中已经写了优雅关闭的代码。
