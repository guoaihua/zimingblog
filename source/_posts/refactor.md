---
title: 重构-坏代码的味道
date: 2022-03-31 11:33:02
---


# 重复代码
>重复出现的代码片段，甚至是表达式都应该被抽离成公共函数

# 过长的函数
>每当需要使用注释来说明的时候，都要考虑把需要说明的东西放进函数，以其用途命名（而不是实现手法命名）

# 过长参数
>过长的参数会带来巨大的维护成本，使用对象替换过长的参数