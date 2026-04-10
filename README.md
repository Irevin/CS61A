# CS61A Fall 2024 学习仓库

本仓库记录了我在 UC Berkeley CS61A Fall 2024 课程中的所做的Homeworks, Labs, Projects。并也对官方课程网站的内容进行了归档，官方网址为：https://insideempire.github.io/CS61A-Website-Archive/index.html

我个人为完成这些内容大约投入了 120 小时左右。

## 课程版本与来源

- 课程版本：CS61A Fall 2024
- 官方归档网址：`https://insideempire.github.io/CS61A-Website-Archive/index.html`
- 此课程基于 SICP（《Structure and Interpretation of Computer Programs》）改编而来，采用优化教材《Composing Programs》。教材地址为：`https://www.composingprograms.com/`

## 这门课讲了什么

CS61A 的核心理念是：**通过建立分层的抽象，来控制程序的复杂度**。课程分为四个阶段：

1. **过程抽象**（第 1-4 周）：学习用函数、高阶函数和递归来编写优雅的逻辑
   - 关键技能：理解递归思想，用通用的计算模式消解重复代码
   - 项目：Hog（掷骰子游戏）

2. **数据抽象**（第 5-6 周）：设计数据结构时，隐藏实现细节，只暴露接口
   - 关键技能：建立"抽象屏障"，使底层实现的改变不影响上层逻辑
   - 项目：Cats（打字竞赛）

3. **对象与状态**（第 7-10 周）：用对象封装状态，管理程序中的时间和变化
   - 关键技能：理解环境模型，学会用类和对象管理复杂的可变状态
   - 项目：Ants（塔防游戏）

4. **元语言抽象**（第 11-15 周）：设计和实现自己的编程语言
   - 关键技能：理解解释器原理，代码和数据的统一性，宏和求值过程
   - 项目：Scheme 解释器（一个完整的编程语言解释器）

**更多深度理解**，见这篇文章：[CS61A 到底在讲什么](https://www.learncs.site/docs/curriculum-resource/cs61a/intro)

## 仓库结构说明

本仓库按课程内容划分为五个主要目录：

### `Discs/`

该目录存放课程discussion文档。

### `Hws/`

该目录存放课程Homework的代码实现。每个作业目录一般包括：

- `hwXX.py`：作业代码实现
- `tests/`：作业测试文件
- `hwXX.ok`：OK 测试或配置脚本
- `ok`：OK 系统可执行文件或链接
- `construct_check.py`：代码结构检查脚本（用于检测禁止使用的语法或结构）

### `Labs/`

该目录存放课程Lab的代码实现。每个实验目录结构通常包括：

- `labXX.py`：实验代码
- `tests/`：实验测试文件
- `labXX.ok`：OK 测试或配置脚本
- `ok`：OK 系统支持文件
- `construct_check.py`：结构检查脚本

### `Projects/`

该目录存放课程Project的代码实现。当前仓库包含的项目有：

- `hog/`：掷骰子比赛模拟项目
- `cats/`：打字测试与竞赛项目，用户进行打字速度挑战，实现自动纠正、打字速度 (WPM) 计算、准确度检测，包含 Web GUI 和多人游戏模式
- `ants/`：Ants vs. SomeBees 塔防游戏项目，需要实现防守蜜蜂入侵的塔防系统，涉及面向对象编程与游戏逻辑设计
- `scheme/`：Scheme 编程语言解释器项目

每个项目目录通常包含：

- 主程序文件和模块源代码
- GUI 相关文件或前端资源
- 项目测试代码
- OK 测试或配置脚本，如 `proj01.ok`, `proj04.ok`

### `Slides/`

该目录存放课程Silde，即课程幻灯片。

### `Zips/`

该目录存放各项目和作业的压缩存档文件。包含：

- `Hws/`：所有 Homework 的压缩包
- `Labs/`：所有 Lab 的压缩包
- `Projects/`：所有 Project 的压缩包