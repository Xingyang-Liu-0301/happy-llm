# Happy-LLM Chapter 2：Transformer 架构学习笔记

## 1. 本章目标

- 理解 Attention 的基本思想
- 理解 Self-Attention 中 Q、K、V 的含义
- 理解 Multi-Head Attention
- 理解 Encoder-Decoder 架构
- 理解 Transformer 为什么适合并行计算

## 2. 今日学习记录

日期：2026-05-26

### 已理解内容

- Attention 是让模型关注输入中更重要的信息。
- Q 表示当前要查询什么，K 表示每个位置可以被匹配的特征，V 表示真正被加权汇总的信息。

### 仍然不理解的内容

- 为什么 Q 和 K 点积可以表示相关性？
- Masked Attention 为什么能防止模型看到未来信息？

## 3. 待提问

- Self-Attention 和普通 Attention 的区别是什么？
- Multi-Head Attention 为什么需要多个头？