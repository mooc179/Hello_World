# 这是一个markdown的测试文本
## 这是标题的测试方法
####
##### jsdjfdg
        
# this is a <h1> tag（一级标题）
    撒发基金了
    fhasfhaskhf
    
### This is an <h2> tag（二级标题）<h2>
    fsjakfljaf

###### afahfkasfljasjflsajfl

# 强调
*jfjjjsdfl*
_jfhjsdf_ jklsjdfl
**jfsakjfj**
_hhfhskfh **jfhashfsahf**_

*This text will be italic*（包括在两个*之间的文字为斜体，其他类似）
_This will also be italic_（斜体）
**This text will be bold**（黑体）
__This will also be bold__（黑体）
~~This text will be deleted~~（删除线）
_You **can** combine them_（可以多种格式复合使用）

# List（列表）
## Unordered（无序列表）
### _*无序列表用 - + * 任何一种都可以，注意符号和文字之间有空格！*_
#### eg
* item1
* item2
    * item2a
        * item2b
        
# Ordered(顺序列表)
*使用数字加点的方式，数字和点之间没有空格，而点和后面的文字之间有空格！无序列表和有序列表都可以进行嵌套。*
1. Item1
1. Item2
    * Item 2a(无序)
    * Item 2b(无序)
1. Item3
    1. Item 3a(有序)
        1. heng
        2. nimeizide
            * hasjhfjksahfk
    1. Item 3b(有序)
    
# Blockquotes(引用)
_**引用的内容可以用>来表示，比如文本中的所有对命令的说明都采用了引用的方式**_
> jsalfjslajflsafj
> 靠，你为什么不换行 
我不加你怎么还是引用
> 你妹子的！！！
我知道了，引用是不是只是少量所以就已行，所以，尼特么怎么取消！！！>
怎么还是绿色啊
# 我直接加个标题总不是绿色了吧
>我又来试你了
<jfkjdl 
<<>>
>stfjsdfjlsdfk  
我的方法是在两端引用中加【回车】【回车】【</br>】（或者全角空格，或者输出空格实体）

emm 好像只要加两个回车就可以了。。。。。
# Code（代码）
## Inline code（行内代码）
_**代码之间分别用一个反引号（tab上面那个）包起来**_
## Code blocks（代码块）
_**连用三个反引号将代码包起来。**_

`print('Hello world')`

```
def f(x):
  return x**2 + 2*x + 1
```

##这东西在键盘tab上面
**fu@k!!汝为何不输出** 可能jupyter notebook不支持吧，但是好像会有变化就是了
    
# Horizontal rules（分割线）

## 三个或者三个以上的 - 或者 * 都可以。

---
***
# Useful syntax（插入对象）
这一部分主要介绍如何插入一些有用的对象，比如表格、图像和公式等，以及其他一些有用的语法。
## Tabels(表格)
表格的插入非常简单，只需要按照如下语法画出表格形状即可，在编辑代码时不需要考虑对齐（但是为了美观和逻辑的直观，建议代码整齐）。竖线（|）用于分栏，短横线（-）用于分割表头和其余部分，冒号（:）用于标记表格内容的对齐方式（默认为左对齐）。如果嫌麻烦，这里有个神奇的表格生成网站，可以直接生成你所需要的代码，而且不止有Markdown代码，还有Latex和HTML代码！

|表头|表头|表头|
|:--------------|:-------------:|------------:|
|内容|内容|内容|
|内容|内容|内容|
|内容|内容|内容|
>_好像没有左右对齐的用处_

# 图像
用 ![名称](图片地址 "标题") 可以添加在线图片或本地图片，其中标题为可选项。添加本地图片需要注意，使用jupyter notebook或lab的时候，图片必须放在程序所在文件夹或所在文件夹的子文件夹下
![Github](url "title")（添加在线图片）
![Github](00000001.jpg "title")（添加本地图片）

# Links（链接）
用 [名称](地址 "标题") 可以添加超链接，语法和添加图片类似，只是少了叹号。
[GitHub](http://github.com "title")

# Equations（公式）
公式的编辑采用Latex语法，如果读者对Latex语法不熟悉，同样为大家提供一个神奇的网站。
**这是行内公式：**
$E=mc^2$（E=mc^2）
**这是公式块：**
$$
e^{i\theta} = \cos \theta +i\sin \theta \
e^z = 1 + \frac{z}{1!} + \frac{z^2}{2!} + \frac{z^3}{3!} + \cdots = \sum_{n=0}^{\infty}\frac{z^n}{n!}
$$

# Backslash（反斜线）
_如果想要插入以上内容中用到的一些符号（字面上，而非功能性应用），比如希望插入星号（*），但不是用这个星号来表示斜体或加粗等，那么可以在符号前面加反斜线（\）以插入这些普通符号。_
\ 反斜线 \` \*
` 反引号
* 星号
\* \n
_ 底线
{} 花括号
[] 方括号
() 括弧
#井字号
+ 加号
- 减号
\+
\-
. 英文句点
! 惊叹号

# Footnotes（脚注）
脚注可以用于编辑参考文献[1]。
> 在文中使用[^1]的方式标记脚注，
> 在文末使用[^1]:加入参考文献，注意要使用英文冒号，后面有无空格均可。

ksakfsdfjsdfjfjlsfjljsdjfsdjflsdjsdfj[^1];
hsdahfsdh[^2]:我是一个参考文献

# 好像没用啊
激发萨基发几[^footnote].
[^footnote]: 这里是 **脚注** 的 *内容*.
