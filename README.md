# TS 模板

## 1. koa + ts

https://github.com/unix/koa-ts

```
├── app
│   ├── controllers         ---  contoller
│   ├── helpers             ---  helper func (interceptor / error handler / validator...)
│   ├── jobs                ---  task (periodic task / trigger task / email server...)
│   ├── entities            ---  database entity (model)
│   └── services            ---  adhesive controller and model
├── config
│   ├── environments        ---  environment variable
│   ├── koa.middlewares     ---  middlewares for Koa
│   ├── routing.middlewares ---  middlewares for Routing Controller
│   ├── routing.options     ---  configs for Routing Controller
│   ├── connection          ---  database connection
│   ├── bootstrap           ---  lifecycle
│   ├── customs             ---  user settings
│   └── interceptors        ---  global interceptor
│   └── utils               ---  pure functions for help
└── test
    └── apis                ---  test cases
├── variables.env           ---  environment file
```

Minimalistic project template to jump start a Node.js back-end application in TypeScript. TSLint, Jest and type definitions included.

## 2. node + ts

https://github.com/jsynowiec/node-typescript-boilerplate

Minimalistic project template to jump start a Node.js back-end application in TypeScript. TSLint, Jest and type definitions included.

What's included:

* TypeScript 3.7,
* ESLint with some initial rules recommendation,
* Jest unit testing and code coverage,
* Type definitions for Node.js and Jest,
* Prettier to enforce a consistent code style,
* NPM scripts for common operations,
* a simple example of TypeScript code and unit test,
* .editorconfig for consistent file format.

> best start for tools

## 3. express + ts

A starter template for TypeScript and Node with a detailed README describing how to use the two together.

node + ts + express && full stack

https://github.com/microsoft/TypeScript-Node-Starter

## 4. monorepo by lerna

https://github.com/Quramy/lerna-yarn-workspaces-example

How to build TypeScript mono-repo project with yarn and lerna

```
.
├── README.md
├── lerna.json
├── package.json
├── packages
│   ├── x-cli
│   │   ├── lib
│   │   │   ├── main.d.ts
│   │   │   ├── main.js
│   │   │   └── main.js.map
│   │   ├── package.json
│   │   ├── src
│   │   │   └── main.ts
│   │   └── tsconfig.json
│   └── x-core
│       ├── lib
│       │   ├── index.d.ts
│       │   ├── index.js
│       │   └── index.js.map
│       ├── package.json
│       ├── src
│       │   └── index.ts
│       └── tsconfig.json
├── tsconfig.json
└── yarn.lock
```

# node + sql 模板

* https://github.com/LFB/nodejs-koa-blog
    * api -> service -> dao -> model
    * jwt：（登录成功：jwt.sign，生成token）（每次带入token校验：obj = jwt.verify(token, secretKey)）
    * validator校验基础帮助库
* https://github.com/wclimb/Koa2-blog/
    * 使用createPool直接传入sql语法执行
    * 权限设计session。 教程：https://www.jianshu.com/p/f3df4ffe3301

详细案例实践：https://github.com/lq782655835/koa-mysql-best-experiment

# 后台管理系统模板

github 搜索关键词： antdv admin

## ElementUI组件库

### 1. https://github.com/lin-xin/vue-manage-system/

基于vue + element的后台管理系统解决方案

### 2. https://github.com/chuzhixin/vue-admin-beautiful

## Antd Vue组件库

### 1. https://github.com/vueComponent/ant-design-vue-pro

官方 antdv-pro

### 2. https://github.com/iczer/vue-antd-admin

简版antdv-pro，但代码解构罗列更好
