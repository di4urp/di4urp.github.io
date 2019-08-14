# docsify 使用

[官方文档地址](https://docsify.js.org)

## 环境部署

### docsify 客户端安装

```bash
$ npm i docsify-cli -g
```

### 初始化

进入文档文件夹，并初始化目录

```bash
$ cd /path/to/doc
$ docsify init .

Initialization succeeded! Please run docsify serve .
```

目录结构如下

```bash
$ tree .
.
├── README.md
└── index.html

0 directories, 2 files
```

### 运行

```bash
$ docsify serve .

Serving /path/to/doc now.
Listening at http://localhost:3000
```

打开本地测试地址 [http://localhost:3000](http://localhost:3000)

即可查阅最简单的文档服务


