# Tex-notes-master

A master tex file for writing notes.

一个简单的使用tex语言做笔记的母版，中英文皆可。

## Tips

```Notes_master.tex``` only works for English notes.

```中文笔记母版.tex``` works both for English and Chinese notes.

```Notes_master.tex``` 只能做英文笔记.

```中文笔记母版.tex``` 可以做中文笔记，也可以做英文笔记，也可中英文混用。

```Notes_master.tex``` 与 ```中文笔记母版.tex``` 的主要区别：

英文母版文件类型为
```
\documentclass[11pt, a4paper]{article}
```
中文母版文件类型为
```
\documentclass[UTF8, a4paper]{ctexart}
```

Please build with ```TraditionalLaTex``` or ```pdfLaTex```.

请使用 ```TraditionalLaTex``` 或 ```pdfLaTex``` 编译文件
