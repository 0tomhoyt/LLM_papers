# LLM Papers

LLM 相关论文的中文阅读笔记整理，按主题分类。

## 目录

### 01_综述与全景

| 论文 | 作者 | 年份 | 关键词 | 笔记 |
|------|------|------|--------|------|
| LLMOrbit: A Circular Taxonomy of Large Language Models | Microsoft | 2026.04 | 缩放墙、模型分类、Agentic AI、架构演进 | [阅读笔记](01_综述与全景/LLMOrbit/01_阅读笔记.md) |
| Mapping the LLM Landscape: A Cross-Family Survey (Ma et al.) | Ma et al. | 2024.12 | GPT/Claude/Gemini/Llama/GLM/Qwen 六大家族对比、性能排名 | [阅读笔记](01_综述与全景/Mapping_LLM_Landscape_Ma/01_阅读笔记.md) |
| Mapping the LLM Landscape: A Cross-Family Survey (Wang et al.) | Wang et al. | 2026 | 架构收敛、对齐安全、开源/闭源互补 | [阅读笔记](01_综述与全景/Mapping_LLM_Landscape_Wang/01_阅读笔记.md) |
| Beyond the Black Box: A Survey on the Theory and Mechanism of LLMs | Zhang et al. | 2026.01 | 生命周期分类、缩放定律、ICL机制、对齐方法、幻觉、线性表示假说 | [阅读笔记](01_综述与全景/Beyond_the_Black_Box/01_阅读笔记.md) |

### 02_架构与训练

| 论文 | 作者 | 年份 | 关键词 | 笔记 |
|------|------|------|--------|------|
| DeepSeek-V4 | DeepSeek-AI | 2025 | MoE、混合注意力、1M上下文、Muon优化器 | [阅读笔记](02_架构与训练/DeepSeek_V4/01_阅读笔记.md) · [注意力机制详解](02_架构与训练/DeepSeek_V4/02_混合注意力机制详解.md) |

## 项目结构

```
├── 01_综述与全景/
│   ├── LLMOrbit/
│   │   ├── paper.pdf
│   │   └── 01_阅读笔记.md
│   ├── Mapping_LLM_Landscape_Ma/
│   │   ├── paper.pdf
│   │   └── 01_阅读笔记.md
│   ├── Mapping_LLM_Landscape_Wang/
│   │   └── 01_阅读笔记.md
│   └── Beyond_the_Black_Box/
│       └── 01_阅读笔记.md
├── 02_架构与训练/
│   └── DeepSeek_V4/
│       ├── paper.pdf
│       ├── 01_阅读笔记.md
│       └── 02_混合注意力机制详解.md
├── README.md
└── .gitignore
```

## 笔记格式

每篇笔记包含：
- 论文基本信息（标题、作者、年份、关键词）
- 研究背景与问题
- 核心贡献 / 创新点
- 方法与模型详解
- 实验与结果
- 结论与局限性
- 难懂概念的比喻解释（💡 标注）

## 添加新论文

1. 确定分类目录（`01_综述与全景` / `02_架构与训练` / 新建类别）
2. 创建文件夹：`论文简称_第一作者姓`
3. 放入原始 PDF 并重命名为 `paper.pdf`
4. 创建 `01_阅读笔记.md`，按上述格式撰写
