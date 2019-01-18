# E-commerce

一个涵盖了Vue、Nuxt.js、Koa2、Mongodb、Redis等众多前后端技术并结合element-ui的电商项目。

## 项目简介
**主要功能：**

- 登录注册
- SMTP服务（邮箱验证）
- 组件复用设计、接口设计
- 搜索、推荐服务
- 城市、定位、地图服务
- 服务端缓存

**技术内容：**

- Vue 2.5语法
- [Vue CLI3](https://cli.vuejs.org/zh/)脚手架
- Vuex实现数据和状态的同步
- Nuxt.js和Koa2实现SSR
- redis服务端缓存
- Mongoose来管理Mongodb数据库

## 项目开发

### 环境准备

node v10.14.0

Vue 2.5.21

npm v6.5.0

webpack v4.28.3

Nuxt v2.3.4

### 项目安装

1. `npm install -g npx`
2. `npx creat-nuxt-app E-commerce`

### 辅助工具安装

- 安装mongodb数据库 [文档](https://mongoose.shujuwajue.com/guide/models.html)
- 安装Robo 3T [Download](https://robomongo.org/download)

### 开始项目

1.  `npm i -g @vue/cli`
2. `vue creat E-commerce`
3. `cd E-commerce `
4. `npm run serve`

### 开发首页

#### 需求分析

**1. 模板设计**

![image-20190117111814632](./readmePic/image-20190117111814632.png)

[Element ui 容器布局](http://element-cn.eleme.io/#/zh-CN/component/container)

**2. 组件设计** 

- 城市服务组件
- 用户数据和状态

**3. 数据结构设计**

**4. 接口设计**

### 登录注册

### Search搜索

## 项目总结和感想

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).