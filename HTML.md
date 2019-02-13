## 默认文档结构

``` html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,user-scalable=0">
  <title>Document</title>
  <meta name="keywords" content="">
  <meta name="description" content="">
  <link rel="dns-prefetch" href="">
  <link rel="shortcut icon" href="" type="image/x-icon">
  <link rel="stylesheet" type="text/css" href="">
</head>
<body>
  <div></div>
</body>
</html>
```

## 语法

- 缩进使用soft tab（2个空格）；
- 嵌套的节点应该缩进
- 在属性上，使用双引号，不要使用单引号；
- 属性名全小写，用中划线做分隔符；

## 属性顺序

- class：高可复用组件设计的，所以应处在第一位
- id：更加具体且应该尽量少使用，所以将它放在第二位
- name
- data-*
- src, for, type, href, value , max-length, max, min, pattern
- placeholder, title, alt
- aria-*, role
- required, readonly, disabled

## JS生成标签

在JS文件中生成标签让内容变得更难查找，更难编辑，性能更差。应该尽量避免这种情况的出现

## 减少标签数量

在编写HTML代码时，需要尽量避免多余的父节点；
很多时候，需要通过迭代和重构来使HTML变得更少。
