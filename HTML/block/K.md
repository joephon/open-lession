# ♦️ K 综合练习

在 ```HTML``` 里，还有一个资源标签叫 script

script 的意思是：脚本，顾名思义 script 标签引入的定然是脚本语言了

没错，你猜对了，被嵌套在 ```<script />``` 标签里的正是 JS 

### 栗子

```html
<script>
  var a = "niuB!"
</script>

<script src="https://newteo.com/static/js/demo.js"/>
```

嵌套在 script 标签里面的东东，叫做 ```JavaScript``` 也就是 ```JS``` 一句带过，不深究。

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="https://newteo.com/static/js/demo.js"/>
    ...
  </head>
  <body>
    <script>
      var a = "niuB!"
    </script>
    ...
    <script src="https://newteo.com/static/js/demo2.js"/>
  </body>
</html>
``` 

## 小知识点

script 标签是一种资源标签，用来引入 ```JS``` 代码

可以被嵌套在 head 和 body 之间

有两种书写方式，注意到了吗？自闭合、带 src 属性的模式，和开标签、闭标签模式

作为资源标签，script 和 style 一样，即不是内联也不是块级哟


