---
layout: post
title: "Python 中的换位符和 \\n"
date: 2025-09-24
---
在这篇文章中，我们将讨论 Python 中的换位符和 `\\n`（换行符）的使用方法。

### Python 的换位符

Python 中可以使用字符串的格式化方法来插入变量。常见的换位符有：

- `%s` 用于字符串
- `%d` 用于整数
- `%f` 用于浮点数

#### 示例 1：使用 `%s` 插入字符串

```python
name = "Alice"
print("Hello, %s!" % name)
