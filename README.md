## 测试用例

```js
// bad
var a = 1;
var b = 2;

// good
const c = 1;
const d = 2;

const message = "hello world";

console.log(a, b, c, d, message);
```

### 注意

airbnb 规范 推荐使用分号(;)

但是我不想用分号

```js
// prettierrc
{
    "semi": false // 失效
}

```

```js
// eslintrc
"rules": {
    "semi": ["error", "never"] // 禁止在语句末尾使用分号
}
```
