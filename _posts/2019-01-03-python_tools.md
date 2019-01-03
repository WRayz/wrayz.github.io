---
layout: post
title: 'Python3 使用工具'
date: 2019-01-03 16:40:6 +0800
categories: Python
---

# Python3

課程講師：Mosh

## 工具

Editor: VSCode

IDE: 安裝相關套件

- Python
- Linter (for Python3): 檢查語法錯誤
- Code Runner: 快捷鍵 Ctrl + Alt + n 自動下指令輸出編譯結果

 運作原理

```txt
Python => CPython => Python Byte Code => Python Virtual Machine => Machine Code
```

使用其他 Implementation，可以使用不同語言的  library，使用 Jython 舉例運作原理

```txt
Python => Jython => Java Byte Code => Java Virtual Machine => Machine Code
```

## 特性

- 變數不用宣告型別，Python 會透過 expression 右邊的值自行推演型別
- string 大小寫有所區分
- bool expression 是 True/False，不是全小寫
- bool 也有 Truthy 和 Falsy
  - Falsy: "", 0, None
  - Truthy: 除 Falsy 外都是 Truthy
    > 注意連 bool(-1) 都是 True...

## 專有名詞

Syntax Error：語法錯誤

> Syntax 意思同 Grammer
