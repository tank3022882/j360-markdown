Markdown 语法说明
=================
### [参考原文地址](http://wowubuntu.com/markdown/ "点击查看")
### [接口文档范例](doc/demo.md "Demo")
兼容HTML
-------------

<h3>标题</h3>
<h4>标题</h4>

<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>

<ul>
<li><p>Bird</p></li>
<li><p>Magic</p></li>
</ul>

<table>
    <tr>
        <td>Foo</td><td>Foo</td>
    </tr>
    <tr>
        <td>Foo</td><td>Foo</td>
    </tr>
</table>

Markdown
-------------

# 标题1级
## 标题2级 ##
### 标题3级
#### 标题4级
##### 标题5级 ####
###### 标题6级 #

最高阶标题
===
第二阶标题
---

> 引用块
> 并不会换行
>
> 需要空一行

> 引用块
可以偷懒不写
还是同一行
>> 嵌套引用块
>>> 无限嵌套

* 列表1
* 列表2
* 列表3

等同于：

+ 列表1
+ 列表2
+ 列表3

等同于：

- 列表1
- 列表2
- 列表3

等同于：

1. 列表1
2. 列表2
3. 列表3

玩的6：

6. 列表1
3. 列表2
4. 列表3

段落：

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.
    > 段落内引用
    
忽略：

123. 1213

123\. What a great season.

   	//代码块
    System.out.println("hello world");

这里是分割线

***

---

*强调\<em\>* 

_强调_

**强调\<strong\>**

__强调__

一段代码 `println()` `<div>`

插入反引号： `` ` ``

同样的： `` `foo` ``

这里有一个[链接](http://www.baidu.com/ "百度")

[相对路径](test.md)

参考式的 [链接] [link]

  [link]: http://www.baidu.com/ '点击打开'
  [link]: http://www.fanxiao.com.cn/ '点击打开'

隐式链接标记[Google][]

  [Google]: http://google.com/ (点击打开)

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

这里有一张图片![图片](http://www.fanxiao.com.cn/site//images/image-06.png "这是一张图片")

![图片][id]

  [id]: image/icon.png 

<http://www.baidu.com/>

<595978937@qq.com>

\*忽略\*

\\   反斜线

\`   反引号

\*   星号

\_   底线

\{\}  花括号

\[\]  方括号

\(\)  括弧

\#   井字号

\+   加号

\-   减号

\.   英文句点

\!   惊叹号

| 参数名 | 参数类型 | 是否必填 | 描述 | 
|---|---|---|---|
| username | String | 必填 | 用户账号 | 
| password | String | 必填 | 用户密码 | 

