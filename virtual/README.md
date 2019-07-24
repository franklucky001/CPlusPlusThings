# virtual那些事

## 关于作者：

个人公众号：

![](../img/wechat.jpg)

## 1.虚函数与运行多态

对应的代码：[emp.cpp](./set1/emp.cpp)

**虚函数的调用取决于指向或者引用的对象的类型，而不是指针或者引用自身的类型。**

## 2.vptr与vtable

见[vptr_vtable那些事](../vptr_vtable)

## 3.虚函数中默认参数

对应的代码：[default_arg.cpp](./set2/default_arg.cpp)

**默认参数是静态绑定的，虚函数是动态绑定的。 默认参数的使用需要看指针或者引用本身的类型，而不是对象的类型**。

## 4.可以不可以

（1） **静态函数可以声明为虚函数吗？**