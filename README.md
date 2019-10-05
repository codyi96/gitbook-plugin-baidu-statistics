# gitbook-plugin-baidu-statistics

![npm](https://img.shields.io/npm/v/gitbook-plugin-baidu-statistics)

## 简介

一个用于GitBook的百度统计插件

## 参考环境

- CLI version: 2.3.2
- GitBook version: 3.2.3

### 使用方法

1. 配置book.json
```json
...
    "plugins": [
        "baidu-statistics"
    ],
    "pluginsConfig": {
        "baidu": {
            "token": "your token"
        }
    }
...
```

2. 安装插件
```shell
gitbook install
```

## 局限性

- 使用[Dashboard](https://app.gitbook.com/)中的编辑器或 [GitHub集成](https://docs.gitbook.com/integrations/github)方式来开发GitBook的用户无法使用本插件。因为GitBook-v2版本已经不再支持插件市场，取而代之的是集成化的内部插件(详见[此处](https://docs.gitbook.com/v2-changes/important-differences#plugins))。如果需要使用本插件，请通过[gitbook-cli](https://www.npmjs.com/package/gitbook-cli)方式构建再发布。
