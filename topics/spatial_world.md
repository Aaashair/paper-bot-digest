# 第 5 板块 · 空间音视频与世界模型

*Spatial Audio-Visual & World Models*

> 空间音频（双耳/Ambisonics/声源定位/RIR）、3D 视听感知、带声音或空间交互的物理/交互式世界模型；纯视频世界模型只在与本研究强相关时收

共 3 篇 A、13 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（3）

- **2026-11-24** · [World Models as Native Latent Action Models](https://arxiv.org/abs/2611.30898) · [第 8 期卡片](../issues/2026-11-24.md#a-2611.30898)
  - 从预训练视频世界模型抽出 native 隐空间动作并预训练 VLA
  - Method / Model/Weights · 仅主页 · SenseTime / NTU S-Lab
  - 技术关键词：Native LAM · PAWlicy · IDM
- **2026-11-13** · [MESH: Multi-receiver Evaluation of Spatial Hearing across Egocentric and Allocentric Views](https://arxiv.org/abs/2611.16787) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.16787)
  - 开源近4万题MESH，评测多接收器自他心空间听觉，现有模型远未过关。
  - Benchmark / Dataset · 代码已开源
  - 技术关键词：spatial hearing · egocentric · allocentric
- **2026-11-11** · [AudioSphere: Towards Self-Supervised Spatial Audio Representation Models](https://arxiv.org/abs/2611.09275) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.09275)
  - Ambisonics掩码自编码学空间表征，并发布冻结SELD评测。
  - Method / Benchmark · 代码已开源 · Donders Institute, Radboud University
  - 技术关键词：masked autoencoder · SELD · Ambisonics

## B 类（13）

| 日期 | 标题 | 核心改动 | 类型 | 代码/数据 |
| --- | --- | --- | --- | --- |
| [2026-11-24](../issues/2026-11-24.md) | [From Spatial Perception to Speech Recovery: Binaural Semantic Adaptation for Spatially Grounded Multi-Talker Transcription](https://arxiv.org/abs/2611.29012)<br><sub>Xi’an Jiaotong-Liverpool University</sub> | 修复空间音频 LLM 语义编码器单耳问题，以提升双耳多说话人转写 | Method / Benchmark | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [ReactDrive: Self-Reactive Driving World Model](https://arxiv.org/abs/2611.27024)<br><sub>Bosch Research North America; Stony Brook University</sub> | 定义驾驶世界模型自反应性并用共享状态联合生成视频 | Method | [仅主页](https://reactdrive.github.io/) |
| [2026-11-24](../issues/2026-11-24.md) | [Audio-Visual Rearrangement](https://arxiv.org/abs/2611.30171)<br><sub>China Agricultural University</sub> | 提出听指令取物送达的视听重排任务与空间音频基线 | Dataset / Method | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [BEARING: Who Is Talking to Whom? Grounding Acoustic Direction in Vision for Online Multi-Party Conversation](https://arxiv.org/abs/2611.31735)<br><sub>University of Denver</sub> | 阵列声方向配准到画面，在线判定说话人与受话人 | Method | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [SWAM: State-aware World Action Model for Multi-Agent 3D Environments](https://arxiv.org/abs/2611.30042)<br><sub>New York University</sub> | 用独立状态模型驱动多代理三维世界的自回归视觉生成 | Method | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [NAVIQUAL-XR: Finding the Sweet Spot of a Live Music Environment in Augmented Reality](https://arxiv.org/abs/2611.28056)<br><sub>University College Dublin · ACM TOMM (submitted)</sub> | 用BINAQUAL预测AR现场音乐的六自由度听音甜点 | Method | 暂无 |
| [2026-11-24](../issues/2026-11-24.md) | [SoundFleXR: Selectively Constraining Axes of Audio Rendering Presentations](https://arxiv.org/abs/2611.28020)<br><sub>Brown University; Carnegie Mellon University</sub> | 对比XR中立体声、仅方位HRTF与全HRTF的定位效果 | Method | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Insight into Parametric First-Order Ambisonics Upscaling in Time and Frequency Domains](https://arxiv.org/abs/2611.23089)<br><sub>Ben-Gurion University</sub> | 按能量选早反射做FOA升阶，时频域更优 | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Learning Spatially Aware Audio-Visual Features from Videos with Mono Audio](https://arxiv.org/abs/2611.19593)<br><sub>Georgia Tech / Dolby · WACV 2027</sub> | 单声道视频渲染伪双耳，学习可泛化的空间视听表征。 | — | 暂无 |
| [2026-11-15](../issues/2026-11-15.md) | [Any Channel Count, One Token Stream: Incorporating Spatial Audio Understanding and Reasoning into Large Audio-Language Models](https://arxiv.org/abs/2611.18112)<br><sub>Alibaba Group / Zhejiang University · ICLR 2027 (withdrawn)</sub> | 任意通道空间LALM：交织空间token，并发布SpheraQA | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Discrete Coding and Masked Modeling for Text-to-Stereo Audio Generation](https://dl.acm.org/doi/abs/10.1145/3767308.3835212)<br><sub>ACM MM 2026</sub> | 离散立体声编码加掩码建模，做文本生成立体声。 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [AURA: Auditory Spatial Intelligence via a Unified Representation from a General-Audio Encoder through Complete Alignment](https://arxiv.org/abs/2611.13687)<br><sub>Southeast University</sub> | 冻结通用音频编码并对齐，用于空间音频问答。 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [BAmbiDrop: Array-Agnostic Speech Enhancement with Zero-Shot binaural Reproduction using Multi-center Ambisonics Encoding](https://arxiv.org/abs/2611.10561)<br><sub>ICASSP 2027 (submitted)</sub> | 多中心Ambisonics掩码实现任意阵列零样本双耳增强。 | — | 暂无 |

## 副板块收录（2）

主板块在别处、兼属本板块的论文。

- 2026-11-24 · B · [G0.7: Scaling Up a Fast World Action Model with Long Context](https://arxiv.org/abs/2611.31822)（主板块：第一人称与全景视觉）
- 2026-11-24 · B · [Seeing Together, Acting Apart: Shared Environmental Understanding for Multi-Robot Navigation](https://arxiv.org/abs/2611.30310)（主板块：第一人称与全景视觉）

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
