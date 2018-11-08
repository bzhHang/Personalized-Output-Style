# 基于 Markdown 的富文本自动排版

## 意义

在各种平台发布文章时，如果在平台自带的编辑器或第三方编辑器中写作，难免需要在写作的过程中为排版问题分散精力。Markdown 是一种轻量级的标记语言，能够用简单的符号完成一篇文章的基本排版，并支持转化为 HTML 格式。因此，利用一份 Markdown 文档中所包含的排版信息，加上一份 CSS 样式文档描述各种标记所对应的具体样式，就能够完成自动排版，大大节省了写作者的精力。

此外，自动排版有助于维持作者在不同文章中排版风格的一致性。这有利于作者在平台上提高个人标识度，打造个人品牌。目前已知使用这种技术排版的作者有：

- “可能吧”微信公众号，阿禅（Jason Ng）
- （待补充）

## 适用范围

本技术适用于各类以展示内容文字为主要写作目的的微信公众号、知乎、各类博客等文章的排版，也适用于一些内容结构固定、按照一定周期循环发表的文章的排版。

本技术不适用于一些以宣传为主要功能的文章，因为它们需要更加精致、更加个性化的排版来起到宣传效果。

（待补充）

## 使用方法

1. 打开[排版网址](http://md.aclickall.com)。
2. 复制一篇 Markdown 文档（比如[这篇](https://raw.githubusercontent.com/tansongchen/Personalized-Output-Style/master/Articles/花园宝宝2017_学期复盘：从经验中快速学习.md)）的内容到左侧 Markdown 编辑区。
3. 点击右上方按钮“一键排版”。
4. 复制一篇 CSS 文档（比如[这篇](https://raw.githubusercontent.com/tansongchen/Personalized-Output-Style/master/CSS/%E8%8A%B1%E5%9B%AD%E5%AE%9D%E5%AE%9D2017_%E4%B8%93%E9%A2%98%E6%96%87%E7%AB%A0.css)）的内容到左侧 CSS 编辑区。
5. 点击左下方按钮“保存”。
6. 在右方显示排版效果，核对无误后点击右上方按钮“复制”。
7. 在微信公众号图文等界面粘贴。

## 致谢

该技术来自于微信用户“颜家大少”，[排版网址](http://md.aclickall.com)由他制作。
