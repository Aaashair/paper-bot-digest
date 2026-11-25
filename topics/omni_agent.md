# 第 2 板块 · Omni 全模态模型与智能体

*Omni-Modal Models & Agents*

> 原生统一语音/音频+视觉+文本的基座与统一表征，及模型原生的全模态/音视频智能体能力；只收好与非常好

共 2 篇 A、20 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（2）

- **2026-11-21** · [WeMM-Video: Pushing the Frontiers of Open-Source Omni-Modal Video Understanding](https://arxiv.org/abs/2611.26409) · [第 6 期卡片](../issues/2026-11-21.md#a-2611.26409)
  - 腾讯开源双语全模态视频理解模型族，1.2T与120+基准称开源SOTA
  - Tech Report / Model/Weights · 代码已开源 · Tencent WeChat Vision / Tsinghua
  - 技术关键词：OPD · MrDPO · hybrid-thinking
- **2026-11-13** · [Duo: A Reciprocal World Model for Full-Duplex Interaction](https://arxiv.org/abs/2611.15131) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.15131)
  - 音视频全双工世界模型，边感知边生成可打断。
  - Tech Report / Method · 代码已开源 · inclusionAI
  - 技术关键词：RWM · full-duplex · dual rollout distillation

## B 类（20）

| 日期 | 标题 | 核心改动 | 类型 | 方法族 | 副板块 | 代码/数据 |
| --- | --- | --- | --- | --- | --- | --- |
| [2026-11-25](../issues/2026-11-25.md) | [Open-OmniCoach: Evidence-Enhanced Trajectory Learning for Omni Video Agents](https://arxiv.org/abs/2611.31891)<br><sub>ICLR 2027 Conference Submission</sub> | 用24.8万证据轨迹和SEPO训练全模态视频智能体 | Method / Dataset | 在线强化学习 / 数据与评测 | — | [代码已开源](https://github.com/Open-OmniCoach/omnicoach) |
| [2026-11-24](../issues/2026-11-24.md) | [StudioBench: Benchmarking Agentic Multimodal Large Language Models for Productive Audiovisual Creation](https://arxiv.org/abs/2611.28902)<br><sub>Tencent</sub> | 用33个工具评测MLLM端到端制作有声短片 | Benchmark | 数据与评测 | — | [代码已开源](https://github.com/openraiser/StudioBench) |
| [2026-11-24](../issues/2026-11-24.md) | [Visual-RFT++: Extending Visual Reinforcement Fine-Tuning to Multimodal Tool Use](https://arxiv.org/abs/2611.30193)<br><sub>Shanghai AI Laboratory</sub> | 将视觉RFT扩展到搜网与图像代码工具调用 | Method / Benchmark | 在线强化学习 | — | [代码已开源](https://github.com/Liuziyu77/Visual-RFT) |
| [2026-11-21](../issues/2026-11-21.md) | [HiUni: Harmonizing Understanding and Generation in Shared Visual Space](https://arxiv.org/abs/2611.26107)<br><sub>ERNIE Team, Baidu · ICLR 2027 Conference Submission</sub> | ERNIE用共享ViT与稠密骨干把VLM扩成理解+像素扩散生成 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [The Elephant in the Question: Unified Models Picture the Concepts Behind Their Answers](https://arxiv.org/abs/2611.24793) | 用统一模型自带图像生成器可视化token隐状态，无需训练解码器。 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Understanding Cross-Modal Inconsistency through Representation Subspaces in Omni Models](https://arxiv.org/abs/2611.22619)<br><sub>Soongsil University · EACL 2027 Main</sub> | 跨模态不一致的可解码方向并不等于可干预的答案子空间。 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Out of Sight, Still in Mind: Token Compression for Omni-LLMs](https://arxiv.org/abs/2607.21179)<br><sub>CoRR 2026</sub> | 训练无关地用音频对齐与文本代理压缩全模态视觉token。 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [PACD: Provenance-Aware Consensus Decoding for Mitigating Cross-Modal Hallucinations in Omnimodal Large Language Models](https://arxiv.org/abs/2611.22456)<br><sub>Xi'an Jiaotong University; University of Toronto; Tsinghua</sub> | 无训练解码，按溯源共识仲裁全模态跨模态幻觉。 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Beyond Attribute-Centric Fairness: Modelling and Mitigating Unified Bias Representation in Omni-modal Large Language Models](https://arxiv.org/abs/2611.22889)<br><sub>University of Oxford / CUHK / University of Sydney</sub> | 提出OmniDebias，抽取跨属性跨模态共享偏见再统一抑制。 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Can Omni-modal LLMs Understand Spoken Intentions?](https://arxiv.org/abs/2611.24706)<br><sub>Renmin University of China / WeChat Vision, Tencent · ICLR 2027 (withdrawn)</sub> | 提出O-IN-Bench，评测全模态模型对口语意图的识别与内容满足。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [UMM-JEPA: Generative Pretraining via Masked Next-Scale Representation Prediction for Unified Multimodal Models](https://arxiv.org/abs/2611.18668)<br><sub>Tencent Youtu Lab / University of Macau · ICLR 2027 (submission)</sub> | 用感知表征逐尺度预测做统一多模态预训练 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Omni-Workspace: Benchmarking Omni-Modal AI Assistants on Multimodal Workspace Tasks](https://arxiv.org/abs/2611.19202)<br><sub>Tongyi Lab / SJTU · ACL ARR 2026 October</sub> | 音视频图文工作区智能体基准，并加记忆与状态追踪 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [CineMME: From Dialogue Grounding to Narrative Reasoning in Multimodal Video Understanding](https://arxiv.org/abs/2611.15161)<br><sub>ByteDance / CASIA · NeurIPS 2026 (Evaluations & Datasets)</sub> | 对话锚定到剧情推理的叙事视频诊断基准 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [XBot-Omni: An Omni-Modal Model for Embodied Understanding and Interaction](https://arxiv.org/abs/2611.17160) | 将Omni扩展为可流式生成语音与肢体表情的具身架构 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [UniSpark: Exploring Hybrid Attention for Multimodal Understanding and Generation](https://arxiv.org/abs/2611.16517)<br><sub>Technical Report</sub> | 9B混合注意力统一模型，同时做视觉理解与图像生成 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [HyperSkill: Training-Free Omnimodal GRPO via Hypergraph-Indexed Skill-Library Evolution](https://arxiv.org/abs/2611.15178)<br><sub>NTU · NeurIPS 2026</sub> | 冻结骨干，用超图技能库替代GRPO参数更新 | — | 推理范式 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [dNaViT: Discrete Codes are General-Purpose Visual Representations](https://arxiv.org/abs/2611.12426)<br><sub>Meituan LongCat · 技术报告</sub> | 离散视觉 tokenizer，一套码兼顾理解、生成与编辑。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [UniWeaver: Harnessing Unified Multimodal Models for Interleaved Text-Image Generation](https://arxiv.org/abs/2611.13530)<br><sub>CUHK</sub> | 为统一多模态模型加规划与视觉校验，做交错图文生成。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [When Audio and Video Mislead: Evaluating Multimodal AI for Conversational Emotion Recognition](https://arxiv.org/abs/2611.11987)<br><sub>Dongguk University · AICompS 2026</sub> | 审计 Omni 模型：匹配的音视频有用，错配会误导。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [From Weapons to Events: Evaluating Evidential Support in Multimodal AI for Policing](https://arxiv.org/abs/2611.10245)<br><sub>University of Surrey (CVSSP)</sub> | 执法BWV上评测omni模型事件证据能否被记录支撑。 | — | — | — | 暂无 |

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
