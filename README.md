# 基本语法

## 基础

|           效果            | markdown 语法                                |
|:-----------------------:|--------------------------------------------|
|      标题 (Heading)       | \# H1 \#\# H2 \#\#\# H3                    |
|        粗体 (Bold)        | \*\*bold text\*\*                          |
|       斜体 (Italic)       | \*italicized text\*                        |
|   删除线 (Line Through)    | \~\~line through\~\~                       |
|    引用块 (Blockquote)     | \> blockquote                              |
|   有序列表 (Ordered List)   | 1. First item 2. Second item 3. Third item |
|  无序列表 (Unordered List)  | - First item - Second item - Third item    |
|        代码 (Code)        | \`code\`                                   |
|  分隔线 (Horizontal Rule)  | ---                                        |
|        链接 (Link)        | \[title\](http://www.example.com)          |
|       图片 (Image)        | !\[alt text\](./path/to/image.jpg)         |

## 表格 [syntax](https://github.com/GitbookIO/markdown/blob/master/syntax/tables.md)
> 使用`:`来控制对齐

| 左对齐             |              右对齐 |      居中对齐       |
|:----------------|-----------------:|:---------------:|
| baidu           |            yahoo |     google      |
| baiduuuuuuuuuuu | yahooooooooooooo | gooooooooooogle |

## 代码块 [syntax](https://github.com/GitbookIO/markdown/blob/master/syntax/code.md)
> 行内插入，一个单词或者一句代使用，使用 \`code\`

    `if ok { return }`
`if ok { return }`

> 多行代码，1. 代码的每行前有至少4个空格或一个tag 2. 使用三个反引号包裹

    ```golang
      func Sum(a, b int) int {
        return a + b
      }
    ```

```golang
func Sum(a, b int) int {
    return a + b
}
```

## 图片 [syntax](https://keatonlao.gitee.io/a-study-note-for-markdown/syntax/%E8%AF%A6%E7%BB%86%E7%89%88/markdown-%E6%8F%92%E5%85%A5%E5%9B%BE%E7%89%87/)
> 行内图片

    ![alt text](/path/to/img.jpg "Title")

![octocat](./resource/image_small.png "octocat small")


> 可通过div+css 控制图片的大小、对齐方式等
>
      <div align=center>
        <img src="./resource/image_big.jpg" height="200" width="400">
      </div>

<div align=center>
  <img src="resource/image_big.jpg" height="200" width="400">
</div>


## links
- [Markdown 语法](https://keatonlao.gitee.io/a-study-note-for-markdown/syntax/)
- [younghz/Markdown](https://github.com/younghz/Markdown)
- [GitbookIO/markdown](https://github.com/GitbookIO/markdown)
- [Syntax supported by github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
