# MyST Markdown

MyST（Markedly Structured Text）是建立在CommonMark基础上的​​增强版Markdown​​，专为科学写作和技术文档设计，支持复杂内容如公式、交叉引用等。


​​支持扩展语法​​：
- 数学公式：$E=mc^2$ 或块公式 $$...$$。
- 交叉引用：{ref} 引用章节、图表。
- 自定义指令：类似RST（reStructuredText），可嵌入交互式内容。
​

​用途​​：
- 用于Jupyter Book、Sphinx等工具，编写技术手册、学术论文。
- 适合需要公式、代码与文字混合排版的场景。
​

​示例​​：

````markdown
```{math}
E = mc^2
```
参见章节 {ref}`intro`。  
````