# Datalab: Manipulating Bits

[TOC]

## 0. Prerequisite

Make 之前需要先安装一些依赖库

```bash
sudo apt-get install libc6 libc6-dev libc6-dev-i386
```

如果运行某个文件时出现权限问题，请使用如下命令

```bash
chmod +x <file_name>
```

## 1. Introduction

The purpose of this assignment is to become more familiar with bit-level representations of integers and floating point numbers. You’ll do this by solving a series of programming “puzzles.” Many of these puzzles are quite artificial, but you’ll find yourself thinking much more about bits in working your way through them.

## 2. Handout Instruction

下载 `datalab-handout.tar` 之后，你可以通过以下命令来解压文件

```bash
tar xvf datalab-handout.tar
```

之后你会得到一个文件夹。在README中你能够看到关于整个目录的介绍

在文件夹中，你只需要在 `bits.c` 中进行代码的编写。你需要用 `!  ̃ & ˆ | + << >>` 这几个基本运算来实现一些比较复杂的函数，具体的要求请参考 `bits.c` 中的要求。

在完成了一部分之后，你希望能够对自己写的函数进行测试，请参考README。

## 3. Submit

### 3.1 实验报告

1. 学号.pdf
2. 解答的思考过程与结果（截图）
3. 实际操作的心得感想（可选）
4. 表意清晰
5. 精简（更重要）

### 3.2 提交方式

提交 `bits.c` 和实验报告，打包成 `学号.tar`；在ftp上提交，ftp地址稍后公布

打包方式，将 `bits.c` 和 实验报告 放在以学号命名的文件夹中，使用如下命令

```bash
tar cvf <学号.tar> <directory_name>
```

#### Deadline: 10月8日 23:59

#### 迟交惩罚: 每迟交一天得分减少20%，五天之后得分为0

#### Scoring lab中的评分程序71 + 报告 29；TA会在提交后重新进行测试

代码风格会计入成绩，不可以直接百度，如果发现照抄，lab 以 0 分记，如果有参考，请在 `bits.c` 最后加上 reference

## 4. Reference

[1] 各种祖传 slides