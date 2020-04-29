# 每周总结可以写在这里
1.包装对象
number、boolean和string都有包装对象
var n = new Number(123); // 123,生成了新的包装类型
var b = new Boolean(true); // true,生成了新的包装类型
var s = new String('str'); // 'str',生成了新的包装类型
虽然包装对象看上去和原来的值一模一样，显示出来也是一模一样，但他们的类型已经变为object了！
2.数字和日期对象
Number
BigInt
Math
Date
3.错误对象
Error
AggregateError
EvalError
4.基本对象
Object
Function
Boolean
Symbol
5.进制对象
Array
Int8Array
Uint8Array
Uint8ClampedArray
Int16Array
Uint16Array
Int32Array
Uint32Array
Float32Array
Float64Array
BigInt64Array
BigUint64Array
6.结构化对象
ArrayBuffer
SharedArrayBuffer 
Atomics 
DataView
JSON
7.arguments对象