---
title: "启动和关闭 postgresql"
date: 2016-01-26 15:26
---

### 1. 启动服务器

设置环境变量:

```
PGDATA=/opt/postgresql/data
export PGDATA
```

然后:
`pgctl start`

### 2. 关闭服务器

仅用于紧急关闭:

`pg_ctl stop -m fast`
