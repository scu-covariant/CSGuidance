<div align="center">
  <h1>四川大学智锐科创计算机协会资料索引</h1>
  <p align="center">
    &#128195; <a href="https://unicov.cn/scu/">社团主页</a> • 
    &#128568; <a href="https://github.com/scu-covariant">github</a> • 
  </p>
</div>
<p align="center">
  <img src="https://github.com/zhangbihan999/CSGuidance/blob/main/imgs/%E5%8D%8F%E4%BC%9A%E6%A0%87%E5%BF%97.png"
    style="width: 50%; height: 50%">
</p>


本仓库由四川大学智锐科创计算机协会维护。旨在为想要学习计算机知识的同学们提供一些优质学习资料索引，避免陷入想做项目但不知道如何找资源、从哪里学起的困境。我们将内容分成了不同的板块，尽可能满足同学们的各种需求。

## &#128221; 基础知识

### 1. Python

Python是一个强大而灵活的编程语言，特别适合机器学习，这得益于它的可读性、一致性和强大的数据科学库生态系统。对于希望从事数据分析、大模型相关领域的同学，Python 将是你的必备工具。

- Python 基础：掌握 Python 的 基础语法、数据类型、错误处理，了解面向对象编程语言。

&#128218; 资源：

- [Learn Python in Y Minutes](https://learnxinyminutes.com/docs/python/): 对于不想看书、追求速成的同学，这个教程将是不二选择！直接用代码教学，一切尽在注释中！
- [Python Tutorial](https://www.w3schools.com/python/?ref=bootvar.com): 想系统学习 Python 看这里。详细介绍了 Python 基础知识以及如何用 Python 作图（matplotlib 库的使用）、如何用 Python 操作 MySQL、MongoDB 数据库等。

--------

### 2. Git

Git 是目前世界上最先进的分布式版本控制系统。作为程序员，日后不可避免地需要进行多人协作开发，Git 提供了一套高效、可靠的方式来管理代码变更历史和版本迭代。它允许开发者在本地进行代码提交、分支创建、代码合并等操作，而不依赖于中央服务器。

- Git 基础：学会使用 Git + Github 联合开发，学会使用 `git clone`, `git add`, `git commit`, `git push`, `git pull` 等基础命令，能够正确处理冲突。

&#128218; 资源：

- [Git教程 - 廖雪峰的官方网站](https://liaoxuefeng.com/books/git/introduction/index.html): 廖雪峰老师的 Git 教程，品质保证！
- [Git 和 GitHub 教程——版本控制入门](https://www.freecodecamp.org/chinese/news/git-and-github-for-beginners/): 选自世界最大的编程自学营地 freecodecamp，速成主义者看这里。

### 3.Docker

Docker 是基于 linux 内核的容器虚拟化技术，可以理解为轻量化、定制化的虚拟机。使用 docker 创建容器作为开发环境，能够确保环境的一致性，从而使得开发环境的迁移更加容易，也能够保证应用程序在任何操作系统上都能够正常运行。

&#128218; 资源：

- [Docker -- 从入门到实践](https://docker-practice.github.io/zh-cn/)

## &#128187; 机器学习 / 深度学习

- 机器学习 / 深度学习 基础知识：了解线性回归模型、梯度下降、逻辑回归模型、过拟合等基础知识
- Pytorch: PyTorch 是一种用于构建深度学习模型的功能完备框架，是一种通常用于图像识别和语言处理等应用程序的机器学习。使用 Python 编写，因此对于大多数机器学习开发者而言，学习和使用起来相对简单。

 &#128218; 资源：

- [机器学习——吴恩达](https://www.bilibili.com/video/BV1Bq421A74G?vd_source=0b09067c2866c4e9422cb38d8613e75c): 吴恩达老师的机器学习课程通俗易懂，涵盖了机器学习的所有基础知识，适合作为0基础同学的第一门机器学习课程。
	- 这里放的是B站搬运版本，正版在 Coursera 上，普通用户有一周的免费试用期，后续则需付费观看，同学们根据自己的条件选择。
- [动手学深度学习——李沐](https://www.bilibili.com/video/BV1if4y147hS/): 硅谷华人大佬李沐老师的经典课程！会带着你写代码，讲解地也很细致。
	- 虽说是入门课程，但有不少同学反馈0基础容易跟不上，这种情况建议先学习吴恩达老师的机器学习课程。
- [PyTorchZeroToAll](https://github.com/hunkim/PyTorchZeroToAll): HKUST 开发的 3~4 天速成 Pytorch 课程
	- B站配套视频：[PyTorch速成教程](https://www.bilibili.com/video/av15823922/)

## &#128483; 大语言模型（LLM）

LLM 是当下最火的研究课题，大家日常使用的 ChatGPT、文心一言、Kimi 等都属于大语言模型。下面我们将由浅入深（从简单的如何更好地使用大模型到了解大模型背后的工作原理）地给出一些学习资料。

### 1. 提示词工程（Prompt engineering）

提示词工程即向大模型提问的艺术，这是一项简单且实用的技术，能够帮助用户更高效地利用大模型。

&#128218; 资源：

- [ChatGPT 中文调教指南](https://github.com/PlexPt/awesome-chatgpt-prompts-zh): 该仓库收纳了一些高效的提问模板，可直接使用。
- [Prompt Engineering Guide](https://www.promptingguide.ai/zh): 想要系统学习 Prompt 知识的看这里，介绍了零样本提示、少样本提示、思维链（CoT）等概念

------------

### 2. Transformer 介绍

Transformer 是当今最为流行的神经网络模型，ChatGPT 等大模型应用都建立在它的基础之上。因此，理解 Transformer 的设计理念和工作原理是理解大语言模型不可或缺的一步。

&#128218; 资源：

- 李宏毅老师合集：

	为什么把李宏毅老师对 Transformer 的介绍单列一个合集出来，因为从我个人看过的所有 AI 教学内容来看，没有人在**把复杂的事情变简单**这件事情上做的比李宏毅老师更好，除了下面列举的 Transformer 相关内容，李宏毅老师在 Youtube 的其他内容也值得观看，绝对精品！

	- [李宏毅：80分钟快速全面了解大型语言模型](https://mp.weixin.qq.com/s/yJJg1Qn_SvK8POQP4GTqwg): **最浅**，但是视角比较宽泛，偏向向0基础人群科普
	- [【生成式AI導論 2024】第10講：今日的語言模型是如何做文字接龍的 — 淺談Transformer (已經熟悉 Transformer 的同學可略過本講)](https://www.youtube.com/watch?v=uhNsUCb2fJI)：**适中**，看完你能明白，从你输入一个问题到模型给出回答的整个过程中，大模型是如何一步步处理的（tokenize, embedding, 自注意力机制计算相似度, 多头注意力关注多维特征, FFN 整合多维信息等）
	- [【機器學習2021】Transformer (上)](https://www.youtube.com/watch?v=n9TlOhRjYoc&t=0s)：**最深**，深入了解 encoder 部分
	- [【機器學習2021】Transformer (下)](https://www.youtube.com/watch?v=N6aRv06iv2g)：**最深**，深入了解 decoder 部分

- [图解 Transformer](https://mp.weixin.qq.com/s?__biz=MzIzMDc2Njc0MQ==&mid=2247484181&idx=1&sn=2436fc57c49dcd904bc0f513b81e8604&chksm=e8af22efdfd8abf9cd7b831840a21d349141ba66f4839e2e6fae2ef2fdc7dd2be370046bbbb9&mpshare=1&scene=1&srcid=0321Lk3ENcUU4g3Djrt8GMW5&sharer_shareinfo=ee33e8994c5af07686d5f3b76fa4e40b&sharer_shareinfo_first=ee33e8994c5af07686d5f3b76fa4e40b&from=industrynews&version=4.1.20.6024&platform=win#rd): 介绍 Transformer 原理的优秀文章
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/): 国外火爆的 Transformer 原理解释文章
- [Transformer from scratch](https://www.youtube.com/watch?v=QCJQG4DuHT0&list=PLTl9hO2Oobd97qfWC40gOSU8C0iu0m2l4): 跟随油管大佬动手复现一个 Transformer，在实现的过程中理解 Transformer 的每个部分，适合那些想通过代码学习而不仅仅是阅读原理文章的同学（实现之后一定会成就感满满！）

## &#127984; 相关仓库推荐

网络上关于计算机的资料整合其实很多，我们推荐的内容只是冰山一角，下面将给出一些很优质的资料仓库，大家可以按需学习。

&#128218; 资源：

- [llm-course: Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks.](https://github.com/mlabonne/llm-course?tab=readme-ov-file): github 上关于 LLM 的最全最优质仓库，没有之一！对于有志在 LLM 方向深入学习的同学，这个仓库是必不可少的指路明灯。
- [CSGuide: 🔥 计算机学习路线，包括科班、非科班、Web、全栈、C++、Java、System等](https://github.com/imarvinle/CSGuide): 由四川大学2016级软件学院学长（知乎万粉大佬 [编程指北](https://www.zhihu.com/people/bian-cheng-zhi-bei)）倾心打造的计算机学习路线，适合任何基础任何专业的同学，强推！
- [CS自学指南](https://csdiy.wiki/): 火遍全网的 CS 自学指南，无数 CS 学生的启蒙知识库。收录了国内外各个方向的经典课程，干货满满！

