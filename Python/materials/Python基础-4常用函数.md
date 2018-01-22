#### 1.数字

Python 数字类型转换

---
```
int(x) 将x转换为一个整数。

float(x) 将x转换到一个浮点数。

complex(x) 将x转换到一个复数，实数部分为 x，虚数部分为 0。

complex(x, y) 将 x 和 y 转换到一个复数，实数部分为 x，虚数部分为 y。x 和 y 是数字表达式。

abs(x)	返回数字的绝对值，如abs(-10) 返回 10

ceil(x)	返回数字的上入整数，如math.ceil(4.1) 返回 5

cmp(x, y)
如果 x < y 返回 -1, 如果 x == y 返回 0, 如果 x > y 返回 1。 Python 3 已废弃 。使用 使用 (x>y)-(x<y) 替换。

exp(x)	返回e的x次幂(ex),如math.exp(1) 返回2.718281828459045

fabs(x)	返回数字的绝对值，如math.fabs(-10) 返回10.0

floor(x)	返回数字的下舍整数，如math.floor(4.9)返回 4

log(x)	如math.log(math.e)返回1.0,math.log(100,10)返回2.0

log10(x)	返回以10为基数的x的对数，如math.log10(100)返回 2.0

max(x1, x2,...)	返回给定参数的最大值，参数可以为序列。

min(x1, x2,...)	返回给定参数的最小值，参数可以为序列。

modf(x)	返回x的整数部分与小数部分，两部分的数值符号与x相同，整数部分以浮点型表示。

pow(x, y)	x**y 运算后的值。

round(x [,n])	返回浮点数x的四舍五入值，如给出n值，则代表舍入到小数点后的位数。

sqrt(x)	返回数字x的平方根。

随机数函数
choice(seq)	从序列的元素中随机挑选一个元素，比如random.choice(range(10))，从0到9中随机挑选一个整数。

randrange ([start,] stop [,step])	从指定范围内，按指定基数递增的集合中获取一个随机数，基数缺省值为1

random()	随机生成下一个实数，它在[0,1)范围内。

seed([x])	改变随机数生成器的种子seed。如果你不了解其原理，你不必特别去设定seed，Python会帮你选择seed。

shuffle(lst)	将序列的所有元素随机排序
uniform(x, y)	
随机生成下一个实数，它在[x,y]范围内。

random.randint(x,y)　#随机生一个整数int类型，可以指定这个整数的范围

random.sample(sequence,length) 可以从指定的序列中，随机的截取指定长度的片断，不修改原序列。
```

---


#### 2.字符串

```
Python字符串运算符

a = "abc"
b = a + "sd"

#+ 拼接

#字符串格式化

print ("我叫 %s 今年 %d 岁!" % ('小明', 10))

a.len() #a的大小

a.rstrip() #去掉多余的行终止符  

```

#### 3.条件控制

```
if condition_1:
    statement_block_1
elif condition_2:
    statement_block_2
else:
    statement_block_3
    
num=int(input("输入一个数字："))
if num%2==0:
    if num%3==0:
        print ("你输入的数字可以整除 2 和 3")
    else:
        print ("你输入的数字可以整除 2，但不能整除 3")
else:
    if num%3==0:
        print ("你输入的数字可以整除 3，但不能整除 2")
    else:
        print  ("你输入的数字不能整除 2 和 3")
        
#循环语句

n = 100
 
sum = 0
counter = 1
while counter <= n:
    sum = sum + counter
    counter += 1
 
print("1 到 %d 之和为: %d" % (n,sum))

#在 while … else 在条件语句为 false 时执行 else 的语句块：
count = 0
while count < 5:
   print (count, " 小于 5")
   count = count + 1
else:
   print (count, " 大于或等于 5")


#for循环

for <variable> in <sequence>:
    <statements>
else:
    <statements>


sites = ["Baidu", "Google","Runoob","Taobao"]
for site in sites:
    if site == "Runoob":
        print("菜鸟教程!")
        break
    print("循环数据 " + site)
else:
    print("没有循环数据!")
print("完成循环!")


>>>a = ['Google', 'Baidu', 'Runoob', 'Taobao', 'QQ']
>>> for i in range(len(a)):
...     print(i, a[i])
... 
0 Google
1 Baidu
2 Runoob
3 Taobao
4 QQ
>>>

var = 10                    # 第二个实例
while var > 0:              
   print ('当期变量值为 :', var)
   var = var -1
   if var == 5:
      break
 
print ("Good bye!")

for letter in 'Runoob':     # 第一个实例
   if letter == 'o':        # 字母为 o 时跳过输出
      continue
   print ('当前字母 :', letter)
 
var = 10                    # 第二个实例
while var > 0:              
   var = var -1
   if var == 5:             # 变量为 5 时跳过输出
      continue
   print ('当前变量值 :', var)
print ("Good bye!")










```




































