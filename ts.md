## npm 全局安装
---

```shell
npm install -g typescript
```

<br>
<br>
<br>

## 尝试第一段代码
---

```js
function greeter(person: string) {
    return "Hello, " + person;
}

let user = "Jane User";

document.body.innerHTML = greeter(user);
```

!> 需要注意, 文件后缀名为`.ts`