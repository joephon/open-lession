# ♦️ Q 判断 && 遍历

关键字 ```if``` ```else``` ```map```

## 栗子

```js
if (true) {
  // 条件为真的逻辑
} else {
  // 条件为假的逻辑
}
```

```if else``` 语句需要有一个条件，写在一对圆括号里 ```()```

这个条件必须为布尔值，非 ```true``` 即 ```false```

```js
[1, 2, 3].map(function(item) {
  return item         // => 1, 2 ,3
})
```

每一个数组都内置了一个 ```map``` 方法，用于遍历数组的每一项

## 小知识点

```map``` 方法需要传入一个函数

```js
var arr = [2, 3, 4]

function func(arg) {
  return arg
}

arr.map(func)        // => 2, 3, 4
```