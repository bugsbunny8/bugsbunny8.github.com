---
layout: page
title: "MarkdownCheetSheet"
description: ""
---
{% include JB/setup %}

#<div align=center>Markdown示例文档<div>
#简介
Markdown标记不支持任何格式，包括：
* 居中
* 右对齐之类

可以通过内嵌HTML语言来进行相应的实现。
'<div align=center> <div></code>

水平线
<hr />
或者如下方式：

---

本文做一个系统的markdown语言
#示例

##标题

#第一级标题

##第二级标题

###第三级标题

####第四级标题

##区块引用

>测试一大堆文件
>
>2

##图片
>![图片描述](图片链接)

![test](test.jpg)

##强调
斜体
>*hello*

效果：*hello*

粗体**加粗文字**

##无差别列表：
* 1
* 2

- Item
- Item
- Item

##列表下的列表
* 1
 * 1
 * 2

##内联格式
Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

##多行强调
测试下文,也就是~键对应的`，而不是’。
```
x = 0
x = 2 + 2
what is x
```

##链接
[测试中文](http://www.google.com)

---

##Github相关的Markdown
~~111~~

http://www.google.com

```
function test() {
  console.log("notice the blank line before this function?");
}
```

```c
    printf("hello\n");
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

###表格
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

##task list

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

##特殊字符emoji
详细的示例可以看：[emoji-cheat](http://www.emoji-cheat-sheet.com/)

:smile:
:dog:
:rooster:
:tada:
:fireworks:

