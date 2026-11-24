# Paper Bot 推送归档 / Paper digest archive

这是 [Paper Bot](https://cursor.com) 每两天一次的论文推送归档：关注语音、音频与空间/第一人称多模态方向，经过筛选后再按 A/B 分级。

最新一期同时发布在 [Paper Bot 推送 Page](https://cursor.com/canvas/store-e1c619e9-9a18-45c2-be84-6a0452d9876f/64510c92-4dce-4196-b8b8-1f618dc85549)。本仓库只保存已经筛选过的内容，不含未筛的全量索引。想看往期，直接点下面的目录即可。

## 关注方向

### Omni-Modal & Speech

- **Omni 基座模型**（Omni-Modal Foundation Models）
- **全双工对话**（Full-Duplex Spoken Dialogue）
- **语音智能体**（Interactive Voice Agents）
- **语音-文本对齐**（Speech-Text Alignment）
- **音频理解与生成**（Audio Understanding & Generation）

### Spatial & Reasoning

- **空间音视频**（Spatial Audio-Visual Understanding & Generation）
- **第一人称视觉**（Egocentric Vision Understanding）
- **全景视觉**（Omnidirectional & Panoramic Vision Understanding）
- **多模态后训练**（Multimodal Post-Training）

## 往期目录

最新在前。

| 期次 | 日期 | A | B | 本期要点 | 归档 |
| --- | --- | ---: | ---: | --- | --- |
| 第 7 期 | 2026-11-23 | 1 | 16 | [RoboCap-10k](https://arxiv.org/abs/2611.26916) | [Markdown](issues/2026-11-23.md) |
| 第 6 期 | 2026-11-21 | 3 | 14 | [WeMM-Video](https://arxiv.org/abs/2611.26409)；[HumanCOIN](https://arxiv.org/abs/2611.26434)；[EgoWitness](https://arxiv.org/abs/2611.25849) | [Markdown](issues/2026-11-21.md) |
| 第 5 期 | 2026-11-19 | 1 | 31 | [Evolve in Panorama, Render in View](https://arxiv.org/abs/2611.22733) | [Markdown](issues/2026-11-19.md) |
| 第 4 期 | 2026-11-17 | 1 | 35 | [HubEgo-100K](https://arxiv.org/abs/2611.21938) | [Markdown](issues/2026-11-17.md) |
| 第 3 期 | 2026-11-15 | 0 | 5 | — | [Markdown](issues/2026-11-15.md) |
| 第 2 期 | 2026-11-13 | 5 | 28 | [Duo](https://arxiv.org/abs/2611.15131)；[Decode Before You Hear](https://arxiv.org/abs/2611.06982)；[An LLM Is All You Need](https://arxiv.org/abs/2611.14774)；[ZONOS3-Mini Technical Report](https://arxiv.org/abs/2611.16525)；[MESH](https://arxiv.org/abs/2611.16787) | [Markdown](issues/2026-11-13.md) |
| 第 1 期 | 2026-11-11 | 8 | 36 | [LAION-Audio-XL](https://arxiv.org/abs/2611.11592)；[Emilia2](https://arxiv.org/abs/2611.13614)；[LongCap](https://arxiv.org/abs/2611.11125)；[SPDMX](https://arxiv.org/abs/2611.09140)；[Confucius4-R2T2](https://arxiv.org/abs/2611.06043)；[AudioSphere](https://arxiv.org/abs/2611.09275)；[RoboMoCap](https://arxiv.org/abs/2611.10994)；[Mental Imagery That Matters](https://arxiv.org/abs/2611.10423) | [Markdown](issues/2026-11-11.md) |

## 说明

- A 类至少满足以下一条：扎实且预期影响大、可作 baseline、开拓新方向。卡片里的分级依据、数字和机构均来自当期筛选记录，没有的字段不会补写。
- B 类是完整但偏增量、工程或领域迁移的工作。
- 每期由 Paper Bot 流水线从 `runs/issues.json` 生成 Markdown，再提交到本仓库。
