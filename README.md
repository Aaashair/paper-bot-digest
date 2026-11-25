# Paper Bot 推送归档 / Paper digest archive

Paper Bot 的论文推送归档。初心是**只看好的和非常好的工作，宁缺毋滥**：本命方向是空间音频理解与空间音视频理解（含第一人称/全景场景），其次是实时多模态交互，再加上 Omni 全模态、音频理解与生成，以及世界模型与上游方法两个前沿雷达。

最新一期：**第 8 期 · 2026-11-24**（窗口 2026-11-22 – 2026-11-24）· [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-24/) · [Markdown](issues/2026-11-24.md) · 同时发布在 [Paper Bot 推送 Page](https://cursor.com/canvas/store-e1c619e9-9a18-45c2-be84-6a0452d9876f/64510c92-4dce-4196-b8b8-1f618dc85549)。

每一期都按**当时的页面风格**做成了可离线打开的网页（随系统浅色/深色切换），目录见 [GitHub Pages](https://aaashair.github.io/paper-bot-digest/)；Markdown 版在 `issues/`。本仓库只保存筛选过的内容，不含未筛的全量列表。

## 7 板块 · 三层漏斗（v4，2026-11-25 起）

每篇论文一个主板块，真正跨界时再给一个副板块。

### 第一层 · 本命精耕（A + 扎实 B，B 有保护名额）

1. **空间音视频**（Spatial Audio & Audio-Visual Understanding）—— 重点聚焦空间理解，Audio-only 与 Audio-Visual 双线并重；A + 扎实 B 均收，享有保护名额 · [专题索引](topics/spatial_audiovisual.md)

### 第二层 · 核心主线（只收好与非常好，B 合计每期最多 6 篇）

2. **Omni 全模态模型与智能体**（Omni-Modal Models & Agents）—— 原生统一语音/音频+视觉+文本的基座与统一表征，及模型原生的全模态/音视频智能体能力；只收好与非常好 · [专题索引](topics/omni_agent.md)
3. **实时全双工交互**（Real-Time Full-Duplex Interaction）—— 严格限定实时/流式交互：边听边说、边看边聊、话轮/提前开口/打断控制、多人全双工、实时主动交互助手、实时对话化身及其评测 · [专题索引](topics/full_duplex.md)
4. **音频理解与生成**（Audio Understanding & Generation）—— 语音/音频大模型（含纯音频侧推理、工具调用与语音能动性）、TTS/音效/音乐生成、语音-文本对齐与 tokenizer、大规模高质量语音数据集与管线 · [专题索引](topics/audio_ug.md)
5. **第一人称与全景理解**（Egocentric & Panoramic Understanding）—— 严格只收理解：第一人称（可穿戴/AI 眼镜）与 360° 全景视频的时空理解、问答、流式记忆、场景与三维几何感知 · [专题索引](topics/ego_pano_und.md)

### 第三层 · 前沿雷达（只收 A）

6. **交互式与通用世界模型**（Interactive & General World Models）—— 只收 A：实时可交互世界模拟、声画同步世界模型、具备通用范式启发意义的潜空间动力学/世界模型（如 Native LAM） · [专题索引](topics/world_models.md)
7. **上游方法前沿**（Upstream Methods (Post-Training / Reasoning / Architecture)）—— 只收 A：后训练（RL/OPD/对齐）、推理范式、测试时扩展与流式/通用架构的前沿突破；普通刷榜/迁移文不收 · [专题索引](topics/upstream_methods.md)

**每期上限（上限不是配额，达标少于上限就按实际输出，严禁降格凑数）：**

- A 类：每期 0–3 篇（全部板块合计；没有真突破时可以为 0）。
- B 类：核心主线（板块 2–5）全期合计最多 6 篇；板块 1「空间音视频」另有 2 篇保护名额，不会被其他板块挤掉。
- 前沿雷达（板块 6、7）只收 A。未公开数据/评测代码的纯 Benchmark 不进 A（板块 1 可视重要程度进 B）。

**推送节奏：每周三、周六两更（北京时间），对齐 arXiv 周一至周五的 5 个发布日。**

- 周三晚约 21:00：覆盖周一至周三上午的 arXiv（3 个发布日）+ 同期官方博客与 HF Daily。
- 周六上午约 10:00：覆盖周四至周五上午的 arXiv（2 个发布日）+ 本周发酵的重磅博客与 HF 高热工作。
- 漏跑时自动从上一期覆盖到的最后一天接着往后补，不会出现空窗。

**板块映射：** v3（2026-11-17 起）的「Omni 全模态基座」→ 2；「语音/多模态智能体」取消，按内容并入 2/3/4；「空间音视频与世界模型」拆成 1「空间音视频」与 6「交互式与通用世界模型」；「第一人称与全景视觉」→ 5「第一人称与全景理解」（只收理解）。往期论文按确定规则映射到新板块、不重新筛选，原板块保存在 `v3Dir` / `legacyDir` 字段；旧的专题链接保留为跳转页。

跨期精华：[highlights.md](highlights.md)（全部 A 类，按板块）。

## 往期目录

| 期次 | 日期 | 风格 | A | B | 精选 A | 阅读 |
| --- | --- | --- | ---: | ---: | --- | --- |
| 第 8 期 | 2026-11-24 | Kimi 风格 | 8 | 38 | [Granary-v2](https://arxiv.org/abs/2611.28248)；[World Models as Native Latent Action Models](https://arxiv.org/abs/2611.30898)；[EgoDepth-Bench](https://arxiv.org/abs/2611.30734)；[OmniV-Bench](https://arxiv.org/abs/2611.31022)；[Gumbel Substitution](https://arxiv.org/abs/2611.27375)；[Unlocking the Power of Loops in Pretrained LLMs with Loop Residuals](https://arxiv.org/abs/2611.31094)；[Composable Soft-Prompt Distillation of RL Experts](https://arxiv.org/abs/2611.27376)；[Verifiable On-Policy Distillation](https://arxiv.org/abs/2611.30325) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-24/) · [Markdown](issues/2026-11-24.md) |
| 第 7 期 | 2026-11-23 | OpenAI 风格 | 1 | 16 | [RoboCap-10k](https://arxiv.org/abs/2611.26916) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-23/) · [Markdown](issues/2026-11-23.md) |
| 第 6 期 | 2026-11-21 | 水墨风 | 3 | 14 | [WeMM-Video](https://arxiv.org/abs/2611.26409)；[HumanCOIN](https://arxiv.org/abs/2611.26434)；[EgoWitness](https://arxiv.org/abs/2611.25849) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-21/) · [Markdown](issues/2026-11-21.md) |
| 第 5 期 | 2026-11-19 | 杂志风 | 1 | 31 | [Evolve in Panorama, Render in View](https://arxiv.org/abs/2611.22733) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-19/) · [Markdown](issues/2026-11-19.md) |
| 第 4 期 | 2026-11-17 | Kimi 风格 | 1 | 35 | [HubEgo-100K](https://arxiv.org/abs/2611.21938) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-17/) · [Markdown](issues/2026-11-17.md) |
| 第 3 期 | 2026-11-15 | OpenAI 风格 | 0 | 5 | — | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-15/) · [Markdown](issues/2026-11-15.md) |
| 第 2 期 | 2026-11-13 | 水墨风 | 5 | 28 | [Duo](https://arxiv.org/abs/2611.15131)；[Decode Before You Hear](https://arxiv.org/abs/2611.06982)；[An LLM Is All You Need](https://arxiv.org/abs/2611.14774)；[ZONOS3-Mini Technical Report](https://arxiv.org/abs/2611.16525)；[MESH](https://arxiv.org/abs/2611.16787) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-13/) · [Markdown](issues/2026-11-13.md) |
| 第 1 期 | 2026-11-11 | 杂志风 | 8 | 36 | [LAION-Audio-XL](https://arxiv.org/abs/2611.11592)；[Emilia2](https://arxiv.org/abs/2611.13614)；[LongCap](https://arxiv.org/abs/2611.11125)；[SPDMX](https://arxiv.org/abs/2611.09140)；[Confucius4-R2T2](https://arxiv.org/abs/2611.06043)；[AudioSphere](https://arxiv.org/abs/2611.09275)；[RoboMoCap](https://arxiv.org/abs/2611.10994)；[Mental Imagery That Matters](https://arxiv.org/abs/2611.10423) | [网页](https://aaashair.github.io/paper-bot-digest/issues/2026-11-11/) · [Markdown](issues/2026-11-11.md) |

## 说明

- A 类至少满足以下一条：扎实且预期影响大、可作 baseline、开拓新方向；卡片标出满足的条款。数字只保留能在 arXiv 全文中逐字找到出处的，机构只写作者栏核实过的，没有的字段不会补写。
- B 类是完整、值得一看但偏增量的工作，按板块以紧凑表格列出（类型 / 方法族 / 副板块 / 代码状态）。第 1–8 期按当时规则：A 不设名额，B 每板块最多 15 篇（更早为 8 篇）。
- 「研究联想（模型推测，非论文结论）」以空间音频/空间音视频理解和实时多模态交互为锚点，只在确有自然迁移价值时给出，是模型推测，不是论文结论。
- 「传导阶段」只用于后训练 / RL / 蒸馏 / 推理范式的跨模态传导，必须附摘要原文依据并经独立核对；「🔴 本领域首落」会触发 A 类复核，不会挂在普通 B 上。
- 「代码/数据」由链接检测得出：代码已开源 / 权重已开源 / 数据已开源 / 仅主页 / 暂无；“即将开源”的空仓库记为仅主页。
- 每期由 Paper Bot 流水线从 `runs/issues.json` 生成当时风格的网页（`docs/issues/<date>/`）和 Markdown，再提交到本仓库。
