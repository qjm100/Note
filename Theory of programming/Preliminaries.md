---
aliases:
  - 导论
tags:
  - 介绍
  - 入门
date: 2025-10-12
time: 15:09
---
# 为什么要学习编程语言导论
+ 提高内容表达能力 Increased capacity to express
+ 改进选择适当语言的原因 Improved background for choosing appropriate languages
+ 提高学习别的编程语言的能力 Increased ability to learn new languages
+ 更好的了解语言实施的重要性 Better understanding of the significance of implementation
+ 更好的使用已经使用的语言 Better use of languages that are already
+ 更进一步的编程 Overall advancement of computing
# 语言评估标准 Language Evaluation Criteria

## 1.可读性 Readable

	“Programming is the art of telling another humanbeing what one wants the   computer to do.” By Donald Knuth

### Overall Simplicity
+ A manageable set of features and constructs 一个特性和结构可管理的集合
+ Minimal feature multiplicity 最小特性多样性
    特性多样性: 不止一种方法完成一种操作 more than one way to accomplish a particular operation
+ Minimal operator overloading 最小操作符重载
	操作符重载: 一种操作符号有不止一种意思 a single operator symbol has more than one meaning.
### Orthogonality 正交性
+ A relatively small set of primitive constructs can be combined in a relatively small number of ways 相对较少的一组原始结构可以在相对较少的方式中组合
+ Every possible combination is legal and meaningful 每种可能的结合都是合法且有意义的
+ The more orthogonal the design of a language, the fewer exceptions the language rules require. 越多的正交越少的例外
+ Fewer exceptions mean a higher degree of regularity in the design, which makes the language easier to learn, read, and understand.越少的例外意味着设计有更高的规律性
+ Too much orthogonality can lead to unnecessary complexity. Furthermore, because languages require a large number of primitives, a high degree of orthogonality results in an explosion of combinations.过高的正交性会导致不必要的复杂度.此外, 因为语言需要打量原始操作,高程度的正交性会使得语言组合爆炸.

### Readability(可读性)
+ Data Types 数据类型
+ Syntax Design 语法设计
+ Writability 可写性(影响可读性也可能影响可写性)
+ Simplicity and Orthogonality 
+ Support for abstraction
+ Expressivity
### Reliability (可靠性)
+ Type Checking
+ Exception Handling(异常处理)
+ Aliasing (别名)
+ Readability and Writability
### cost(花费)
最重要的是program development, maintenance, and reliability.
## 语言分类Language Categories

+ **Declarative languages 声明式语言**
+ **Imperative languages 指令型语言**
+ Functional Language
+ Dataflow Language
+ Logic- or Constraint-based Languages基于逻辑约束语言
+ Von Neumann Language 冯·诺伊曼语言
+ Scripting Language 脚本语言
+ Object-oriented Language 面向对象的语言
## Compilation编译
+ lexical analysis 词法分析
+ syntax analysis 语法分析
+ semantics analysis 语义分析
+ code generation 机器代码生成