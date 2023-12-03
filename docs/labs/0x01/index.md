# 实验一：操作系统的启动

!!! tip "就像宇宙的大爆炸，操作系统的启动是一切的起点。<br/>在这个微妙的瞬间，一切从无到有，从混沌到秩序。"

    <p align="right" style="font-weight: bold">by Copilot</p>

## 实验目的

1. 了解页表的作用、ELF 文件格式、操作系统在 x86 架构的基本启动过程。
2. 尝试使用 UEFI 加载并跳转到内核执行内核代码。
3. 实现基于 uart16550 的串口驱动，使用宏启用输出能力、并启用日志系统。
4. 学习并尝试使用调试器对内核进行调试。

## 实验基础知识

!!! note "善用 LLM 进行学习"

    对于现代计算机专业的学生，我们建议并要求大家学习借助 LLM（Large Language Model）进行学习，这是一种非常有效的学习方法，可以帮助你更快的学习到知识。

    对于不理解的知识点和概念，我们建议优先参考文档、借助 LLM 进行实践，在仍然无法解决的情况下再向他人提问。

对于本次实验内容，你需要参考学习如下实验资料：


## 实验任务与要求

1. 请各位同学独立完成作业，任何抄袭行为都将使本次作业判为 0 分。
2. 请参考 [代码规范](../../general/coding_convention.md) 进行实验代码编写。
3. 依据 [实验任务](./tasks.md) 完成实验。