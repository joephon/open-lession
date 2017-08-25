# ♦️ K 综合实操

写一个函数来遍历一个数组的每一项

在遍历之前，需要判断输入的参数类型是否为数组

如果是，则遍历并打印数组的每一项

如果不是，直接返回，什么也不做

## 栗子

```js
// 声明
var arr = ["小白", "新手", "高手", "大神"]

function mission(arr) {
  var condition = arr instanceof Array
  if (!condition) {
    return 
  } 
  arr.map(function(item) {
    console.log(item)
  }) 
}

// 调用
mission(arr)           // => "小白", "新手", "高手", "大神"
mission()              // => undefined
mission("arr")         // => undefined
mission(1)             // => undefined
mission({})            // => undefined
```

## 小知识点

```instanceof``` 是 ```JS``` 的关键字，常用于判断数据类型

```JS``` 代码执行顺序是 ```由上而下```