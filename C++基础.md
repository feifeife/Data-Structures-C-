### 数据类型
- int：4个字节
- double：8个字节
- bool/char：1个字节
### 声明和定义
- 声明：指定变量或函数类型，“如何使用一个实体”。可以进行初始化

`int x{9}`

`double sqrt(double d)`
- 定义：也是一个声明。分配存储空间。“这个实体要干什么”
```c++
double sqrt(double d){
...
}
```
**因为每个名字都要先声明在使用，所以有时会在开头先声明函数，（也可以不声明），这样之后写函数时不用考虑调用顺序**
### 姓名空间namespace
使用姓名空间内部的函数名字就不会引起冲突。如`Graph::color`和`Text::color`

`using namespace std //使用std中的姓名直接可以使用`
