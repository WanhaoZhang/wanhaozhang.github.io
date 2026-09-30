---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
---

教育背景
======

- **清华大学**，网络空间安全专业硕士，2022.09 - 2025.06，GPA 3.92/4.0
- **北京航空航天大学**，计算机科学与技术专业学士，2018.09 - 2022.06，GPA 3.70/4.0

论文发表
======

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

工作、实习与研究经历
======

- **AI Infrastructure / 大模型系统**，2025.07 - 至今；PyTorch 编译栈、推理框架、MoE / EP、通信计算融合与 NPU 算子优化
- **国际农业发展基金会（IFAD）ICT AI Team**，Research & Development Intern，2025.01 - 2025.04
- **腾讯视频 AI 技术中心**，AI 研发实习生，2024.05 - 2024.09
- **华为 2012 实验室**，算法研发实习生，2023.07 - 2024.05
- **快手主站技术部**，研发实习生，2022.07 - 2022.10
- **北航软件开发环境国家重点实验室**，研究助理，2022.04 - 2023.03

技能
======

- 编程语言：Python、C / C++、Go、Java、SQL
- AI Infra：PyTorch、torch.compile、Dynamo / FX、Inductor、vLLM、SGLang、MoE / Expert Parallelism
- 系统与性能：通信计算融合、高性能算子、NPU 软件栈、模型服务、ONNX、性能分析
- AI 与数据：LLM、RAG、机器学习、自然语言处理、日志分析与智能运维
- 语言：英语六级 580 分，具备英文技术阅读、交流与汇报能力

荣誉奖项
======

- 清华大学校设综合优秀一等奖学金（2024）
- 清华大学校设综合优秀二等奖学金（2023）
- 北京航空航天大学优秀毕业生（2022）
- “蓝桥杯”算法竞赛北京赛区二等奖（2021）
- 中国大学生数学建模竞赛北京市二等奖（2020）
- 中国大学生数学竞赛北京市一等奖（2019）
