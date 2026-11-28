# 第 5 板块 · 第一人称与全景理解

*Egocentric & Panoramic Understanding*

> 严格只收理解：第一人称（可穿戴/AI 眼镜）与 360° 全景视频的时空理解、问答、流式记忆、场景与三维几何感知

共 6 篇 A、60 篇 B；由 `export_markdown.py` 每次运行从 `runs/issues.json` 重建，请勿手改。

## A 类（6）

- **2026-11-23** · [RoboCap-10k: A Metrically Accurate Egocentric Dataset for Robot Learning](https://arxiv.org/abs/2611.26916) · [第 7 期卡片](../issues/2026-11-23.md#a-2611.26916)
  - 约一万小时单设备职业第一人称视频，含度量头手三维标注。
  - Dataset · 仅主页 · Grounded Superintelligence / BitRobot
  - 技术关键词：visual-inertial SLAM · 6-DoF · egocentric
- **2026-11-21** · [HumanCOIN: A 12,500-Hour Dataset for Human Intent in Egocentric Manipulation](https://arxiv.org/abs/2611.26434) · [第 6 期卡片](../issues/2026-11-21.md#a-2611.26434)
  - 1.25万小时自我中心操作数据，分层记录注视、肌电与脑电。
  - Dataset · 仅主页 · BAAI
  - 技术关键词：surface EMG · scalp EEG · gaze
- **2026-11-21** · [EgoWitness: Benchmarking Instance-Level Spatial Memory and Reasoning in Egocentric Video Streams](https://arxiv.org/abs/2611.25849) · [第 6 期卡片](../issues/2026-11-21.md#a-2611.25849)
  - 跨天跨人的实例级空间记忆基准与检索智能体。
  - Benchmark / Method · 仅主页 · HKUST / Tsinghua University
  - 技术关键词：GRPO · SFT · EgoClue
- **2026-11-19** · [Evolve in Panorama, Render in View: Panoramic World State Evolution for Video World Models](https://arxiv.org/abs/2611.22733) · [第 5 期卡片](../issues/2026-11-19.md#a-2611.22733)
  - 全景隐空间持续演化世界，再按视角渲染透视视频
  - Method / Dataset · 暂无 · MBZUAI / Kuaishou
  - 技术关键词：Panoramic Evolver · Perspective Renderer · cross-attention
- **2026-11-17** · [HubEgo-100K: In-the-Wild Egocentric Video of Skilled Work for Robot Learning](https://arxiv.org/abs/2611.21938) · [第 4 期卡片](../issues/2026-11-17.md#a-2611.21938)
  - 开源1万小时野外职业劳动第一人称视频与同步IMU
  - Dataset · 数据已开源 · Hub Labs (Hub Data, Inc.)
  - 技术关键词：egocentric · IMU · imitation
- **2026-11-11** · [RoboMoCap: A Large-Scale Whole-Body Motion Capture Dataset with Egocentric Vision for Robot Learning](https://arxiv.org/abs/2611.10994) · [第 1 期卡片](../issues/2026-11-11.md#a-2611.10994)
  - 光学动捕对齐头戴多相机，做人形全身运动与落脚评测。
  - Dataset · 仅主页
  - 技术关键词：motion capture · egocentric · loco-manipulation

## B 类（60）

| 日期 | 标题 | 核心改动 | 类型 | 方法族 | 副板块 | 代码/数据 |
| --- | --- | --- | --- | --- | --- | --- |
| [2026-11-28](../issues/2026-11-28.md) | [Who Is Ego? Scaling Cross-View Camera Wearer Identification and Segmentation beyond Humans](https://arxiv.org/abs/2611.34489)<br><sub>Central South University / Fudan University / KAUST</sub> | 用极点几何把冻结三维重建转成佩戴者识别与分割。 | Dataset / Method | 数据与评测 | — | 暂无 |
| [2026-11-28](../issues/2026-11-28.md) | [AIRIS: Benchmarking Social Embodied Intelligence in Egocentric Streaming Videos](https://arxiv.org/abs/2611.34347)<br><sub>Tencent Robotics X Lab · ICLR 2027 Conference Withdrawn Submission</sub> | 用因果前缀评第一人称社交决策的A-I-R-I链。 | Benchmark | 数据与评测 | — | [代码已开源](https://github.com/AIRIS-bench/AIRIS) |
| [2026-11-28](../issues/2026-11-28.md) | [EgoCARBS: Egocentric Video Meets Active Acoustics for Kitchen Action Understanding](https://arxiv.org/abs/2611.33565)<br><sub>Cornell University / Amazon</sub> | 用眼镜和手表的超声回波补第一人称出画手部 | Dataset / Benchmark | 数据与评测 | — | [仅主页](https://saif-mahmud.github.io/projects/ego-carbs/) |
| [2026-11-25](../issues/2026-11-25.md) | [Speak When You See It: Proactive Task Assistants Should Wait for Evidence, Not the Clock](https://arxiv.org/abs/2611.30895)<br><sub>Beijing University of Posts and Telecommunications/Queen Mary University of London</sub> | 同时刻正负配对微调，迫使助手凭画面而非时钟开口 | Method | 数据与评测 | 全双工与实时交互 | 暂无 |
| [2026-11-25](../issues/2026-11-25.md) | [Clinical3D-Bench: Evaluating and Improving Spatial Intelligence of Multimodal LLMs in Hospital Environments](https://arxiv.org/abs/2611.32094)<br><sub>University of Science and Technology of China / IAIC, A*STAR / Wenzhou Medical University</sub> | 建医院第一人称空间问答基准，用三维原语修正选项分 | Benchmark / Method | 推理范式 / 数据与评测 | — | [数据已开源](https://huggingface.co/datasets/clinicalspace/Clinical3D-Bench) |
| [2026-11-25](../issues/2026-11-25.md) | [OmniV-Bench: Can MLLMs Comprehend Immersive Spatio-temporal Scenes?](https://arxiv.org/abs/2611.31022)<br><sub>Shanghai Jiao Tong University / Beijing University of Technology / Tsinghua University</sub> | 提出全向视频十一任务基准，并用六面视角取证提升问答 | Benchmark / 智能体/工具调用 | 数据与评测 | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [EgoSurgHands: An Egocentric 3D Hand Pose Dataset & Benchmark for Open Surgery Training](https://arxiv.org/abs/2611.27101)<br><sub>Harvard Medical School / Beth Israel Deaconess Medical Center · NeurIPS 2026 Evaluations and Datasets Track</sub> | 发布开放手术训练中真实第一人称三维手部姿态数据集与基准。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [EgoLAM: Learning Latent Actions from Hand and Head Motion](https://arxiv.org/abs/2611.27290)<br><sub>Tsinghua University / Tongji University</sub> | 用腕部运动监督潜在动作，把头动交给前向模型以剥离相机运动。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [Ego2Ego: Generative Visual Perspective Taking Across Collaborators](https://arxiv.org/abs/2611.27459)<br><sub>University of Stuttgart / Toyota Research Institute</sub> | 由己方第一人称视频生成协作者连续第一人称视角。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [TouchBench: Can Vision-Language Models Feel Invisible Physical Properties?](https://arxiv.org/abs/2611.26883)<br><sub>Meta Reality Labs</sub> | 第一人称视触基准显示VLM对镜头不可见物理属性近随机。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [VMSA: Video Memory Skill Agent for Long Video Understanding](https://arxiv.org/abs/2611.27381)<br><sub>Seoul National University</sub> | 用结构化视频记忆与记忆技能做长视频问答，周级第一人称基准领先。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [TacHOI: Contact-Aware Object Reconstruction and Tracking for Egocentric Videos](https://arxiv.org/abs/2611.26764) | 用触觉接触约束，从单目第一人称视频无训练重建手物度量几何。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [Ego4Gen: Generating Geometry-Grounded Motion Tokens as a World-Action Interface](https://arxiv.org/abs/2611.27513) | 从单张第一人称图联合生成未来RGB、点图与场景流并映射为动作。 | — | — | — | 暂无 |
| [2026-11-23](../issues/2026-11-23.md) | [PanoUAV-Track: Full-Spherical UAV Visual Tracking in the Wild](https://arxiv.org/abs/2611.27383)<br><sub>TeleAI, China Telecom</sub> | 机载全向跟踪基准，针对ERP畸变与接缝 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [StreamEgo: Streaming Exocentric-to-Egocentric Video Generation](https://arxiv.org/abs/2611.26165)<br><sub>Peking University</sub> | 流式第三人称转第一人称视频生成，单卡24.3FPS。 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [ACE-Brain-0.7: Learning Execution-Grounded Reasoning for Embodied Agents](https://arxiv.org/abs/2611.26519) | 3.7M执行态问答微调9B模型，做具身进度推理。 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [EgoCaptioner: Towards Comprehensive and Fine-Grained Egocentric Video Captioning](https://arxiv.org/abs/2611.26380)<br><sub>KlingAI Research</sub> | 粗到细标注与GRPO训练细粒度第一人称视频描述。 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [Online Mistake Detection in Instruction-Conditioned Procedural Video](https://arxiv.org/abs/2611.25567)<br><sub>University of Haifa</sub> | 在线结合指令检测第一人称流程视频中的失误。 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [Better Retrieval, Not Better Binding: Pretraining Exposure in Egocentric Video Retrieval](https://arxiv.org/abs/2611.26120)<br><sub>University of Bristol</sub> | 诊断表明自我中心检索提升来自曝光而非动宾绑定。 | — | — | — | 暂无 |
| [2026-11-21](../issues/2026-11-21.md) | [SkillLens: Action-Guided Dense Visual Dynamics for Proficiency Estimation](https://arxiv.org/abs/2611.25712)<br><sub>KIST · CVPR Workshop 2026</sub> | 用动作窗口与原型间隔估计第一人称熟练度。 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [HandWorldBench: A Unified Benchmark for Hand-Centric World Models](https://arxiv.org/abs/2611.24731)<br><sub>Tsinghua University</sub> | 跨人/仿/真灵巧手的手中心世界模型基准 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [EgoPass-Bench: Identifying Objects That May Affect the Wearer's Passage in Egocentric Video](https://arxiv.org/abs/2611.24995)<br><sub>ICLR 2027 Withdrawn</sub> | 评测眼镜视频中影响通行的观察者相对交互 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [EgoJev: Finding Evidence in Egocentric Video by Reading VLM Decisions](https://arxiv.org/abs/2611.24616)<br><sub>Harvard University</sub> | 无训练读取VLM标签分布做ego视频抽帧 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [TOMAS: Topology-Aware Operation Modeling and Adaptive Staging for Egocentric Hand Forecasting](https://arxiv.org/abs/2611.23970)<br><sub>Shanghai Jiao Tong University</sub> | 用操作拓扑与自适应阶段预测ego手部轨迹 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [WM^MLLM: Turning MLLMs into World Models](https://arxiv.org/abs/2611.24193) | 以外置全景状态让MLLM编排可持久、可局部编辑的世界 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [GameRealm: Grounding Visual Learning in Interactive Games](https://arxiv.org/abs/2611.23140) | 1.2亿帧游戏多视图数据，含全景与几何真值 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [CoSphere-SLAM: Multi-Agent Panoramic Gaussian Splatting SLAM with Spherical Loop Closure](https://arxiv.org/abs/2611.22235)<br><sub>Harbin Engineering University / University of Liverpool</sub> | 多智能体全景高斯SLAM，球面回环并校正尺度漂移 | — | — | — | 暂无 |
| [2026-11-19](../issues/2026-11-19.md) | [Zero to Four Views: Unified Panorama Generation and Preference RL for Unobserved Regions](https://arxiv.org/abs/2611.25389)<br><sub>George Mason University</sub> | 统一0–4视角全景生成，并用GRPO修补未覆盖区域 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [WinDEX: Metric 3D Hand Motion Reconstruction in the Wild for Dexterous Teleoperation and Policy Learning](https://arxiv.org/abs/2611.21143)<br><sub>City University of Hong Kong</sub> | 野外鱼眼立体度量手部重建并用于遥操作与策略学习 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [EgoSwarm: Learning Decentralized Robot Swarm Intelligence from Human Swarm Demonstrations](https://arxiv.org/abs/2611.20100)<br><sub>Huazhong University of Science and Technology · HumanRLI 2026</sub> | 从多人第一人称示范学习去中心化机器人群协作 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [HandRSI: Recursive Self-Improvement for Hand Pose Estimation](https://arxiv.org/abs/2611.22164)<br><sub>Technical report</sub> | 编码智能体循环改手姿推理套件并蒸馏回估计器 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [EgoLink: Egocentric Language-Vision Interactive Network Knowledge Challenge Summary](https://arxiv.org/abs/2611.21690)<br><sub>Ant Group / Zhejiang University · ACM Multimedia 2026</sub> | ACM MM第一人称社交推理与交互智能体挑战综述 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [MetricHand: Geometry-Aware Flow Matching for 4D Hand Reconstruction in Metric World Space](https://arxiv.org/abs/2611.21060)<br><sub>National University of Defense Technology · ICLR 2027 submission</sub> | 几何条件流匹配实现度量世界系四维手部重建 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Ego2Sim2Humanoid: Agentic Real-to-Sim for Learning Loco-Manipulation VLAs without Robot Demonstrations](https://arxiv.org/abs/2611.19196)<br><sub>University of Notre Dame</sub> | 眼镜记录转仿真轨迹，无真机示范微调人形VLA | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Is It Still There? Place-Registered Verification Makes VLMs Reliable Scene-Change Detectors](https://arxiv.org/abs/2611.18734)<br><sub>Loughborough University</sub> | 将场景变化检测改写为配准位置上的物体仍在与否 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [Probing Where Surprise Happens: Localized Violation-of-Expectation Evaluation of Video World Models](https://arxiv.org/abs/2611.18979)<br><sub>University of Miami · NeurIPS 2026 BabyVLM Workshop</sub> | 在违规发生的时空局部检验视频世界模型的预期违背 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [DEFDVO: Deformable Deep Visual Odometry for Equirectangular Images](https://arxiv.org/abs/2611.19095)<br><sub>WACV 2027</sub> | 在ERP上做可变形特征与接缝感知的360视觉里程计，WACV录用。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [PanDWM: Panoramic 4D Driving World Models](https://arxiv.org/abs/2611.19857)<br><sub>Peking University / Shenzhen University</sub> | 把六路环视拼成360全景带做驾驶世界模型，并蒸馏加速。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [HIVE-ECIA: Identity-Aware Historical Evidence Acquisition for Bandwidth-Efficient Multi-Object Tracking](https://arxiv.org/abs/2611.19897)<br><sub>Ruhr-Universität Bochum</sub> | 全景MOT按需回取历史高清以省带宽，并发布DualPano-MOT。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [sqrtVINS-Based 360 Visual-Inertial SLAM Systems: Hilti-Trimble SLAM Challenge 2026 Entry](https://arxiv.org/abs/2611.20568)<br><sub>Hilti-Trimble SLAM Challenge (ICRA 2026)</sub> | Hilti挑战赛第二名的360双鱼眼视觉惯性SLAM系统报告。 | — | — | — | 暂无 |
| [2026-11-17](../issues/2026-11-17.md) | [How Much Does Saliency Accuracy Matter for Saliency-Guided 360-degree Image Compression?](https://arxiv.org/abs/2611.21532)<br><sub>DRIVE Lab / CNRS-AIST JRL · IEEE/SICE SII 2027</sub> | 量化360显著图精度对压缩增益的边际收益，轻量模型已够用。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [SALA: Semantically Aligned Latent Actions Enable Dual-Axis Scaling of Embodied Foundation Models](https://arxiv.org/abs/2611.17110)<br><sub>SJTU-Sharpa / Tsinghua</sub> | 用语言语义对齐人机潜在动作，让自我中心视频监督机器人。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Ropedia Xperience 2: A Gold Standard for Scaling Physical AI Environments and Behaviors](https://arxiv.org/abs/2611.17060) | 度量三维扫描配自我中心行为，宣称物理AI环境-行为金标准。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [HEIR: Harness Egocentric Intent for Human-Robot Interactions](https://arxiv.org/abs/2611.17238)<br><sub>Tsinghua / BAAI</sub> | 配对注视、语音与自我中心视频及机器人轨迹的家居HRI数据。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [PhysCapBench: A Cross-Domain Benchmark for Physically Grounded Video Captioning](https://arxiv.org/abs/2611.16424) | 跨第三人称、自我中心与夹爪的物理视频字幕评测基准。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Can an LVLM Perceive Event Boundaries Like a Human?](https://arxiv.org/abs/2611.16452)<br><sub>Qualcomm AI Research</sub> | LVLM精炼小时级自我中心事件边界，并发布EgoBoundary。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [EgoX: Egocentric Cross-Embodiment Manipulation with Embodiment Dreaming](https://arxiv.org/abs/2611.16728)<br><sub>CMU / Bosch / NVIDIA · IROS 2026 Bimanual Manipulation Workshop</sub> | 自我中心统一观察动作，跨本体预训练操作策略。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Topology-Aware 4D Gaussian Splatting for Egocentric Videos](https://arxiv.org/abs/2611.16012)<br><sub>Bocconi / TUM / Google</sub> | 针对切割开合等拓扑变化的自我中心4D高斯重建。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Sub-actions in Action: Text-Guided Hand-Role Alignment for Sub-Action Recognition](https://arxiv.org/abs/2611.16056)<br><sub>University of Surrey · BMVC 2026</sub> | 文本引导对齐左右手角色，识别自我中心子动作。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [EG360: Efficient and Generalizable $360^\circ$ Depth Estimation via Adaptive Panorama-Perspective Distillation and Spherical Cross-Level Feature Fusion](https://arxiv.org/abs/2611.16793)<br><sub>CUHKSZ, Tongji University</sub> | 轻量全景深度：几何自适应双教师蒸馏，Jetson上35FPS。 | — | — | — | 暂无 |
| [2026-11-13](../issues/2026-11-13.md) | [Spatial Foundry: A Multimodal Dataset for Spatial Intelligence](https://arxiv.org/abs/2611.17318) | 5280套可编辑住宅场景，对齐平面图、全景RGB与几何。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [SWAM: Scaling World Action Models with Cross-Modal Alignment](https://arxiv.org/abs/2611.12870) | 在 4.7 万小时混合数据上研究世界动作模型的跨模态对齐配方。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [UTOPI: Efficient Egocentric Long-Video Understanding in AR via User-Guided Token Pre-Compression](https://arxiv.org/abs/2611.11562)<br><sub>NeurIPS 2026</sub> | 用 AR 头动与眼动对第一人称长视频做最高 95% 的 token 压缩。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Hand-Object Contact Transition Detection in Egocentric Video](https://arxiv.org/abs/2611.13486)<br><sub>ACCV 2026</sub> | 检测第一人称视频中手-物接触的触达与松开边界。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [From Egocentric Human Video to Robot Manipulation in the Era of Embodied Intelligence](https://arxiv.org/abs/2611.13610)<br><sub>Hong Kong Polytechnic University</sub> | 综述从第一人称人类视频学习机器人操作的四种范式。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [EgoHMP: Achieving Precise Human Motion Prediction in 3D Scenes via Egocentric Cues](https://arxiv.org/abs/2611.13654)<br><sub>NeurIPS 2026</sub> | 用第一人称画面与头部运动替代注视，预测场景中的人体运动。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Ego Guidance: Enhancing Robot Policy Learning with Action-Free Human Egocentric Videos](https://arxiv.org/abs/2611.13685)<br><sub>Ant Group / Peking University</sub> | 无动作标签的第一人称视频经未来表征预测，提升机器人策略泛化。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [EgoLink: Egocentric Language-Vision Interactive Network Knowledge Challenge Summary](https://dl.acm.org/doi/abs/10.1145/3767308.3837706)<br><sub>ACM MM 2026</sub> | ACM MM 2026 第一人称社交推理与交互智能体挑战赛综述。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Disentangling Where and When: Factored Spatio-Temporal Explanations for Video Action Recognition](https://arxiv.org/abs/2611.11214)<br><sub>Oregon State University · NeurIPS 2026</sub> | 把视频动作解释拆成空间外观与时间运动掩膜并分别评测。 | — | — | — | 暂无 |
| [2026-11-11](../issues/2026-11-11.md) | [Scale-Consistent Monocular Fisheye Visual Odometry via Spherical Bundle Adjustment-Guided Unsupervised Depth Learning](https://arxiv.org/abs/2611.11934)<br><sub>Tongji University</sub> | 球面 BA 引导无监督深度，改善单目鱼眼视觉里程计的尺度一致性。 | — | — | — | 暂无 |

---

[返回目录](../README.md) · [跨期精华](../highlights.md)
