# 第 4 板块 · 音频理解与生成

*Audio Understanding & Generation*

> 语音/音频大模型（含纯音频侧推理、工具调用与语音能动性）、TTS/音效/音乐生成、语音-文本对齐与 tokenizer、大规模高质量语音数据集与管线

共 5 篇 A、53 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（5）

- **2026-11-13** · [ZONOS3-Mini Technical Report](https://arxiv.org/abs/2611.16525) · [第 2 期卡片](../issues/2026-11-13.md#a-2611.16525)
  - 开源端侧零样本克隆TTS，15Hz新编解码，55语WER 6.71%
  - Tech Report / Model/Weights · 代码已开源
  - 技术关键词：latent MoE · ZAC-1 · zero-shot voice-cloning
- **2026-11-11** · [LAION-Audio-XL: A Web-Scale Corpus and Scaling Studies for Contrastive Language-Audio Pretraining](https://arxiv.org/abs/2611.11592) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.11592)
  - 3.65 亿对网页级音频-文本语料，以及开源 CLAP2 的缩放研究。
  - Dataset / Model/Weights · 代码已开源
  - 技术关键词：CLAP2 · NaFlex · contrastive
- **2026-11-11** · [Emilia2: A Large-Scale Dataset for Controllable Long-Form Speech Generation](https://arxiv.org/abs/2611.13614) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.13614)
  - 22.9 万小时多语长语音数据，支撑可控长时与多人合成。
  - Dataset / Benchmark · 暂无
  - 技术关键词：AR · NAR · long-form speech generation
- **2026-11-11** · [LongCap: Hour-Scale Timestamped Audio Captioning via Chunk-wise Processing](https://arxiv.org/abs/2611.11125) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.11125)
  - 小时级带时间戳音频描述：新基准与可外推的模型。
  - Method / Benchmark · 仅主页
  - 技术关键词：TAC · self-distillation · timestamped audio captioning
- **2026-11-11** · [SPDMX: Large-Scale Open Stem Audio From Symbolic Music](https://arxiv.org/abs/2611.09140) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.09140)
  - 从公有领域乐谱渲染大规模开放许可分轨音频。
  - Dataset · 暂无
  - 技术关键词：source separation · stem-conditioned synthesis · MIDI-to-audio

## B 类（53）

| 日期 | 标题 | 核心改动 | 类型 | 方法族 | 副板块 | 代码/数据 |
| --- | --- | --- | --- | --- | --- | --- |
| [2026-11-28](../issues/2026-11-28.md) | [TigerTTS: Draft-Guided Multi-Frame Parallel Speech-Token Language Model for Fast and Robust Text-to-Speech](https://arxiv.org/abs/2611.34241)<br><sub>Wiz Holdings Pte. Ltd.</sub> | 整句NAR草稿按帧注入，LLM每步并行预测12个token。 | Method / System/Code | 架构与流式 | — | 暂无 |
| [2026-11-25](../issues/2026-11-25.md) | [LiveAudio: From Bidirectional to Autoregressive Diffusion for Real-Time Streaming Video-to-Audio Generation](https://arxiv.org/abs/2611.30714)<br><sub>Tsinghua University / Monash University / Renmin University of China</sub> | 把双向视频到音频模型转成四步实时分块生成器 | Method / System/Code | 架构与流式 | — | [仅主页](https://streamaudio.github.io/) |
| [2026-11-25](../issues/2026-11-25.md) | [MusicListenBench: Can Audio LLMs Hear the Difference Yet?](https://arxiv.org/abs/2611.29375)<br><sub>Singapore University of Technology and Design/University of Venice · ICLR 2027 Conference Submission</sub> | 成对FLIP/STAY听辨，分开音乐变化与纯声响变化 | Benchmark | 数据与评测 / 在线强化学习 | — | [代码已开源](https://github.com/AMAAI-Lab/MusicListenBench) |
| [2026-11-25](../issues/2026-11-25.md) | [SoundWeaver: Compositional Warm-Starting for Text-to-Audio Diffusion Serving](https://arxiv.org/abs/2603.07865)<br><sub>University of Illinois Urbana-Champaign/Assured Intelligence · ICLR 2027 Conference Submission</sub> | 跨缓存片段拼成声学先验，自适应热启动文生音频扩散 | Method / System/Code | — | — | 暂无 |
| [2026-11-25](../issues/2026-11-25.md) | [BiSAT: Bidirectionally Aligned Semantic-Acoustic Tokenization for Speech Language Models](https://arxiv.org/abs/2611.30723)<br><sub>Japan Advanced Institute of Science and Technology</sub> | 双分支共享索引，把声学与语义收成单流词元 | Method | 架构与流式 | — | [仅主页](https://seekmind-lab.github.io/bisat-demo) |
| [2026-11-25](../issues/2026-11-25.md) | [SonicRender: Structured and Time-Grounded Rendering of Multi-Event Audio Scene Generation](https://arxiv.org/abs/2611.30241)<br><sub>Kling AI / The Chinese University of Hong Kong / Tsinghua University</sub> | 用场景图绑定声源与时间窗，并以绝对帧坐标一次生成多事件混合。 | Method | 架构与流式 | — | [仅主页](https://caiyunrui.github.io/SonicRender) |
| [2026-11-25](../issues/2026-11-25.md) | [Tenlai-TTS 2.0: Continuous-Representation LLM-Based TTS System with End-to-End Training](https://arxiv.org/abs/2611.29226)<br><sub>Tencent Yuanbao / Tencent Ethereal Audio Lab</sub> | 用有闭式信息率上界的高斯瓶颈端到端训练连续语音TTS | Method / Tech Report | 架构与流式 | — | [仅主页](https://tenlai-tts.github.io/Tenlai-TTS-2.0/) |
| [2026-11-25](../issues/2026-11-25.md) | [Reproducing the Speech Labels of Qwen3-Omni's Talker: Mimi in bf16, and a Last-Frame Pitfall](https://arxiv.org/abs/2611.32286)<br><sub>The Chinese University of Hong Kong, Shenzhen</sub> | 钉死Talker标签为moshi bf16 Mimi，填充末帧去掉噪声 | System/Code / Tech Report | — | — | [代码已开源](https://github.com/elpsykongloo/qwen3-omni-talker-finetune) |
| [2026-11-23](../issues/2026-11-23.md) | [SLP-Bench: Evaluating and Improving Acoustic Claims of Reasoning Audio Language Models on Clinical Speech](https://arxiv.org/abs/2611.27810)<br><sub>Callyope · ICASSP 2027 workshop (submitted)</sub> | 用临床感知评分核验推理音频模型思维链中的声学断言。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [PromptTTSD: Controllable Text to Spoken Dialogue Synthesis with Open-Ended Text Descriptions](https://arxiv.org/abs/2611.27601)<br><sub>BUPT / BIGAI</sub> | 从有声书抽八千小时对话，用开放式风格描述做可控多轮TTS。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [Neural Defend ARCAS 290M: A Robust Foundation Model for AI-Generated Audio Detection](https://arxiv.org/abs/2611.27784) | 封闭 290M 音频深伪检测器，在十个公开测试集上零样本评测。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [EAF-TTS: Rethinking Codec-Latent Coordinates for Flow TTS](https://arxiv.org/abs/2611.27214)<br><sub>AI Lab, Country Garden Services Group</sub> | 用无参数 ZCA 校正 Flow TTS 的 codec 隐空间坐标。 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [When Sounds Turn Heads: Recovering Event Timing That Audio LLMs Fail to Say](https://arxiv.org/abs/2611.25960)<br><sub>KAIST</sub> | 音频LLM内部头已跟踪事件时刻，无训练解码可纠时戳 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [Joint Language Modeling for In-the-Wild Speech-Scene Generation with Distinct Token Representations](https://arxiv.org/abs/2611.25503)<br><sub>Seoul National University</sub> | 语音与环境分流通用、交错LLM生成野外语音场景 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [From Attention to Semantics: Detecting and Mitigating Sound Event Hallucinations in Large Audio-Language Models](https://arxiv.org/abs/2611.25789)<br><sub>SJTU; OPPO · ICLR 2027 (desk rejected)</sub> | 用语义支撑检测并差分掩蔽缓解声音事件幻觉 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Great Listeners, Poor Decision-Makers: Rethinking Agentic Audio AI](https://arxiv.org/abs/2611.23847) | 指出语音代理瓶颈在决策，显式门控将旁话执行从41%降至约10% | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Beyond Co-Generation: Rethinking Jointness in Joint Audio-Video Generation](https://arxiv.org/abs/2611.22857)<br><sub>KAIST · Preprint</sub> | 用欠指定prompt检验T2AV是否真有跨模态协同 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Social Signal Bench: Evidence-Weighted Evaluation of Co-occurring Social Signals in Video and Audio](https://arxiv.org/abs/2611.22704)<br><sub>Interhuman AI · Preprint</sub> | 47小时音视频社交信号基准，提出证据加权F1 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [21Codec: Decoder-side Speaker Control for Text-to-Speech](https://arxiv.org/abs/2611.24094)<br><sub>Leiden University LIACS · ICASSP 2027 (submitted)</sub> | 流式codec从token去说话人、解码端条件控制音色 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [High-Fidelity Binarized Neural Vocoder](https://arxiv.org/abs/2611.22593)<br><sub>Institute of Acoustics, CAS · IEEE TASLP 2026</sub> | 混合精度二值神经声码器，音质接近部分全精度基线 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Harmonic Circuit: Chord Progression Lies in a Sparse Principal Information Flow in Symbolic Music Models](https://arxiv.org/abs/2611.24453)<br><sub>MBZUAI · NeurIPS 2026 Workshop on Interpretability for Discovery</sub> | 在ChatMusician/MuPT中定位驱动I–V–I终止的稀疏电路 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Location Matters: Layer-wise Prompt Conditioning for Voice--Style Disentanglement in Text-to-Speech](https://arxiv.org/abs/2611.24125)<br><sub>Leiden University LIACS · ICASSP 2027 (submitted)</sub> | 系统比较TTS中声线与风格prompt的注入层位置 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Learning from Distribution: Rethinking One-Hot Supervision for ASR and QA in Speech Language Models](https://arxiv.org/abs/2611.20436)<br><sub>Nankai University; Xingchen AGI Lab (China Telecom)</sub> | 用文本LLM条件分布替代one-hot，缓解ASR训练伤害口语QA | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Factorized Self-Supervised Speech Tokenization](https://arxiv.org/abs/2611.18898)<br><sub>Ubisoft La Forge; Mila; Stellenbosch University · NeurIPS 2026</sub> | 线性因式分解自监督语音分词，去掉说话人后token更稳、TTS更好 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Beyond Controllability: Speaker Diversity in Instruction-Guided Text-to-Speech](https://arxiv.org/abs/2611.19030)<br><sub>National Taiwan University; NVIDIA · ACL ARR 2026</sub> | 审计七个指令TTS的说话人多样性及其与可控性的分裂。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Decode Early, Verify Late: Streaming Offline Speech Recognizers Without Accuracy Loss](https://arxiv.org/abs/2611.20064)<br><sub>Nari Labs</sub> | 无训练框架让离线ASR流式出final，精度几乎等于greedy离线。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [A Systematic Study of Cross-Token Transfer for Data-Efficient Non-Verbal Text-to-Speech](https://arxiv.org/abs/2611.19145)<br><sub>Meta</sub> | 系统验证非言语语音合成里跨符号迁移能省目标样本。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [AudioTrace: File-Level Membership Detection for Audio Large Language Models](https://arxiv.org/abs/2611.21088)<br><sub>University of Cambridge</sub> | 提出无标注条件下音频文件级成员推断及配套受控基准。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Think2Listen: Evidence-Centric Learning For Agentic Audio Understanding With LALMS](https://arxiv.org/abs/2611.21083)<br><sub>ICLR 2027 submission</sub> | 用证据驱动的智能体循环改进大音频语言模型的多步推理。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Sada-ASR: A Production Multidialectal Arabic Speech Recognition System](https://arxiv.org/abs/2611.19512) | 生产级多方言阿拉伯ASR，120小时评测优于11个商用系统。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [No-Shot Text-to-Speech: Limitations of Zero-Shot TTS and its Evaluation Methods in Representing Queer and Transgender Voices](https://arxiv.org/abs/2611.20822)<br><sub>KTH; UC Berkeley · Interspeech 2026</sub> | 评估零样本TTS对酷儿与跨性别声音的复现及自动指标失配。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Rethinking Post-Training for Expressive Zero-Shot Text-to-Speech](https://arxiv.org/abs/2611.19787) | 三段后训练使零样本音色克隆按文本改写表达韵律。 | — | 离线对齐 / 在线强化学习 | — | 暂无 |
| [2026-11-15](../issues/2026-11-15.md) | [Opus-Chat: Exploring How Speech Language Models Remember and Think](https://ieeexplore.ieee.org/abstract/document/11782816/)<br><sub>IEEE TASLP 2026</sub> | OpusLM后续开源SpeechLM族，接推理式口语对话并谈记忆。 | — | — | — | 暂无 |
| [2026-11-15](../issues/2026-11-15.md) | [CoTTAGE: An Explainable Judge for Text-to-Audio Generation](https://arxiv.org/abs/2611.17644)<br><sub>NTU / Amazon AGI · ACL ARR 2026 August</sub> | 可解释TTA评判器，SFT后再用Thurstone-RL对齐人类 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Human-Likeness and Conversational Preference Diverge for Synthesized Agent Speech in Customer-Service Calls](https://arxiv.org/abs/2611.16051)<br><sub>Fluid Concepts Research</sub> | 客服合成语音的拟人度与愿不愿聊它并不一致 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Scaffolding Self-Transduction with Alignment Attention Mask for Aligner-Encoder ASR](https://arxiv.org/abs/2611.15087)<br><sub>NTT · IEEE SLT 2026</sub> | 用强制对齐掩码脚手架Aligner，揭示对齐推断瓶颈 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Speech Tokenizers are Vulnerable: Transferable Semantic Attack and Robust Tokenizer](https://arxiv.org/abs/2611.14929)<br><sub>NeurIPS 2026</sub> | 可迁移语义攻击揭示语音分词器脆弱，并提出ROSETok | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Right Answers, Inconsistent Evidence: Source-Level Counterfactual Auditing of Large Audio-Language Models](https://arxiv.org/abs/2611.15463)<br><sub>ICASSP 2027 (submitted)</sub> | 答对也可证据乱序：6.3%正确样本过不了声源反事实审计 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [RSE-TTS: Compact Text-to-Speech through Shared Text-Aware Reference Encoding and Generation](https://arxiv.org/abs/2611.15464) | 共享TTS骨干作参考编码器，1.18亿英配音优于同级克隆 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Can Music Generation Models Tap Along? Evaluating Generative Approaches to Beat Tracking](https://arxiv.org/abs/2611.14971)<br><sub>McGill CIRMMT / NYU / MBZUAI</sub> | 用MusicGen生成同步打击乐来做节拍跟踪，GTZAN接近SOTA | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Harmony: Bridging Audio Understanding and Editing through Agentic Collaboration](https://arxiv.org/abs/2611.14724)<br><sub>WPI / UT Dallas</sub> | LLM规划+工具协同做自然语言音频编辑，MMAE精确匹配22.6% | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Hy ASR 3.0 Technical Report](https://arxiv.org/abs/2611.14908)<br><sub>Tencent Hunyuan · Technical Report</sub> | 腾讯混元LLM式ASR，覆盖中英粤与方言。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [DeALR: Decoupled Audio-Latent Optimization with Acoustic Backtracking for Test-Time Reasoning](https://arxiv.org/abs/2611.15439)<br><sub>HKUST(GZ)</sub> | 测试时声学回溯+置信度策略梯度，让冻结LALM重访音频 | — | 推理范式 | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Text Grouping Changes Completion-Time Comparisons in Long-Form Simultaneous Speech Translation](https://arxiv.org/abs/2611.12501)<br><sub>VinUniversity</sub> | 同传里文本如何送入 TTS 会改变完成时差。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Walrus Technical Report](https://arxiv.org/abs/2611.13689)<br><sub>Sony · 技术报告</sub> | 索尼 8B 语音音频基座，靠数据课表追上更大的 Omni。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Beyond the Transcript: Measuring and Improving the Use of Acoustic Information in Audio Language Models](https://arxiv.org/abs/2611.11573)<br><sub>UConn / UT Austin / Oxford</sub> | 用录音增益测量并修补音频语言模型是否真在听。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [ReListen: Training-Free Evidence Localization in Hour-Long Audio with Frozen Audio Language Models](https://arxiv.org/abs/2611.04480)<br><sub>CUHK-Shenzhen / Microsoft</sub> | 冻结音频语言模型扫描小时级音频，自行定位答题证据。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [WaveGen: Truly End-to-End Waveform Generation via Internal Spectral Trajectory Learning](https://arxiv.org/abs/2611.12527)<br><sub>Ajou University · NeurIPS 2026</sub> | 内部频谱轨迹学习的端到端扩散波形 TTS。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Guidance at Pure Noise Erodes Speaker Similarity in Few-Step Token-Conditioned Flow-Matching TTS](https://arxiv.org/abs/2611.11179)<br><sub>KAIST · IEEE TASLP 投稿中</sub> | 少步流匹配 TTS 在纯噪声处做 CFG 会损音色。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [PodEval: A Multimodal Evaluation Framework for Long-form Podcast Generation](https://dl.acm.org/doi/abs/10.1145/3767308.3835931)<br><sub>ACM MM 2026</sub> | 开源播客长音频生成评测，拆分文本、语音与音频维度。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [AudioCodex: Streaming Autoencoders for Live Audio](https://arxiv.org/abs/2611.12375)<br><sub>ISMIR 2026</sub> | 面向直播的严格因果、约 10 Hz 连续音频编码。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Music Inpainting With Similarity-Guided Latent Diffusion](https://arxiv.org/abs/2611.11522)<br><sub>ISMIR 2026</sub> | 相似度检索引导扩散，修补音乐大段缺失。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [REAL: Reward Modeling through Evidence-Linked Analysis of Lifelikeness in Generated Speech](https://arxiv.org/abs/2611.12406) | 用时间戳证据链监督训练语音拟真奖励模型。 | — | — | — | 暂无 |

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
