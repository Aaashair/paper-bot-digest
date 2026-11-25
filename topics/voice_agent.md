# 第 4 板块 · 语音/多模态智能体

*Voice & Multimodal Agents*

> 语音驱动的 Agent、工具/函数调用、多轮任务执行；纯文本或纯 GUI 智能体不收

共 1 篇 A、14 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（1）

- **2026-11-11** · [Confucius4-R2T2: A Stable-Prefix Streaming ASR Model for Real Real-Time Transcription](https://arxiv.org/abs/2611.06043) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.06043)
  - 用最长稳定前缀把全上下文 ASR 变成不可回改的流式识别。
  - Method / Model/Weights · 代码已开源 · NetEase Youdao
  - 技术关键词：Longest Stable Prefix · LSP · stable-prefix

## B 类（14）

| 日期 | 标题 | 核心改动 | 类型 | 代码/数据 |
| --- | --- | --- | --- | --- |
| [2026-11-24](../issues/2026-11-24.md) | [StudioBench: Benchmarking Agentic Multimodal Large Language Models for Productive Audiovisual Creation](https://arxiv.org/abs/2611.28902)<br><sub>Tencent</sub> | 用33个工具评测MLLM端到端制作有声短片 | Benchmark | [代码已开源](https://github.com/openraiser/StudioBench) |
| [2026-11-24](../issues/2026-11-24.md) | [Visual-RFT++: Extending Visual Reinforcement Fine-Tuning to Multimodal Tool Use](https://arxiv.org/abs/2611.30193)<br><sub>Shanghai AI Laboratory</sub> | 将视觉RFT扩展到搜网与图像代码工具调用 | Method / Benchmark | [代码已开源](https://github.com/Liuziyu77/Visual-RFT) |
| [2026-11-24](../issues/2026-11-24.md) | [SayWhen: Set-Valued Semantic Commitment for Low-Regret Early Speech](https://arxiv.org/abs/2611.31101)<br><sub>Ryquo / App-In Club · NeurIPS 2026 Workshop PTA</sub> | 测试时控制器在用户话音结束前做低后悔的提前开口 | Method | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [EMIP: Embodied Multi-Party Interaction Platform](https://arxiv.org/abs/2611.29333)<br><sub>Okayama Prefectural University</sub> | 基于Minecraft的多人全双工语音与同时动作具身平台 | System/Code | [代码已开源](https://github.com/AI-Humans-Lab/EMIP-Embodied-Multi-Party-Interaction-Platform) |
| [2026-11-24](../issues/2026-11-24.md) | [Voice Agents: From Auditory Intelligence to Auditory Agency](https://arxiv.org/abs/2611.29465)<br><sub>National University of Defense Technology</sub> | 用承诺边界与能动闭环刻画语音从感知到可追责行动 | Tech Report | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Can Omni-modal LLMs Understand Spoken Intentions?](https://arxiv.org/abs/2611.24706)<br><sub>Renmin University of China / WeChat Vision, Tencent · ICLR 2027 (withdrawn)</sub> | 提出O-IN-Bench，评测全模态模型对口语意图的识别与内容满足。 | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Great Listeners, Poor Decision-Makers: Rethinking Agentic Audio AI](https://arxiv.org/abs/2611.23847) | 指出语音代理瓶颈在决策，显式门控将旁话执行从41%降至约10% | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [When Should a Voice Agent Speak? End-of-Turn Detection in Turkish](https://arxiv.org/abs/2611.25489) | 土耳其语轮次结束检测：微调TurnGPT结合时序可缩短回复延迟 | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Latency, Speech Recognition and Turn-Taking in Voice Agents for Spanish Phone Negotiation: An Externally Measured Comparison of Pipecat, LiveKit and GPT-Live](https://arxiv.org/abs/2611.19118)<br><sub>Freight Technologies Inc. (Fr8Tech) AI Lab</sub> | 外部测量对比三种西语电话议价语音智能体的延迟与抢话 | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Does the Voice Matter? Evaluating Frustration Detection on Deployed Clinical Voice-Agent Calls](https://arxiv.org/abs/2611.21001)<br><sub>Ufonia · ML4H 2026; GenAI4H workshop @ NeurIPS 2026</sub> | 部署临床语音座席的短轮次上，纯转写几乎检不出挫败。 | — | 暂无 |
| [2026-11-15](../issues/2026-11-15.md) | [Opus-Chat: Exploring How Speech Language Models Remember and Think](https://ieeexplore.ieee.org/abstract/document/11782816/)<br><sub>IEEE TASLP 2026</sub> | OpusLM后续开源SpeechLM族，接推理式口语对话并谈记忆。 | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Human-Likeness and Conversational Preference Diverge for Synthesized Agent Speech in Customer-Service Calls](https://arxiv.org/abs/2611.16051)<br><sub>Fluid Concepts Research</sub> | 客服合成语音的拟人度与愿不愿聊它并不一致 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Joi-Bench-Task: Benchmarking Task Coordination in Full-duplex Voice Agents through Interactive Simulation](https://arxiv.org/abs/2611.12118)<br><sub>Tencent</sub> | 用可干预模拟器评测语音智能体任务协调，商用系统仍失败。 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Benchmarking Speaker Embedders in the Sub-Second Regime for Real-Time Voice AI Agents](https://arxiv.org/abs/2611.09516)<br><sub>AIST 2026</sub> | 亚秒预算下对比开源说话人嵌入，给出实时语音助手部署建议。 | — | 暂无 |

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
