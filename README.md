GUI是图形用户界面，用VB(Visual Basic)实现。

十进制：123 是 1 在百位，2 在十位、3在个位 1* 100+2* 10+3* 1=123。

二进制：7是1在4位，1在2位，1在个位 1* 4+1* 2+1* 1=7 7在二进制中表示为110，65535表达为2进制是16个1，bit是二进制中最小的位，八个比特为一个字节。ASCII是计算机的摩斯密码，在ASCII中大写A的编码为65，所以当我们在键盘上输入A时，在计算机二进制的存储中A被表示为1000001。

***

### 计算机组成结构
#### 硬件
中央处理器 存储器（区分内存和硬盘）输入设备（键盘、鼠标）输出设备（音响、显示器）
#### 软件
系统软件：win Linux Mac等
应用软件：wx b站等 应用软件又分为两类，需要提前安装（客户端）再去使用的软件我们称为C/S架构的软件，不需要提前安装（网页端）的称为B/S架构的软件。

***

### HTML
#### 超文本标记语言
单标签`<input/>`

大部分为双标签：起始标签 结束标签
```
<marquee>reno<input></marquee> 
<input>
```

#### 标签属性
每个属性前都要有空格，id为通用属性，标签及标签属性不区分大小写，同一个标签写两个相同的属性，只会执行第一个属性。
```
<marquee loop="1" bgcolor="orange">reno<input type="password"></marquee> 
<input disable> 
```
```
<html>
  <head>
    <title>my-study-notes</title>
  </head>
  <body>
    <marquee>reno<input></marquee> <img><内联框架><a>
  </body>
</html>
```
