# Spring源码学习

——《Spring源码深度解析》 郝佳 著

<div style="page-break-after:always;"></div>

[TOC]

## 第1章 Spring整体架构和环境搭建

略

## 第2章 容器的基本实现

### 2.1 核心类介绍

1. `DefaultListableBeanFactory`

   整个bean加载的核心部分，是Spring注册及加载 `bean` 的默认实现。

   - `AlisaRegistry` : 定义对`alias`的简单增删改等操作。
   - 

2. `XmlBeanDefinationReader`
