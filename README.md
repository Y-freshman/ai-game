# 斗地主游戏项目

## 项目概述
这是一个基于前后端分离架构的斗地主游戏实现，包含Java后端和Vue.js前端。

## 技术栈
- 后端: Java + Spring Boot
- 前端: Vue.js + Webpack
- 数据库: MySQL

## 项目结构
```
ddz/
  ├── backend/        # 后端代码
  │   ├── src/        # 源代码
  │   └── pom.xml     # Maven配置文件
  └── frontend/       # 前端代码
      ├── src/        # Vue源代码
      └── package.json # 前端依赖
```

## 运行方式
### 后端
1. 确保已安装JDK和Maven
2. 在backend目录下运行: `mvn spring-boot:run`

### 前端
1. 确保已安装Node.js
2. 在frontend目录下运行:
   - `npm install`
   - `npm run dev`

## 核心功能
- 玩家身份管理(地主/农民)
- 回合结果计算
- 倍数计算系统
