---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

你好！我是张万豪，目前的工作与技术兴趣聚焦于 **AI Infrastructure**，关注大模型训练与推理系统、机器学习编译器和高性能算子。我主要围绕 PyTorch 编译栈、vLLM / SGLang、MoE / Expert Parallelism、通信计算融合与 NPU 算子优化开展工作，希望打通从模型前端、编译器 lowering、运行时到硬件内核的完整链路，让大模型在加速器上运行得更高效、更易用。

我于 2025 年获得清华大学网络空间安全专业硕士学位，2022 年获得北京航空航天大学计算机科学与技术专业学士学位。此前在智能运维、生成式 AI、模型服务与异构硬件迁移等方向积累了从算法研究到系统落地的经验，这些经历也逐步将我的关注点引向 AI Infra。邮箱：[wzhangt@gmail.com](mailto:wzhangt@gmail.com)。

# Research Interests

- **LLM Systems：** 大模型训练与推理、vLLM / SGLang、MoE 与 Expert Parallelism
- **ML Compilers：** PyTorch、torch.compile、Dynamo / FX、Inductor 与后端 lowering
- **High-Performance Kernels：** 通信计算融合、算子优化、NPU 软件栈与端到端性能分析

# News

- **2025.07 - 至今** 工作与技术方向聚焦 AI Infra、大模型推理系统和加速器软件栈。
- **2025.04** 完成在国际农业发展基金会（IFAD）ICT AI Team 的研发实习。
- **2024.10** LogRAG 被 IEEE ISSRE 2024 Research Track 接收。
- **2024.09** 完成在腾讯视频 AI 技术中心的研发实习。
- **2024.05** LogRAG 在华为云及车云日志异常检测场景完成落地验证。
- **2023.08** Neural-Hidden-CRF 发表于 ACM KDD 2023，并获最佳论文候选。

# Publications

### Leveraging RAG-Enhanced Large Language Model for Semi-Supervised Log Anomaly Detection

**Wanhao Zhang**, Qianli Zhang, Enyu Yu, Yuxiang Ren, Yeqing Meng, Mingxi Qiu, Jilong Wang<br>
*IEEE International Symposium on Software Reliability Engineering (ISSRE), 2024.*<br>
[[Paper]](https://doi.org/10.1109/ISSRE62328.2024.00026) [[Code]](https://github.com/WanhaoZhang/LogRAG)

### Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labeler

Zhijun Chen, Hailong Sun, **Wanhao Zhang**, Chunyi Xu, Qianren Mao, Pengpeng Chen<br>
*ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2023. Best Paper Candidate.*<br>
[[Paper]](https://arxiv.org/abs/2309.05086) [[Code]](https://github.com/WanhaoZhang/Neural-Hidden-CRF)

### FTM-RCA: A Fast Two-Stage Multi-dimensional Root-Cause Analysis of Network Anomalies

Yeqing Meng, Qianli Zhang, Xiangyu Tang, **Wanhao Zhang**, Jilong Wang<br>
*IEEE/ACM International Symposium on Quality of Service (IWQoS), 2023.*<br>
[[Paper]](https://dblp.org/rec/conf/iwqos/MengZTZW23)

# Honors

- 清华大学校设综合优秀一等奖学金，2024
- 清华大学校设综合优秀二等奖学金，2023
- 北京航空航天大学优秀毕业生，2022
- “蓝桥杯”算法竞赛北京赛区二等奖，2021
- 中国大学生数学建模竞赛北京市二等奖，2020
- 中国大学生数学竞赛北京市一等奖，2019

# Experience

### 1. AI Infrastructure / 大模型系统（2025.07 - 至今）

- 围绕 PyTorch 编译栈和加速器后端，推进算子从前端接口、计算图捕获与编译器 lowering，到运行时及设备内核的端到端接入。
- 面向 MoE 大模型推理，关注 Expert Parallelism、通信计算融合与高性能算子，并在 vLLM / SGLang 等推理框架中开展集成、正确性验证和性能分析。

### 2. 国际农业发展基金会 IFAD，ICT AI Team（2025.01 - 2025.04）

- 建设面向大模型应用的数据处理链路，探索 PDF、PPT 等非结构化文件向高质量 Markdown 的自动转换，并参与内部 AI 工具平台与 LLM 内容安全模块开发。
- 调研中国大语言模型发展情况，并在 IFAD 内部进行英文分享。

### 3. 腾讯，腾讯视频 AI 技术中心（2024.05 - 2024.09）

- 围绕生成式 AI 内容生产链路，对 Qwen2-7B 进行 LoRA 指令微调，并实现从文本理解到分镜生成的模型工作流。
- 使用 Go 与 tRPC 搭建模型服务和智能剪辑微服务链路，完成推理服务向异构 GPU 的迁移适配与成本优化。

### 4. 华为，2012 实验室（2023.07 - 2024.05）

- 独立负责生产级日志异常检测系统的算法设计、实验验证与工程实现，提出 DeepSVDD 与 RAG 结合的 LogRAG 框架。
- 推动方案在云服务与车云场景落地，积累了大规模日志处理、检索增强、模型评测和线上系统优化经验。

### 5. 快手，主站技术部（2022.07 - 2022.10）

- 基于 WALA 构建 Java 字节码静态分析流程，通过调用图、变量流转图与污点传播完成全程序分析。
- 独立开发缺陷检测模块并集成至程序分析引擎，形成了对编译分析、中间表示与工程工具链的早期实践。

# Education

- **清华大学**，网络空间安全硕士，2022.09 - 2025.06，GPA 3.92/4.0
- **北京航空航天大学**，计算机科学与技术学士，2018.09 - 2022.06，GPA 3.70/4.0
