# 一道关于C++函数声明中const关键字用法的选择题。

题目内容：
已知print()函数是一个类的常成员函数，它无返回值。下列表示中，（）是正确的。

选项有：

A. void print() const

B. const void print()

C. void const print()

D. void print(const)

解析：

• 在C++中，当一个成员函数不修改类的数据成员时，通常将其声明为const成员函数。const关键字应放在函数参数列表之后。

• 选项A：void print() const是正确的声明方式，表示print是一个不修改类数据成员的函数。

• 选项B：const void print()这种写法是错误的。const放在void前面没有意义。

正确答案是：A. void print() const

#虚函数

总结：

• 纯虚函数没有具体实现，是虚函数的一种特殊形式。

• 含有纯虚函数的类是抽象类。

• 如果派生类没有实现从基类继承来的纯虚函数，派生类仍然是抽象类。

• 抽象类通常作为基类使用，不能直接实例化对象。
