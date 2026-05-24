# 你好，我是 icy

SJTU 大一在读，方向偏 **NLP / 大模型推理与训练**，正在尝试把学习内容做成可复现的代码与小项目，并探索 **云服务器上的训练与部署流程**。  
联系我：icy_wcz@sjtu.edu.cn

## 我在学什么（Learning Focus）
- **NLP 基础 → 深度学习基础 → Transformer / Attention → LLM**
- **LLM 训练全流程**：预训练数据流、SFT 数据处理与训练、推理生成策略（Top-k / Top-p / temperature 等）
- **RAG 系统与评测闭环**：向量检索 / 混合检索、拒答机制、批量评测与 badcase 分析

## 代表性仓库（Featured Repos）
### 1) NLP 学习与从零实现（NLP → Transformer → 类 LLaMA2）
- `nlp-exercises`：从中文分词、RNN/LSTM、Seq2Seq+Attention、Transformer，到 **Transformer 从零实现**，再到 **类 LLaMA2 架构 LLM 的关键组件实现**（RMSNorm / RoPE / GQA / KV Cache）与训练/生成流程练习。  
  Repo：https://github.com/Icyw-git/nlp-exercises

### 2) RAG 领域问答系统（含评测与日志）
- `RAG`：以推免政策文档为知识库的领域问答系统，支持 **向量检索** 与 **BM25+向量混合检索（RRF 融合）**，并实现 **拒答机制、批量评估、指标统计、评测日志与 badcase 分析**。  
  Repo：https://github.com/Icyw-git/RAG

### 3) 深度学习系统学习（PyTorch）
- `deep_learning-tutorial`：从张量/自动求导/训练流程到 CNN、RNN，再到 MNIST 与文本生成等综合案例；包含测试与基础工程化配置。  
  Repo：https://github.com/Icyw-git/deep_learning-tutorial

## 技术栈（Tech Stack）
- **语言**：Python /（学习中）C++
- **深度学习**：PyTorch，HuggingFace 生态（transformers / datasets / tokenizers / peft）
- **实验与数据**：Jupyter Notebook，numpy / pandas / matplotlib
- **环境管理**：conda
- **数据库**：MySQL
- **正在尝试**：云服务器训练与部署（持续更新）

## 近期目标（Roadmap）
- [ ] 完善一个“可复现”的 **LLM 推理实验**：统一评测脚本 + 消融实验记录  
- [ ] 完善 `RAG` 的评测集与 badcase 分析，形成可读报告（指标 + 失败类型）  
- [ ] 完善手写数字识别项目的训练流程（数据/训练/可视化/导出）  
- [ ] 持续学习数据结构与算法（C++ 实现），提高工程与算法基础

## 我希望参与的方向
- 大模型推理
- LLM 训练与对齐
- RAG / Agent
