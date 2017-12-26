
前端纳米学位街机游戏克隆项目
===============================

学生应该用这个[评审标准](https://review.udacity.com/#!/rubrics/499/view))来自我检查自己提交的代码。 确认自己写的函数要是**面向对象的** -  要么是类函数（就像函数 Player 和 Enemy）要么是类的原型链上的函数比如 Enemy.prototype.checkCollisions ， 在类函数里面或者类的原型链函数里面适当的使用关键词 'this' 来引用调用该函数的对象实例。最后保证你的**readme.md**文件要写明关于如何运行和如何玩你的街机游戏的指引。

关于如何开始这个项目的更详细的指导，可以查阅这份[指南](https://gdgdocs.org/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true)。

###typeof 和 instanceof 的区别
---
**typeof** 返回值是一个字符串，表明数据的类型，可返回的值包括number,String,boolean,function,object,unfined
 使用：常判断一个字符串是否被定义
 局限：null,array等特殊类型的都会返回object
 
 **instanceof**
 使用：a instanceof b ，a是否是b的实例
 