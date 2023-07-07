# 标题
1、要创建标题，请在单词或短语前面添加井号 (#) 。# 的数量代表了标题的级别。例如，添加三个 # 表示创建一个三级标题

2、还可以在文本下方添加任意数量的 == 号来标识一级标题，或者 -- 号来标识二级标题

# 段落
要创建段落，请使用空白行将一行或多行文本进行分隔

要创建段落，请使用空白行将一行或多行文本进行分隔

# 换行
1、行尾添加“结尾空格”或 HTML 的<br\> 标签来实现换行<br>
2、无须在行尾添加任何内容，只须键入回车键（return）即可实现换行

无须在行尾添加任何内容，只须键入回车键（return）即可实现换行


# 强调语法
**双星号包裹加粗体**

# 斜体
*单星号包裹加斜体*

# 引用
> 要创建块引用，请在段落前添加一个 > 符号
>
> 块引用可以包含多个段落。为段落之间的空白行添加一个 > 符号
>
>> 块引用可以嵌套。在要嵌套的段落前添加一个 >> 符号
>
> ## 块引用可以包含其他 Markdown 格式的元素。并非所有元素都可以使用

# 列表
## 有序列表
要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始
1. first line
3. two line
4. three line
    1. five line
    2. ten line

## 无序列表
要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表
* first line
* second line
* three line
    * five line
    * six line
    > 要在保留列表连续性的同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符<br>
    代码块通常采用四个空格或一个制表符缩进。当它们被放在列表中时，请将它们缩进八个空格或两个制表符。

        <html>
          <head>
            <title>Test</title>
          </head>
 * and  line

# 代码
要将单词或短语表示为代码，请将其包裹在反引号 (`) 中

```java
 public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello, World");
        }
 }
 ```

# 分割线
要创建分隔线，请在单独一行上使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容
___

要创建分隔线，请在单独一行上使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容


# 链接
链接文本放在中括号内，链接地址放在后面的括号中，链接title可选

这是一个链接 [MarkDown语法](https://markdown.com.cn "超链接title")

这是一个图片 
![这是一个图片](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "图片超链接")

给图片添加超链接
[![这是一个图片](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "图片超链接")](https://markdown.com.cn)

## 网址和email
<https://markdown.com.cn>

<fake@example.com>

## 带格式化的链接
I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

## 引用类型链接
引用类型的链接的第一部分使用两组括号进行格式设置。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接

[test-demo][1]


[1]:https://en.wikipedia.org/wiki/Hobbit#Lifestyle


# 转义
显示原本用于格式化 Markdown 文档的字符，请在字符前面添加反斜杠字符 \ 

# 表格
要添加表，请使用三个或多个连字符（---）创建每列的标题，并使用管道（|）分隔每列。您可以选择在表的任一端添加管道

| name | age |sex|
| :-- | ---: |:---:
|张三|18  | 男|
|王五|19|女|

# 删除线
~~删除~~

