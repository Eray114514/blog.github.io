> [!NOTE]
> Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档，然后转换成结构化的HTML代码。Markdown 语法简单，但功能强大，广泛应用于博客、笔记、文档编写等方面。
以下是 Markdown 的一些常用语法：
## 标题
在文字前面加上 `#` 表示标题，`#` 的数量表示标题的级别：
```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
## 强调
- *斜体* ：将文字两边各加上一个 `*` 或 `_`。
- **粗体**：将文字两边各加上两个 `*` 或 `_`。
- ***粗斜体***：将文字两边各加上三个 `*` 或 `_`。
## 列表
- 无序列表：使用 `*`、`+` 或 `-` 加上一个空格。
  ```markdown
  - 项目一
  - 项目二
  - 项目三
  ```
- 有序列表：使用数字加点加空格。
  ```markdown
  1. 第一项
  2. 第二项
  3. 第三项
  ```
## 链接与图片
- 链接：`[显示文本](链接地址 "标题")`
  ```markdown
  [百度](https://www.baidu.com)
  ```
- 图片：`![替代文字](图片链接 "标题")`
  ```markdown
  ![这是一张图片](https://example.com/image.jpg)
  ```
>  "标题"指鼠标悬停在链接上时显示的文本，该项非必要项
## 引用
在引用的文字前加上 `>` 符号：
```markdown
> 这是一个引用。
```
## 代码
- 行内代码：用一对反引号"\`"包围代码:\`code\`→`code`
- 代码块：用一对三个反引号上下包围代码块。

> \```（可以在后面加上代码语言如：python）
print("Hello World")
\```

```python
print("Hello World")
```
## 表格
使用 `|` 和 `-` 创建表格：
```markdown
| 标题1 | 标题2 | 标题3 |
|-------|-------|-------|
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |
```
| 标题1 | 标题2 | 标题3 |
|-------|-------|-------|
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |
## 分隔线
使用三个以上的 `*`、`-` 或 `_` 来创建分隔线：
```markdown
---
```
## HTML 代码
Markdown 支持直接插入 HTML 代码，但某些平台可能会限制这一功能。
```html
<p>这是一个HTML段落。</p>
```
## 转义字符
您可以在 Markdown 字符前使用 \ 命令 Markdown 解析器忽略（转义）Markdown 格式：\*这不是一个斜体\*
```markdown
\*这不是一个斜体\*
```
---
> [!TIP]
> 根据不同的解析器或平台（如 Github），还可能支持额外的功能或语法。
详见[Github Markdown语法官方文档](https://docs.github.com/zh/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)