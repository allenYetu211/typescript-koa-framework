# typescript-koa-framework
用 koa v2.0 框架和 TypeScript 写的服务器端架构。

结构如下：

```
.
├── README.md
├── package.json
├── src
│   ├── config
│   │   └── index.ts
│   ├── handler
│   │   └── index.ts
│   ├── index.ts
│   ├── models
│   │   ├── User.ts
│   │   ├── db.ts
│   │   └── index.ts
│   └── routes
│       └── index.ts
├── tsconfig.json
└── typings.json
```

```
$ npm i

```

```
$ typings i

```

```
$ tsc -w

```
修改数据库连接

```
$ npm start

```

启动在 30001 端口


GET `localhost:30001/test`
