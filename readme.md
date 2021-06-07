# markdown

- githubのマークダウンのテストをする

```js
console.log("OK")
```

```ts
console.log("OK")
```

```py
if (a) :
    print("hello")
```

# 駄目なパターン

```js:test
console.log("OK")
```

```js: test
console.log("OK")
```
```js :test
console.log("OK")
```


# 行けるパターン

```js : test
console.log("OK")
```

```js,test
console.log("OK")
```

- `,` ならくっつけても行ける
- `:` は両方にスペースが必要