Markdown
=======

![Markdown](markdown.png)

介绍
------

Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。


语法
------

| 类型 | 代码                                            | 代码片段 |
| :--- | :--------------------------------               | :------  |
| 强调 | `*斜体*` `**粗体**`                             | i    b   |
| 链接 | `[描述](http://example.com)`                    | l        |
| 图片 | `![描述](example.jpg)`                          | img      |
| 标题 | `# 标题1` `## 标题2` `###### 标题6` *[1]*       | #        |
| 列表 | `1. 有序列表` `- 无序列表` `- [x] 复选框` *[2]* | t        |
| 引用 | `> 这是引用文字，引用内可以嵌套标题、列表等`    | >        |
| 代码 | ```ruby    print 'Hwllo world'``` *[3]*         | code     |
| 表格 | *[4]*                                           | table    |
|`<hr>`|  `------------`                                 | ---      |

-------------------
**参考**

*[1]*
```
标题1        标题2
======       ------

### 标题3    ####### 标题7
```

*[2]*
```
1. 有序列表   - 无序列表   - [ ] 复选框
2. 有序列表   - 无序列表   - [x] 复选框
```
```html
/*                        <ul>
                            <li>Sizes</li>
- Sizes                     <li>Shapes</li>
- Shapes                    <li>Colors
- Colors                    <ul>
  - Blue                      <li>Blue</li>
  - Green                     <li>Green</li>
                            </ul></li>
                          </ul>
```
```html
/*                        <ol>
                            <li>First</li>
1. First                    <li>Second</li>
2. Second                   <li>Third
3. Third                    <ol>
  1. Alpha                    <li>Alpha</li>
  2. Bravo                    <li>Bravo</li>
                            </ol></li>
                          </ol>
```

*[3]*
>行内代码 ` 

>代码区块 ```

*[4]*
```
| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |
```
