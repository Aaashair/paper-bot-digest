# 第 2 板块 · 实时全双工交互

*Real-Time Full-Duplex Interaction*

> 边听边说、打断/轮次控制、backchannel、低延迟流式音视频对话系统

共 2 篇 A、10 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（2）

- **2026-11-13** · [Decode Before You Hear: Speculative Listening for Chunk-Interleaved Full-Duplex Speech Language Models](https://arxiv.org/abs/2611.06982) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.06982)
  - 听时用静音假设投机解码，无损加速全双工推理。
  - Method / Benchmark · 暂无 · CUHK-Shenzhen / Amphion
  - 技术关键词：Speculative Listening · self-speculative decoding · TickTock-Bench
- **2026-11-13** · [An LLM Is All You Need: Data-Efficient Adaptation to Full-Duplex, Word-Level Spoken Dialogue](https://arxiv.org/abs/2611.14774) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.14774)
  - 冻住多模态LLM，约30 GPU小时做成词级全双工。
  - Method · 暂无 · AveraLabs
  - 技术关键词：thinker-talker · full-duplex · finite-state machine

## B 类（10）

| 日期 | 标题 | 核心改动 | 类型 | 代码/数据 |
| --- | --- | --- | --- | --- |
| [2026-11-24](../issues/2026-11-24.md) | [UUBench: Understanding the Unspoken toward Full-Duplex Multimodal Interaction](https://arxiv.org/abs/2611.30157) | 提出评测全双工系统能否理解并回应未言明意图的基准 | Benchmark | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [BASE: A Backend-Agnostic Streaming Embodiment Layer for Full-Duplex Conversational Avatars](https://arxiv.org/abs/2611.30388) | 提出仅凭语音对接任意全双工后端的流式化身层 | Method / System/Code | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [Duopra: From Full-Duplex Conversation to Full-Duplex Agency](https://arxiv.org/abs/2611.25773)<br><sub>Shanghai Jiao Tong University / Tencent</sub> | 全双工前端学工具调用与委派，同后端Pass@1从4.7%升至44.7% | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Constructing Dynamic Conversations with Neural Back-channel Generation and Voice-line Scheduling](https://arxiv.org/abs/2611.24086)<br><sub>University of Toronto, JALI Research · ACM SIGGRAPH MIG 2026</sub> | 独立配音经全双工调度插入重叠与反馈，合成可控双人对话 | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Leveraging Dual-Process Theory for Multimodal Multiparty Turn-Taking Prediction](https://arxiv.org/abs/2611.19484)<br><sub>IEEE TASLP (submitted)</sub> | 用双过程框架在连续多方对话中发现并核验话轮转换 | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Kezek: Splitting Mono Two-Person Conversations into Per-Speaker Tracks for Full-Duplex Dialogue Data](https://arxiv.org/abs/2611.16933) | 把双人单声道对话拆成对齐分轨，专供全双工数据。 | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [JEV-VAD: Efficient Semantic Endpointing via Task-First Conditioning and Decoder-Prefix Pruning](https://arxiv.org/abs/2611.15362)<br><sub>Tianjin University</sub> | 无转写语义端点：任务前置、标量头与解码器前缀剪枝 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [AVCC: Audio-Visual Conversation Corpus for Turn-Taking Prediction with a Human Benchmark](https://arxiv.org/abs/2611.13957)<br><sub>KTH</sub> | 把 31 小时单机位对话做成带人类对照的轮次预测基准。 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Omni-JEV: Text and Dual-Stream Speech Decisions](https://arxiv.org/abs/2611.13777)<br><sub>Merit Interactive Research Institute</sub> | 在片段终点用文本或双流语音预测全双工五类动作。 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Real-Time Short-Response Selection for Spoken Dialogue Systems](https://arxiv.org/abs/2611.09057)<br><sub>The University of Osaka</sub> | 在VAP上用对比学习实时挑选预生成短回复以掩盖生成延迟。 | — | 暂无 |

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
