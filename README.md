#  Python 旋风之旅

Jake VanderPlas 著，同济大学苹果开发俱乐部 译校

点击[这里](https://github.com/SXKDZ/A-Whirlwind-Tour-of-Python/archive/master.zip)下载并访问`Book/Index.html`文件查看中文翻译版

*A Whirlwind Tour of Python* is a fast-paced introduction to essential
components of the Python language for researchers and developers who are
already familiar with programming in another language.

## 目录

1. Python 介绍
2. 如何运行 Python 代码
3. Python 语法速览
4. 基础 Python 语义：变量和对象
5. 基础 Python 语法：运算符
6. 内置类型：简单变量类型
7. 内置数据结构
8. 控制流
9. 定义和使用函数
10. 错误和异常
11. 迭代器
12. 列表推导
13. 生成器
14. 模块和包
15. 字符串处理和正则表达式
16. 数据科学工具概览
17. 更多学习资源
18. 附录：插图代码


## 译者序

Python 官方教程的开头是这样写的：“Python 是一门既容易上手又强大的编程语言。”随着大数据、机器学习与人工智能的兴起，Python 语言正在受到越来越广泛的关注和应用。对爱好 Python 的人来说，人生苦短，Python 当歌！简洁轻松的语法，开箱即用的模块，强大快乐的社区，总可以快速构建出简单高效的解决方案。对于希望快速入门 Python 语言的读者们来说，市面上众多像字典一般厚厚的 Python 书籍常常让人感到头皮发麻。为了让对 Python 语言感兴趣的读者能快速入门这门语言，而非过分纠结于 Python 细枝末节之处，我们选择并翻译了这本 Python 教程：*A Whirlwind Tour of Python*。

本书作者 Jake VanderPlas 目前是华盛顿大学 eScience 学院物理科学研究院院长。他既是一位天文学家，也是一位会议演讲达人，活跃于历年的 PyData 会议，尤其擅长 Python 科学计算与数据可视化。Jake 在数据可视化方面颇有建树，创建了 altair、mpld3、JSAnimation 可视化程序库，同时为 NumPy、Scikit-Learn、Scipy、Matplotlib、IPython 等著名 Python 程序库做了大量贡献。

这本仅 100 余页的小册子是一本精简的 Python 编程入门教程，介绍了 Python 语言的核心特性以及数据科学领域内一些 Python 第三方扩展包的实际应用，目的是让熟悉其他编程语言的数据科学家快速学习 Python。本书适合从未接触过 Python 语言但对其他编程语言有一定了解的读者，建议读者跟随本书亲自动手完成每一个例子。

本书翻译力求在原版基础上做到精炼、全面、准确地介绍 Python 语言。在书中难于理解的部分我们添加了译者注，希望能便于读者理解。

本书由同济大学苹果开发俱乐部翻译、审校，其中朱彦樵负责全书统稿工作；朱彦樵负责翻译第 5、11–13、15–17 章和附录，蒋宇凯负责翻译第 6–9 章，李晗负责翻译第 1–4、10、14 章；朱彦樵、李晗、李阳、梁琛、阿思亘负责审稿、校对与润色；朱彦樵、李源完成了全书的编辑排版工作。

本书的出版工作得到了同济大学软件学院出版基金的大力支持，在此一并感谢。

Python 语言以及其他第三方包发展迅速，限于译者的水平与功底，本书错谬之处在所难免。希望读者能够不吝赐教，帮助本书更加完善。

## 版权与引用信息

### 中文版版权

中文翻译版版权归同济大学苹果开发俱乐部所有。

### 原书版权

This material is released under the "No Rights Reserved" [CC0](LICENSE)
license, and thus you are free to re-use, modify, build-on, and enhance
this material for any purpose.
Read more about CC0 [here](https://creativecommons.org/share-your-work/public-domain/cc0/).

If you do use this material, I would appreciate attribution.
An attribution usually includes the title, author, publisher, and ISBN.
For example:

> *A Whirlwind Tour of Python* by Jake VanderPlas (O’Reilly). Copyright 2016 O’Reilly Media, Inc., 978-1-491-96465-1.
