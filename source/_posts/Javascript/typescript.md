title: "typescript"
---

编程语言的类型
	* 动态类型语言(运行的时候 数据类型检查)
	* 静态类型语言(编译的时候 数据类型检查)

为什么使用
	* 程序更容易理解 >代码就是注释
	* 效率更高 >代码补全 代码跳转 接口提示
	* 更少的错误 >编译时期能够发现错误
	* 非常好的包容性 >第三方库支持

缺点

	* 学习成败 & 短期开发成本

interface
	* 对 对象的形状进行描述 shape
	* 对类 进行抽象 class
	* 鸭子类型 duck typing

class
	* class 定义了一切事物的抽象特点
	* object 类的实例
	* 面向对象 oop 三大特性：封装 继承 多态

public 是公有的，可修改，可读取的private 属性“name”为私有属性，只能在类“Animal”中访问protected 属性“name”受保护，只能在类“Animal”及其子类中访问。readonly 只读属性static 和创建的动态实例没有关系，是类自己特有的属性方法interface 定义约束内容 用implements方法 抽象类的属性和方法，定义函数的类型generics
	* 定义函数接口或者类的时候，不先指定类型，使用的时候再指定类型
	* 占位符，变量，约束
	* 约束泛型 用 extends 继承 interface

type aliases //类型别名
type assertion //类型断言

