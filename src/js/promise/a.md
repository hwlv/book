### promise的特性



### 案例参考

1. promise 交替执行
```js

Promise.resolve()
  .then((res) => {
    console.log(1);
  })
  .then((res) => {
    console.log(2);
  })
  .then((res) => {
    console.log(3);
  })
  .then((res) => {
    console.log(4);
  })
  .then((res) => {
    console.log(5);
  });

Promise.resolve()
  .then((res) => {
    console.log(10);
  })
  .then((res) => {
    console.log(20);
  })
  .then((res) => {
    console.log(30);
  })
  .then((res) => {
    console.log(40);
  })
  .then((res) => {
    console.log(50);
  });

```