---
layout: page
title: openFuyao AI 推理基础设施
description: 攻克 PD 分离架构、分布式 KVCache 传输、AscendCacheTier 等关键技术，实现 DeepSeek 等主流大模型在昇腾 910B 上的云原生高效部署。
img:
importance: 1
category: AI Infra
---

## 项目概述

openFuyao 是面向昇腾 NPU 的 AI 推理基础设施平台，致力于推动主流大模型在昇腾硬件上的高效部署。

## 关键技术

- **PD 分离架构**：Prefill 和 Decode 阶段解耦，实现资源利用率最优化
- **分布式 KVCache 传输**：跨节点高效 KVCache 共享，减少冗余计算
- **AscendCacheTier**：层次化缓存管理，提升推理吞吐

## 核心成果

- 与 Mooncake 社区合作，实现 store 接口 **60%-80%** 性能提升
- 支撑 DeepSeek 等主流大模型在昇腾 910B 上的高效部署
