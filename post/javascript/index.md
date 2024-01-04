# 

# 数组方法





# Map and Set（映射和集合）

创建一个函数 `unique(arr)`，该函数返回一个由 `arr` 中所有唯一元素所组成的数组。

```javascript
 function unique(arr) {
  return Array.from(new Set(arr))
}

let values = ["Hare", "Krishna", "Hare", "Krishna",
  "Krishna", "Krishna", "Hare", "Hare", ":-O"
];

alert( unique(values) ); // Hare, Krishna, :-O
```

P.S. 这里用到了 string 类型，但其实可以是任何类型的值。



# 函数

###  匿名函数

函数是对象所以可以通过赋值来指向到函数对象的指针，当然指针也可以传递给其他变量，注意后面要以`;`结束。下面使用函数表达式将 `匿名函数` 赋值给变量

```text
let hd = function(num) {
  return ++num;
};

console.log(hd instanceof Object); //true

let cms = hd;
console.log(cms(3));
```








