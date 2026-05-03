---
aliases:
  - 描述语法和语义
tags:
  - 语法
  - 语义
date: 2025-10-13
time: 23:46
---
![[Pasted image 20251014005750.png]]
**语法** 关注的是程序结构和形式是否正确
**语义** 关注的是程序执行时的行为和结果,即程序的意义
## Terminology
*A sentence* is a string of characters over some alphabet一个句子是某个字母表上的一串字符
*A language* is a set of sentences一种语言是一组句子的集合
*A lexeme* is the lowest level syntactic unit of a language词素是语言的最低级句法单位
*A token* is a category of lexemes 词法单元是词素的一类
### token 词法单元
	A token is a pair consisting of a token name and an optional attribute value. The token name is an abstract symbol representing a kind of lexical unit.
- 词法单元是程序中的基本语法单元，由一个词法单元名和一个可选的属性值组成。
- 词法单元名是一个抽象符号，代表某种类型的词法单元。
e.g, 
- 关键词（如 `if`、`else`）
- 运算符（如 `+`、`-`、`<`、`>`）
- 标识符（如变量名 `x`、`y`）
- 常量（如数字 `42`、字符串 `"hello"`）
### 模式（Pattern）
	A pattern is a description of the form that the lexemes of a token may take
一个模式是对一个标记的词素可能采取的形式的描述 
- 模式是描述词法单元可以采取的形式的规则。
- 模式通常使用正则表达式来定义。
### 词素（Lexeme）
	A lexeme is a sequence of characters in the source program that matches the pattern for a token and is identified by the lexical analyzer as an instance of that token.
一个词素是源程序中匹配令牌模式的一系列字符，并且由词法分析器识别为该令牌的一个实例
- 词素是源程序中匹配某个词法单元模式的字符序列。
- 词素由词法分析器识别为词法单元的一个实例。
## Regular Expression(正则表达式)
Regular expressions represent patterns of strings ofcharacters.正则表达式代表字符字符串的模式
