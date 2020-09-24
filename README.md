# markdown语法:

标题：
#h1级标题
##h2级标题
###h3级标题
####h4级标题
#####h5级标题
######h6级标题

分割线：三个以上的短线 即可作出分割线

----

超链接：[连接名称](网址 , 标题)
[我是链接名](http://www.izhangbo.cn, "我是标题")
[<i class="icon-refresh"></i> 点我刷新](/sonfilename/)

另一种超链接写法：[链接名][链接代号]
[here][3]
然后在别的地方定义 3 这个详细链接信息，
[3]: http://www.izhangbo.cn "聚牛团队"

直接展示链接的写法：<http://www.izhangbo.cn>

键盘键
<kbd>Ctrl+[</kbd> and <kbd>Ctrl+]</kbd>

code格式：反引号
Use the `printf()` function.

``There is a literal backtick (`) here.""针对在代码区段内插入反引号的情况`` 

``let a = function(){
            return "sdfsdf"
        }``
强调：
*斜体强调*
**粗体强调**

图片
![美女咯](http://store.happytifyaged.com/uploads/2/1A/21A7465979.jpeg)

使用 icon 图标文字
<i class="icon-cog">111</i>

段落：以一个空行开始，以一个空行结束，中间的就是一个段落。

表格：

Item     | Value
-------- | ---
Computer | $1600
Phone    | $12
Pipe     | $1

无序列表：使用 - 加一个空格（）

- 无需列表1
- 无序列表2
- 无序列表3
- (水电费水电费)



有序列表：使用 数字 加一个英文句点

1. 有序列表
2. 有序列表
3. 有序列表
4. 有序列表
5. 有序列表

换行缩进形成代码区块

    这里先换行，然后缩进4个空格，之后的内容便可以原样显示了，适合用于显示代码内容。直到文本结束或最后一个存在缩进的行为止。 
---

块引用
>给引用的文本开始位置都加一个 '>'，
>便可组成一个块引用。在块引用中，可以结合
>其他markdown元素一块使用，比如列表。
>**强调**
也可以只在第一行加大于号，其他位置不加。

>- 块引用里使用列表，需要和上面的内容隔开一个空行
>- 记得加空格哦。
>1. 撒旦法

一级标题
=
二级标题
-
> 区块引用
>>1.内容一
>>>1.撒旦法是
>>>>2.胜多负少

    代码区域:
        function(){
            代码展示
        }

*撒旦法*
**sdfs**

***
[百度](http://www.baidu.com)

[百度翻译][1]

[1]:http://fanyi.baidu.com "bbs"



name | age
---- | ---
bbs  | sdf 
---  | ---
