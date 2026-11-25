# 第 7 板块 · 上游方法前沿（后训练/推理）

*Upstream Methods (Post-Training / Reasoning)*

> 只收 NLP/VLM 刚出的硬核新方法（新 RL 算法、在线蒸馏、隐空间推理、测试时扩展等）的原创或跨模态首篇；普通刷榜/迁移文不收。试运行

本板块只收 A（原创方法或首次跨模态应用），试行。

共 5 篇 A、0 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（5）

- **2026-11-24** · [Gumbel Substitution: Removing Sampler Drift from RL Without Trusting the Sampler](https://arxiv.org/abs/2611.27375) · [第 8 期卡片](../issues/2026-11-24.md#a-2611.27375)
  - 用公开Gumbel噪声替换采样，去掉不信任sampler的漂移
  - Method · 代码已开源 · Reliquary
  - 技术关键词：Gumbel substitution · GSPO · CISPO
- **2026-11-24** · [Unlocking the Power of Loops in Pretrained LLMs with Loop Residuals](https://arxiv.org/abs/2611.31094) · [第 8 期卡片](../issues/2026-11-24.md#a-2611.31094)
  - 用循环残差把预训练LLM改成可测试时扩展的loop
  - Method · 代码已开源 · National University of Singapore
  - 技术关键词：LoopRes · test-time scaling · Attention Residuals
- **2026-11-24** · [Composable Soft-Prompt Distillation of RL Experts: Toward Continual Post-Training](https://arxiv.org/abs/2611.27376) · [第 8 期卡片](../issues/2026-11-24.md#a-2611.27376)
  - 把每个RL专家蒸馏成软提示，拼接即可组合
  - Method · 代码已开源 · University of California, Santa Barbara / Mind Lab / Apple
  - 技术关键词：CSPD · MOPD · on-policy distillation
- **2026-11-24** · [Verifiable On-Policy Distillation](https://arxiv.org/abs/2611.30325) · [第 8 期卡片](../issues/2026-11-24.md#a-2611.30325)
  - 把可验证奖励投影到教师隐式奖励，做成稠密VOPD目标
  - Method · 仅主页 · Stanford University / Google DeepMind
  - 技术关键词：VOPD · OPD · RLVR
- **2026-11-11** · [Mental Imagery That Matters: Curing Latent Collapse in Multimodal Reasoning](https://arxiv.org/abs/2611.10423) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.10423)
  - 揭示潜空间视觉推理的心象坍缩，并用对比蒸馏使其真正生效。
  - Method · 仅主页 · UT Austin / UC Berkeley / Bespoke Labs
  - 技术关键词：AnchorSim · MSC · contrastive distillation

## B 类（0）

暂无。

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
