# ♦️ J 函数（下）

函数在声明的时候，可以拥有自己的参数

```js
function func(arg) {
  // 函数体
}
```

其中 ```arg``` 就是函数 ```func``` 的参数

函数的参数写在圆括号内，可以有多个，表示 ```从函数外部传入函数内部的数据```

```js
// 声明
function name(arg, arg2) {
  return arg + arg2
}

// 调用
name(1, 2)           // => 3
```

其中 ```arg``` 和 ```arg2``` 是形参

```1``` ```2``` 是实参

```return``` 是 ```JS``` 的关键字，表示 ```返回``` 也表示 ```逻辑结束```

## 小知识点

在 ```JS``` 里，所有函数都有一个默认的 ```返回值``` ：```undefined```

声明函数时，定义的参数叫 ```形参```

调用函数时，输入的参数叫 ```实参```

函数可以有任意类型的返回值 ```Number``` ```String``` ```Array``` ```Object``` ```null``` ```undefined```

甚至，函数也能返回函数 ```function```

