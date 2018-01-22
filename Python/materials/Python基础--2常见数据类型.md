#### 1.常见赋值
```
num = 4
str = "few"
str1 = 'sfd'

a = b = c = 1

a , b, c = 1 , 2, '32'



```

#### 2.标准数据类型

Python3有六种标准数据类型

- Number(数字)
- String(字符串)
- List(列表)
- Tuple(元组)
- Sets(集合)
- Dict(字典)


```
#数字 int float bool complex

a, b, c, e = 1, 23.23, True ,4+4j

#字符串 Python中的字符串不能改变
#加号（+）是列表连接运算符，星号（*）是重复操作
str = 'abcdef'
str1 = "bcdeffaf"

print (str)          # 输出字符串
print (str[0:-1])    # 输出第一个到倒数第二个的所有字符
print (str[0])       # 输出字符串第一个字符
print (str[2:5])     # 输出从第三个开始到第五个的字符
print (str[2:])      # 输出从第三个开始的后的所有字符
print (str * 2)      # 输出字符串两次
print (str + "TEST") # 连接字符串

#列表 List
list = [ 'abcd', 786 , 2.23, 'runoob', 70.2 ]
tinylist = [123, 'runoob']
 
print (list)            # 输出完整列表
print (list[0])         # 输出列表第一个元素
print (list[1:3])       # 从第二个开始输出到第三个元素
print (list[2:])        # 输出从第三个元素开始的所有元素
print (tinylist * 2)    # 输出两次列表
print (list + tinylist) # 连接列表

#元组 元组与列表不同之处在于不能修改
tuple = ( 'abcd', 786 , 2.23, 'runoob', 70.2  )
tinytuple = (123, 'runoob')
 
print (tuple)             # 输出完整元组
print (tuple[0])          # 输出元组的第一个元素
print (tuple[1:3])        # 输出从第二个元素开始到第三个元素
print (tuple[2:])         # 输出从第三个元素开始的所有元素
print (tinytuple * 2)     # 输出两次元组
print (tuple + tinytuple) # 连接元组

#集合（set）是一个无序不重复元素的序列
student = {'Tom', 'Jim', 'Mary', 'Tom', 'Jack', 'Rose'}
 
print(student)   # 输出集合，重复的元素被自动去掉
 
# 成员测试
if('Rose' in student) :
    print('Rose 在集合中')
else :
    print('Rose 不在集合中')
 
 
# set可以进行集合运算
a = set('abracadabra')
b = set('alacazam')
 
print(a)
 
print(a - b)     # a和b的差集
 
print(a | b)     # a和b的并集
 
print(a & b)     # a和b的交集
 
print(a ^ b)     # a和b中不同时存在的元素

#字典 键值对
dict = {}
dict['one'] = "1 - 菜鸟教程"
dict[2]     = "2 - 菜鸟工具"
 
tinydict = {'name': 'runoob','code':1, 'site': 'www.runoob.com'}
 
 
print (dict['one'])       # 输出键为 'one' 的值
print (dict[2])           # 输出键为 2 的值
print (tinydict)          # 输出完整的字典
print (tinydict.keys())   # 输出所有键
print (tinydict.values()) # 输出所有值

dict1 = {'abc':1,"cde":2,"d":4,"c":567,"d":"key1"}
for k,v in dict1.items():
    print(k,":",v)
    
Python数据类型转换

int(x [,base])： 将x转换为一个整数
float(x) ：将x转换到一个浮点数
complex(real [,imag])：创建一个复数
str(x)：将对象 x 转换为字符串
repr(x)：将对象 x 转换为表达式字符串
eval(str)：用来计算在字符串中的有效Python表达式,并返回一个对象
tuple(s)：将序列 s 转换为一个元组
list(s)：将序列 s 转换为一个列表
set(s)：转换为可变集合
dict(d)   ：创建一个字典。d 必须是一个序列 (key,value)元组。

```

















