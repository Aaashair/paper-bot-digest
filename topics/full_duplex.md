# 第 3 板块 · 全双工与实时交互

*Full-Duplex & Real-Time Interaction*

> 所有以「实时双向/全双工交互机制或流式主动交互体验」为核心卖点的工作：纯语音全双工、多/全模态全双工交互、主动式流式音视频助手、端到端实时音视频交互系统及其评测

共 3 篇 A、15 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（3）

- **2026-11-13** · [Decode Before You Hear: Speculative Listening for Chunk-Interleaved Full-Duplex Speech Language Models](https://arxiv.org/abs/2611.06982) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.06982)
  - 听时用静音假设投机解码，无损加速全双工推理。
  - Method / Benchmark · 暂无 · CUHK-Shenzhen / Amphion
  - 技术关键词：Speculative Listening · self-speculative decoding · TickTock-Bench
- **2026-11-13** · [An LLM Is All You Need: Data-Efficient Adaptation to Full-Duplex, Word-Level Spoken Dialogue](https://arxiv.org/abs/2611.14774) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.14774)
  - 冻住多模态LLM，约30 GPU小时做成词级全双工。
  - Method · 暂无 · AveraLabs
  - 技术关键词：thinker-talker · full-duplex · finite-state machine
- **2026-11-11** · [Confucius4-R2T2: A Stable-Prefix Streaming ASR Model for Real Real-Time Transcription](https://arxiv.org/abs/2611.06043) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.06043)
  - 用最长稳定前缀把全上下文 ASR 变成不可回改的流式识别。
  - Method / Model/Weights · 代码已开源 · NetEase Youdao
  - 技术关键词：Longest Stable Prefix · LSP · stable-prefix

## B 类（15）

| 日期 | 标题 | 核心改动 | 类型 | 方法族 | 副板块 | 代码/数据 |
| --- | --- | --- | --- | --- | --- | --- |
| [2026-11-28](../issues/2026-11-28.md) | [$μ$-Bench: Benchmarking Multi-User Task Completion in Shared Interaction Voice Agents](https://arxiv.org/abs/2611.34920)<br><sub>Shanghai Jiao Tong University / Shanghai Artificial Intelligence Laboratory / Tsinghua University</sub> | 以反应式多用户仿真评测共享全双工语音联合任务成功 | Benchmark / Dataset | 数据与评测 | — | [代码已开源](https://github.com/lqh1106/mu-bench) |
| [2026-11-25](../issues/2026-11-25.md) | [BASE: A Backend-Agnostic Streaming Embodiment Layer for Full-Duplex Conversational Avatars](https://arxiv.org/abs/2611.30388)<br><sub>United Arab Emirates University</sub> | 只读输出语音驱动化身，并用DAHP缓解历史漂移 | System/Code / Method | 架构与流式 | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [Duopra: From Full-Duplex Conversation to Full-Duplex Agency](https://arxiv.org/abs/2611.25773)<br><sub>Shanghai Jiao Tong University / Tencent</sub> | 全双工前端学工具调用与委派，同后端Pass@1从4.7%升至44.7% | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Constructing Dynamic Conversations with Neural Back-channel Generation and Voice-line Scheduling](https://arxiv.org/abs/2611.24086)<br><sub>University of Toronto, JALI Research · ACM SIGGRAPH MIG 2026</sub> | 独立配音经全双工调度插入重叠与反馈，合成可控双人对话 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [When Should a Voice Agent Speak? End-of-Turn Detection in Turkish](https://arxiv.org/abs/2611.25489) | 土耳其语轮次结束检测：微调TurnGPT结合时序可缩短回复延迟 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Leveraging Dual-Process Theory for Multimodal Multiparty Turn-Taking Prediction](https://arxiv.org/abs/2611.19484)<br><sub>IEEE TASLP (submitted)</sub> | 用双过程框架在连续多方对话中发现并核验话轮转换 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Latency, Speech Recognition and Turn-Taking in Voice Agents for Spanish Phone Negotiation: An Externally Measured Comparison of Pipecat, LiveKit and GPT-Live](https://arxiv.org/abs/2611.19118)<br><sub>Freight Technologies Inc. (Fr8Tech) AI Lab</sub> | 外部测量对比三种西语电话议价语音智能体的延迟与抢话 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Does the Voice Matter? Evaluating Frustration Detection on Deployed Clinical Voice-Agent Calls](https://arxiv.org/abs/2611.21001)<br><sub>Ufonia · ML4H 2026; GenAI4H workshop @ NeurIPS 2026</sub> | 部署临床语音座席的短轮次上，纯转写几乎检不出挫败。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Kezek: Splitting Mono Two-Person Conversations into Per-Speaker Tracks for Full-Duplex Dialogue Data](https://arxiv.org/abs/2611.16933) | 把双人单声道对话拆成对齐分轨，专供全双工数据。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [JEV-VAD: Efficient Semantic Endpointing via Task-First Conditioning and Decoder-Prefix Pruning](https://arxiv.org/abs/2611.15362)<br><sub>Tianjin University</sub> | 无转写语义端点：任务前置、标量头与解码器前缀剪枝 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [AVCC: Audio-Visual Conversation Corpus for Turn-Taking Prediction with a Human Benchmark](https://arxiv.org/abs/2611.13957)<br><sub>KTH</sub> | 把 31 小时单机位对话做成带人类对照的轮次预测基准。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Omni-JEV: Text and Dual-Stream Speech Decisions](https://arxiv.org/abs/2611.13777)<br><sub>Merit Interactive Research Institute</sub> | 在片段终点用文本或双流语音预测全双工五类动作。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Real-Time Short-Response Selection for Spoken Dialogue Systems](https://arxiv.org/abs/2611.09057)<br><sub>The University of Osaka</sub> | 在VAP上用对比学习实时挑选预生成短回复以掩盖生成延迟。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Joi-Bench-Task: Benchmarking Task Coordination in Full-duplex Voice Agents through Interactive Simulation](https://arxiv.org/abs/2611.12118)<br><sub>Tencent</sub> | 用可干预模拟器评测语音智能体任务协调，商用系统仍失败。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Benchmarking Speaker Embedders in the Sub-Second Regime for Real-Time Voice AI Agents](https://arxiv.org/abs/2611.09516)<br><sub>AIST 2026</sub> | 亚秒预算下对比开源说话人嵌入，给出实时语音助手部署建议。 | — | — | — | 暂无 |

## 副板块收录（2）

主板块在别处、兼属本板块的论文。

- 2026-11-25 · B · [BEARING: Who Is Talking to Whom? Grounding Acoustic Direction in Vision for Online Multi-Party Conversation](https://arxiv.org/abs/2611.31735)（主板块：空间音视频）
- 2026-11-25 · B · [Speak When You See It: Proactive Task Assistants Should Wait for Evidence, Not the Clock](https://arxiv.org/abs/2611.30895)（主板块：第一人称与全景理解）

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
