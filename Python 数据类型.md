# Python 数据类型

不可变数据：Number （数字），String （字符串），Tuple （元组）

可变数据：List （列表），Dictionary （字典），Set （集合）

## Number （数字）

Pyhton3 中的数字类型有 int 整型，float 浮点数，bool 布尔值，complex 复数

### int  （整型）



### float （浮点数）

浮点数由整数部分和小数部分组成。

浮点数在运算时可能会出现误差，整数运算则不会。

### bool （布尔值）

对于一个布尔值，只有两种结果即 Ture 和 False，也可以用 1 和 0 来表示。

其中 False 等价于None , 不含任何值的空数据结构（如： [ ] , ( ) ,{ } , ' '）以及 0 。

### * 空值

空值是 Python 中一个特殊的值，用 None 表示。

需要注意的是 None 与不含任何值的空数据结构不相等。

### complex （复数）

复数由 real 实部和 imag 虚部两个浮点数组成，形如  `1+2j` ，其中 j 不区分大小写

### 方法

* <b>`int( )`, `float( )` , `complex( )`</b> 通过这三个函数，数字之间可以相互转换，其中复数需要对实部和虚部单独转化。

  ```python
  #!/usr/bin/python
  
  >>> a = 1+2j
  >>> int(a)
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  TypeError: can't convert complex to int
  >>> int(a.real)
  1
  >>> int(a.imag)
  2
  ```

* <b> `round( )` </b> 通过 `round( )`方法可以改变浮点数的显示精度

  

* <b>数值运算</b>

  

## String （字符串）



## List （列表）



## Tuple （元组）



## Set （集合）



## Dictionary （字典）





