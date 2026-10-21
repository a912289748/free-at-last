# free-at-last

一个只有一个目的的网页：显示距离 **2027-01-29** 还有多少天。

## 用法

直接用浏览器打开 `index.html` 即可。

线上地址（GitHub Pages）：
https://a912289748.github.io/free-at-last/

## 修改目标日期

编辑 `index.html` 里的这一行：

```js
const TARGET = new Date(2027, 0, 29, 0, 0, 0); // 2027-01-29 本地时间 00:00
```

改完 push，GitHub Pages 会自动更新（通常 1-2 分钟）。