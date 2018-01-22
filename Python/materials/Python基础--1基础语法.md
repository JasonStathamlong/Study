####  常用的注释
```
1.使用#单行注释
#第一个注释

2.使用'''和"""多行注释

```
#### 行与缩进

```
if Ture :
    print ("hello world")
    print ("my first python")
else :
    print ("end")
```

#### 多行语句
```
#使用\来拆分长的一行语句
str = "abc" + "bcd" + "def"

#也可以这么写
str = "abc" + \
      "bcd" + \
      "def"
#在 [], {}, 或 ()中的多行语句，不需要使用反斜杠(\)，例如：

list = ["agd","bdd"
        "fs",
        "sdf"]
```

#### 空行
函数之间和类的方法之间使用空行进行分割

#### 常用函数和输入格式

```
#注解解释器
#/usr/bin/python

#常用声明
num = 4

str = "abc"

list = [3223,"sdf",'dff']

dict = (233,'2323','df',"feew")

```

#### 同一行多条语句

```
#使用;号分割多条语句
import sys;a=7;print(a)
x="a"
y="b"
# 换行输出
print( x )
print( y )

print('---------')
# 不换行输出
print( x, end=" " )
print( y, end=" " )
print()


```
#### import 与 from...import
在 python 用 import 或者 from...import 来导入相应的模块。

将整个模块(somemodule)导入，格式为： 
import somemodule

从某个模块中导入某个函数,格式为：
from somemodule import somefunction


从某个模块中导入多个函数,格式为：
from somemodule import firstfunc, secondfunc, thirdfunc

将某个模块中的全部函数导入，格式为：
from somemodule import *
