---
title: markdown初记
date: 2021-01-18 11:25:30
tags:
    - Markdown
---

# 一级标题  
## 二级标题  
###### 六级标题  

> 这里可以加注释

>第一层
>>第二层
>>>第三层  

脚注[^1] 

[^1]:脚注内容


*斜体/这里的 * 和_作用一样*  
_斜体_  
**两个 * 是粗体**  
***三个 * 是斜加粗***  
~~两个~是删除线~~  
<u>用html中的 < u >加下划线</u>

[点击前往百度](http://www.baidu.com)  
<http://www.baidu.com>  

这里用 1 做变量网址[百度][1]  
这里用 2 做变量网址[谷歌][2]  
> 这里记得空行

[1]:https://www.baidu.com/  
[2]:http://www.google.cn/


+ 无序列列表+
+ 无序列列表+
    + 无序列列表+
    + 无序列表+
        + 无序列列表
        + 无序列列表
            + 无序列列表

- 无序列列表-
- 无序列列表-

* 无序列列表*  
    无序列小段

* 无序列列表*  

1. 有序列表1  
    * 列表嵌套1
    * 列表嵌套1  
2. 有序列表2    
    * 列表嵌套2  
    * 列表嵌套2  
3. 有序列表3


*    段落一
  
     小段一
*    段落二

     小段二
    
* 段落一
    > 区块标记一，首端缩进4个空格，即一个tab间距
* 段落二
    > 区块标记二

上面
***
这里是一条分割线
___
下面    

这里是变量名内容`filter`

``
fun (x: Int, y: Int): Int {
  return x + y
}
``

```c++
fun (x: Int, y: Int): Int {
  return x + y
}
```

```html
<div class="card">
    <div class="card-content">
        <div class="card-content article-card-content">
                <div class="title center-align" data-aos="zoom-in-up">
                    <i class="fa fa-address-book"></i>&nbsp;&nbsp;<%- __('myCV') %>
                </div>
                <div id="articleContent" data-aos="fade-up">
                    <%- page.content %>
                </div>
        </div>
    </div>
</div>
```

左对齐|右对齐|居中
:---|---:|:---:|
行1|行1|行1
行2|行2|行2
行3|行3|行3

>三个短斜杠左右的冒号用于控制对齐方式，只放置左边冒号表示文字居左，只放置右边冒号表示文字居右，如果两边都放置冒号表示文字居中。

普通换行在一行文字后两个空格  
就像这样，
如果没有就是这样 

当然，也可以直接选择空一行开始新段落
