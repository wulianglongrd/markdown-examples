# 基本语法

## 基础

|效果                              |markdown 语法                |
|:------------------------:|------------------------------------|
|标题 (Heading)             | \# H1 \#\# H2 \#\#\# H3 |
|粗体 (Bold)                | \*\*bold text\*\* |
|斜体 (Italic)              | \*italicized text\* |
|删除线 (Line Through)      | \~\~line through\~\~ |
|引用块 (Blockquote)        | \> blockquote |
|有序列表 (Ordered List)    | 1. First item 2. Second item 3. Third item |
|无序列表 (Unordered List)  | - First item - Second item - Third item |
|代码 (Code)               | \`code\` |
|分隔线 (Horizontal Rule)  | --- |
|链接 (Link)               | \[title\](http://www.example.com) |
|图片 (Image)              | !\[alt text\](./path/to/image.jpg) |

## 表格
> 使用`:`来控制对齐

| 左对齐 | 右对齐|居中对齐|
|:----|----:|:-----:|
| baidu | yahoo| google |
| baiduuuuuuuuuuu | yahooooooooooooo | gooooooooooogle |

## 代码块
> 行内插入，一个单词或者一句代使用，使用 \`code\`
> 
> 多行代码，使用三个反引号包裹多行

`if ok { return }`

```golang
func Sum(a, b int) int {
    return a + b
}
```

## links
- [Markdown 语法](https://keatonlao.gitee.io/a-study-note-for-markdown/syntax/)
- [younghz/Markdown](https://github.com/younghz/Markdown)
