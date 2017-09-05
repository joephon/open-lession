# ♦️ J style 标签

在 ```HTML``` 里，有一类标签是是专门用来引入资源的，其中 style 标签算一个

除此之外 ```style``` 标签和寻常标签没啥两样

都是有开始，有结束，被包裹在 ```</>``` 一对尖括号之间

### 栗子

```html
<style>
  .niuB { color: red }
</style>
```

嵌套在 style 标签里面的东东，叫做 ```CSS``` 这里知道就好，不深究。

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .niuB { color: red }
    </style>
    ...
  </head>
  <body>
    ...
  </body>
</html>
``` 

## 小知识点

style 标签是一种资源标签，用来引入 CSS 样式

一般嵌套在 head 标签之间，为啥呢？

因为样式要优先加载，不然用户就会看到一坨木有样式的简陋页面

作为资源标签，style 即不是内联也不是块级哟


