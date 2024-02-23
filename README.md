# projX-la-qemu-instrument

## 项目名称

基于Qemu的龙架构平台高性能插桩工具

## 支持单位

龙芯中科技术股份有限公司、中国科学院计算技术研究所

## 项目描述

[Pin](https://www.intel.com/content/www/us/en/developer/articles/tool/pin-a-dynamic-binary-instrumentation-tool.html)是Intel提供的一个动态二进制插桩工具，它可以用于性能分析、安全增强和程序分析等领域。本项目的目标是为龙架构平台提供一个类似的工具。由于Pin并不开放源代码，已有人在开源QEMU二进制翻译器基础上做了一些工作，可以作为项目参考。

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

* 张福新 
    - github github.com/foxsen
    - Email  fxzhang @ ict.ac.cn

## 难度

中-高

# License

GPL V3.0.

## 预期目标

* 实现大部分Pin通用API
* 参加Pin提供的应用示范代码，通过移植或者自研，提供常见场景的应用示范案例

## 参考资源

* [pin like QEMU instrument](https://github.com/foxsen/qemu-instrument/tree/instru)。龙芯组一位同学做的基础工作，已实现部分功能。
* [LoongArch docs](https://github.com/loongson/LoongArch-Documentation)。LoongArch相关文档，包括架构手册，ABI, 芯片手册等。
* [LoongArch汇编手册](https://github.com/loongson/la-asm-manual)

## 备注

