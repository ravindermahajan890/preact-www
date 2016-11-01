---
name: Project Goals
permalink: '/about/project-goals'
---

# Preact的项目目标
 
Preact 实现的几个关键目标:

- **性能:** 快速与高效的渲染
- **大小:** 小，轻 _(大约 3.5kb)_
- **效率:** 高效的内存使用 _(对象重复利用, 避免垃圾回收)_
- **可理解性:** 可以几小时理解框架代码
- **兼容性:** Preact兼容大部分的React API. preact-compat 实现了更多的react api兼容

# 非目标(Non-Goals)

有些React特性在Preact是有意的没有被实现，因为要满足上面列出的主要项目目标，或者因为它们不适合作为Preact的核心功能。

- 如下是没有被实现的功能 [缺少了哪些?](/guide/differences-to-react#whats-missing):
    - PropTypes, 方便作为一个分开库使用 
    - Children, 由于Preact总是将子节点作为数组
    - Synthetic Events, 由于Preact不需要去兼容老板本的浏览器，如IE8

[preact-compat]: https://github.com/developit/preact-compat/