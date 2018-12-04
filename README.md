## 数值扩展
```
// 是否为整数 Number.isInteger
console.log(Number.isInteger(1));
console.log(Number.isInteger(1.00));
console.log(Number.isInteger(1.1));
// 输出结果
// true
// true
// false

// Number 最大值 最小值
console.log(Number.MAX_SAFE_INTEGER,Number.MIN_SAFE_INTEGER);
// 输出结果
// 9007199254740991 -9007199254740991

// Number 是否为安全的树 Number.isSafeInteger
console.log(Number.isSafeInteger(1));
console.log(Number.isSafeInteger(564444444444444444444444444444444444444444444444444444));
console.log(Number.isSafeInteger('acc'));
// 输出结果
// true
// false
// false

// 取整 Math.trunc
console.log(Math.trunc(3.23123))
console.log(Math.trunc(3.9))
// 输出结果
// 3
// 3

// 正负数与0的判断 Math.sign
console.log(Math.sign(0));
console.log(Math.sign(4));
console.log(Math.sign(-45));
// 输出结果
// 0
// 1
// -1

// 有效数字的判断 Math.sign
console.log(Math.sign('500'));
console.log(Math.sign('foo'));
console.log(Math.sign('-34.5'));
// 输出结果
// 1
// NaN
// -1

// 立方根 Math.cbrt
console.log(Math.cbrt(-1))
console.log(Math.cbrt(8))
// 输出结果
// -1
// 2
```
