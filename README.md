# TS Templates

## koa ts 

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

## node ts

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

## express ts

A starter template for TypeScript and Node with a detailed README describing how to use the two together.

node + ts + express && full stack

https://github.com/microsoft/TypeScript-Node-Starter