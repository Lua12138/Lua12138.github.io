---
title: 测试文章案例
date: 2017-08-09
update: 2017-08-10
comments: true
categories: 
    - 未分类
permalink: demo-aricle
---

# 格式说明

头部为yml格式，定义文章相关属性

```
title: 文章标题
date: 创建日期
update: 修改日期
comments: [true | false] 是否允许评论 默认true
categories: 
    - 未分类 // 文章分类
permalink: demo-aricle // url中显示的名称
```

yml格式的元数据由`---`分割，之后为标准的markdown格式的文章正文。