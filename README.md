<div align="center">

### wttc-nonelove

方向：**AI 应用**

把大模型接进真实业务流程，而不是做一个只能演示的 demo。

</div>

---

### 🧭 关于我

- 更关心 AI 结果**不可全信**这件事：优先设计人机协同与兜底策略（相似度阈值拒答、规则优先 / LLM 只补空、识别值与人工值分离、差异逐条确认）。
- 日常用 Claude Code / Codex / DeepSeek Harness / OpenCode 一类 Agentic Coding 工具开发。

### 🧩 主要项目

**[RAG ｜ 企业知识库智能问答系统](https://github.com/wttc-nonelove/RAG)**
`FastAPI` `Vue 3` `MySQL` `ChromaDB` `Neo4j` `Redis` `Docker Compose`
标题感知分块 → 向量召回 Top-5 → 相似度阈值拒答 → 知识图谱子图注入 Prompt → 答案带引用溯源。58 个后端模块约 4k 行 Python、70 个 REST 接口、9 张业务表，6 容器一键部署。

**[OCR-IPMS ｜ 基于 OCR-NLP 的智能项目管理系统](https://github.com/wttc-nonelove/OCR-IPMS)**
`FastAPI` `Vue 3 + TS` `MySQL` `PaddleOCR` `Docker Compose + Nginx`
打通「立项 → 合同解析 → 开票 → 回款 → 结项审批 → 统计报表」。19 张表、56 个接口、4 角色 RBAC、4 个 Alembic 迁移、46 个 pytest 用例。合同字段抽取「规则优先、LLM 只补空」，识别值与人工采用值分离存储，可审计。

**[Quad-OS ｜ 综合操作系统模拟平台](https://github.com/dyfyyds/quad-os-engine)**　*3 人协作，我负责存储管理核心与部署重构*
`Vue 3` `ECharts` `FastAPI` `SQLAlchemy 2.0` `MySQL` `Docker Compose`
把调度 / 存储 / 进程资源 / 设备管理整合成一个可「运行 / 暂停 / 单步」的虚拟机。我实现了分页引擎的异步预取与 tick 回放、backend / local 双模降级、缺页中断阻塞进程并打通「存储 ↔ 调度」因果闭环，补了 29 个跨模块集成测试用例。

### 🛠 技术栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![Vue3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

`RAG` · `知识图谱（Neo4j）` · `Prompt 工程` · `结构化输出` · `PaddleOCR` · `Docker Compose` · `pytest`

---

📫 lijtkevin6688@gmail.com
