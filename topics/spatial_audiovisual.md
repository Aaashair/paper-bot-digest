# 第 1 板块 · 空间音视频

*Spatial Audio & Audio-Visual Understanding*

> 重点聚焦空间理解，Audio-only 与 Audio-Visual 双线并重；与板块 2–5 同一标准（只收好与非常好），无保护名额

共 2 篇 A、8 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（2）

- **2026-11-13** · [MESH: Multi-receiver Evaluation of Spatial Hearing across Egocentric and Allocentric Views](https://arxiv.org/abs/2611.16787) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.16787)
  - 开源近4万题MESH，评测多接收器自他心空间听觉，现有模型远未过关。
  - Benchmark / Dataset · 代码已开源
  - 技术关键词：spatial hearing · egocentric · allocentric
- **2026-11-11** · [AudioSphere: Towards Self-Supervised Spatial Audio Representation Models](https://arxiv.org/abs/2611.09275) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.09275)
  - Ambisonics掩码自编码学空间表征，并发布冻结SELD评测。
  - Method / Benchmark · 代码已开源 · Donders Institute, Radboud University
  - 技术关键词：masked autoencoder · SELD · Ambisonics

## B 类（8）

| 日期 | 标题 | 核心改动 | 类型 | 方法族 | 副板块 | 代码/数据 |
| --- | --- | --- | --- | --- | --- | --- |
| [2026-11-25](../issues/2026-11-25.md) | [BEARING: Who Is Talking to Whom? Grounding Acoustic Direction in Vision for Online Multi-Party Conversation](https://arxiv.org/abs/2611.31735)<br><sub>University of Denver</sub> | 免标注配准阵列方位到画面，在线判别谁对谁说。 | Method / System/Code | 在线强化学习 / 离线对齐 | 全双工与实时交互 | 暂无 |
| [2026-11-25](../issues/2026-11-25.md) | [From Spatial Perception to Speech Recovery: Binaural Semantic Adaptation for Spatially Grounded Multi-Talker Transcription](https://arxiv.org/abs/2611.29012)<br><sub>Xi'an Jiaotong-Liverpool University; University of Liverpool</sub> | 冻结骨干，用双耳共享编码和耳间差分补齐空间转写 | Method / Benchmark | 数据与评测 | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Insight into Parametric First-Order Ambisonics Upscaling in Time and Frequency Domains](https://arxiv.org/abs/2611.23089)<br><sub>Ben-Gurion University</sub> | 按能量选早反射做FOA升阶，时频域更优 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Learning Spatially Aware Audio-Visual Features from Videos with Mono Audio](https://arxiv.org/abs/2611.19593)<br><sub>Georgia Tech / Dolby · WACV 2027</sub> | 单声道视频渲染伪双耳，学习可泛化的空间视听表征。 | — | — | — | 暂无 |
| [2026-11-15](../issues/2026-11-15.md) | [Any Channel Count, One Token Stream: Incorporating Spatial Audio Understanding and Reasoning into Large Audio-Language Models](https://arxiv.org/abs/2611.18112)<br><sub>Alibaba Group / Zhejiang University · ICLR 2027 (withdrawn)</sub> | 任意通道空间LALM：交织空间token，并发布SpheraQA | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Discrete Coding and Masked Modeling for Text-to-Stereo Audio Generation](https://dl.acm.org/doi/abs/10.1145/3767308.3835212)<br><sub>ACM MM 2026</sub> | 离散立体声编码加掩码建模，做文本生成立体声。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [AURA: Auditory Spatial Intelligence via a Unified Representation from a General-Audio Encoder through Complete Alignment](https://arxiv.org/abs/2611.13687)<br><sub>Southeast University</sub> | 冻结通用音频编码并对齐，用于空间音频问答。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [BAmbiDrop: Array-Agnostic Speech Enhancement with Zero-Shot binaural Reproduction using Multi-center Ambisonics Encoding](https://arxiv.org/abs/2611.10561)<br><sub>ICASSP 2027 (submitted)</sub> | 多中心Ambisonics掩码实现任意阵列零样本双耳增强。 | — | — | — | 暂无 |

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
