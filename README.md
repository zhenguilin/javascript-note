# jsnote

### Please see issues

* JavaScript在设计之初，为了方便初学者学习，并不强制要求用var申明变量。这个设计错误带来了严重的后果：如果一个变量没有通过var申明就被使用，那么该变量就自动被申明为全局变量启用strict模式的方法是在JavaScript代码的第一行写上：`'use strict'`; 这样会强制使用var声明变量

* 对于函数`function fun(){}`,如果在js中调用`fun`，则并不是触发该函数，只是得到该函数的引用。只有`fun()`才能触发该函数

* 关于逻辑运算符与（&&）
   - 如果逻辑 与 运算符左边的值布尔转换后为true，那么返回右边的值（不管右边的值是真还是假）
   - 如果逻辑 与 运算符左边的值布尔转换后为false，那么返回左边的值
   - 但是当逻辑与的左边为 null/NaN/undefined ，结果就会得到null/NaN/undefined

* 关于逻辑运算符或（||） 
   - 如果逻辑 或 运算符左边的值布尔转换后为false，那么返回右边的值（不管右边的值是真还是假）
   - 如果逻辑 或 运算符左边的值布尔转换后为true，那么返回左边的值
   - 如果两个操作数都是是null（NaN/undefined），返回null（NaN/undefined）

**Question**
   * 面向对象编程章节暂时没有搞懂

> 内容整理自：[廖雪峰JavaScript教程](https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000)
