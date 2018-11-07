ICS (Fall 2018) Project
======

**本Project分为三个阶段，主要目标是编写一个Y86-64流水线CPU模拟器。**

Project的基本说明
----------------
+ 对所用的语言，结构，技术栈等没有任何限制。
+ 对程序的表现方式没有限制，可以有图形界面也可以是终端输出。
+ 可以单人完成也可以两人组队。两人组队时分数结算会有一定的变化。两人组队请在组建后维持至PJ结束。
+ 请不要抄袭。

阶段一：模拟器的正确性与基础功能（30%）
----------------
**实验内容**
+ 正确实现正确模拟测试样例所需的最小指令集。
+ 提供基本的观察CPU运行状态与代码运行结果的功能。

**评分标准**
+ 根据测试样例结果的运行结果的正确性评分，前提是模拟器有恰当的方式使得用户可以观察到CPU的运行方式及其行为。
测试样例可以在[此处](http://csapp.cs.cmu.edu/3e/sim.tar)下载，其中包括一个Y86-64汇编器，一个Y86-64CPU模拟器和一组测试用例。模拟器提供GUI版本与终端版本，GUI版本需要安装tk、tcl包（具体包名请查询你所使用的系统使用的包管理器），如果需要终端版本，请修改Makefile文件。执行make命令后即可在y86-64code文件夹中找到所用测试样例的汇编代码(\*.ys)和机器代码(\*.yo)。其他请参阅包中的README文件。
+ 组队分数结算调整：无

**提交**
+ 需要提交源代码，可执行的程序文件（如有必要请提供必需的运行环境等信息）。
+ 如果不能以类似\*.yo格式文件进行输入的，请提供一个转换器或提供转换后的可用于输入的文件。
+ 提交截止时间：2018.11.21 23:59:59。
+ 迟交惩罚：每迟交一天本部分分数-20%，五天后分数为0.

阶段二：模拟器的附加功能与完整性（40%）
----------------------
**实验内容**
+ 通过以下方面完善你的模拟器：
功能性（提供用于调试、观察的额外功能；优化流水线；实现附加指令等）
创新性
人机交互友好度（模拟器的易用、整洁、合理）
鲁棒性等

**评分标准**
+ 从功能性、创新性、人机交互友好度、鲁棒性及其他方面对于模拟器进行评分，各方面优先级即按照前面所示的顺序（在优先级高的方面有优秀的实现能得到更高的分数。
+ 评分的依据为源代码、模拟器的实际使用和pre。
+ 组队分数结算调整：此部分的给分上限将会提升25%，最后再80%折算，折算后满分与单人时一致。

**提交**
+ 需要提交源代码，可执行的程序文件、实验报告。
+ 如果不能以类似\*.yo格式文件进行输入的，请提供一个转换器或提供转换后的可用于输入的文件。
+ 提交截止时间：2018.12.5 23:59:59。
+ 迟交惩罚：2018.12.12 23:59:59 前提交分数-20%，之后每迟交一天本部分分数-16%，五天后分数为0.

阶段二Pre
---------------------
+ 时间安排：2018.12.6 起的连续四周上机课。每组10分钟（包含提问时间）。2018.11.29起可以向助教预约，2018.12.5前预约可以有少量的分数加成。
+ Pre内容：模拟器实现的功能、功能的实现、创新点、心路历程等。主要是要充分展示自己做的模拟器。
+ PPT提交：请于Pre之后一周内提交Pre使用的PPT。

阶段三：多线程Y86-64模拟器与存储结构模拟（30%）
------------------
**实验内容**
+ 实现多线程的Y86-64模拟器。
+ 模拟存储器层次结构、虚拟内存等。

**评分标准**
+ 多线程Y86-64模拟器行为的正确性。
+ 存储器层次结构、虚拟内存模拟的正确性与合理性。
+ 组队分数结算调整：此部分的给分上限将会提升33.3%，最后再75%折算，折算后满分与单人时一致。

**提交**
+ 需要提交源代码，可执行的程序文件、新增内容的实验报告、能够展示对于存储部分模拟的代码、一个能够展示所实现的此阶段功能的模拟器屏幕录像。
+ 如果不能以类似\*.yo格式文件进行输入的，请提供一个转换器或提供转换后的可用于输入的文件。
+ 提交截止时间：2018.12.26 23:59:59。
+ 迟交惩罚：2019.1.2 23:59:59 前提交分数-20%，之后每迟交一天本部分分数-16%，五天后分数为0.

挑战Project
--------------------
如果你认为以上的Project缺爱挑战性，可以选择ARM或MIPS指令集或包含浮点数功能的指令集等实现类似的模拟器，如果想要选择挑战Project，请与助教联系讨论具体实现的内容和日程安排。

参考资料
-------------------
+ [Intel® 64 and IA-32 Architectures Software Developer’s Manuals](https://software.intel.com/en-us/download/intel-64-and-ia-32-architectures-sdm-combined-volumes-1-2a-2b-2c-2d-3a-3b-3c-3d-and-4)
+ [CSAPP官方文档](http://csapp.cs.cmu.edu/3e/students.html)