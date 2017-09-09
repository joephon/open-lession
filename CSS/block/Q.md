# ♦️ Q 定位

```HTML``` 文档流存在着多种定位模式

可使用 ```CSS``` 的 ```position``` 属性来定义

### 栗子

```css
div { position: static }

div {
  position: relative；
  left: 20px;
  top: 10px;
}

div {
  position: absolute；
  right: 20px;
  bottom: 10px;
}

div {
  position: fixed；
  left: 0;
  bottom: 0;
}

```

```static``` 是默认文档流

```relative``` 表示相对定位

```absolute``` 表示绝对定位

```fixed``` 表示固定定位

## 小知识点

```position``` 的值如果不是 ```static``` 一般与之相随的还有：

```top```、```bottom```、```left``` 和 ```right```，分别对应上、下、左、右

通常情况下，上下左右只需要写两个就可以了。






