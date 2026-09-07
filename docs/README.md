<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-07
- 运行时间：2026-09-07 23:37:10 UTC
- 运行状态：成功
- 本次总论文数：42
- 精读区：29
- 速读区：13

### 今日简报（AI）
今日精读29篇，速读13篇，两篇满分论文聚焦可扩展视频预训练与VLA高效在线强化学习。  
最值得关注的方向：ZimaBlue用视频预训练进化通用世界动作模型，VLA-Precision则通过非对称联合引导实现真实世界机器人高效在线学习。  
下一步建议普通读者优先追踪“视频预训练+世界模型”对具身智能泛化的推动，并留意跨具身物理仿真与人群导航规划的应用潜力。
- 详情：[/202609/07/README](/202609/07/README)

### 精读区论文标签
1. [ZimaBlue: Evolving Generalizable World Action Models through Scalable Video Pre-training](/202609/07/2609.00188v1-zimablue-evolving-generalizable-world-action-models-through-scalable-video-pre-training)  
   标签：评分：10.0/10、query:world-models
   evidence：直接提出世界动作模型并从大规模视频预训练获得泛化操控能力
2. [VLA-Precision: Asymmetric Co-Bootstrapping for Efficient Real-World Online RL of Vision-Language-Action Models](/202609/07/2609.04355v1-vla-precision-asymmetric-co-bootstrapping-for-efficient-real-world-online-rl-of-vision-language-action-models)  
   标签：评分：10.0/10、query:robot-rl
   evidence：针对VLA策略的真实机器人在线强化学习，提出非对称共同引导和流式架构来克服价值信号漂移与推理开销
3. [AGM: Achievement-Grounded Memory for Closed-Loop Agents with Frozen VLA Policies](/202609/07/2608.29537v1-agm-achievement-grounded-memory-for-closed-loop-agents-with-frozen-vla-policies)  
   标签：评分：9.0/10、query:vla-policy
   evidence：为冻结VLA策略加入成果验证式记忆，实现闭环进展判断
4. [DriftingVLA: Native One-Step Vision-Language-Action Generation via Per-Dimension Temporal Drifting](/202609/07/2608.29749v1-driftingvla-native-one-step-vision-language-action-generation-via-per-dimension-temporal-drifting)  
   标签：评分：9.0/10、query:vla-policy
   evidence：提出一种单步VLA生成方法，可在单次前向中输出完整动作块以支持在线机器人控制。
5. [SmoothRL: Online Reinforcement Learning During Asynchronous Execution](/202609/07/2608.29768v1-smoothrl-online-reinforcement-learning-during-asynchronous-execution)  
   标签：评分：9.0/10、query:robot-rl
   evidence：在异步执行期间用在线强化学习微调预训练的通用机器人策略，兼顾可靠性与实时性。
6. [SymVD: Symmetric Vision Language Action Distillation for Robot Manipulation](/202609/07/2608.29828v1-symvd-symmetric-vision-language-action-distillation-for-robot-manipulation)  
   标签：评分：9.0/10、query:vla-policy
   evidence：面向机器人操控的VLA蒸馏方法，利用对称性提升VLA策略的泛化
7. [Training-Free Action Correction for VLA Model Failures via Language Feedback](/202609/07/2608.29967v1-training-free-action-correction-for-vla-model-failures-via-language-feedback)  
   标签：评分：9.0/10、query:vla-policy
   evidence：CorrectVLA 将任务级语言纠正翻译为加性动作调整，无需重训即可修正 VLA 模型部署失败。
8. [Motus2: A Self-Evolving General World Model for Dexterous Manipulation](/202609/07/2608.30237v1-motus2-a-self-evolving-general-world-model-for-dexterous-manipulation)  
   标签：评分：9.0/10、query:world-models
   evidence：将策略、仿真器和价值模型统一为world-action模型以支持机器人控制
9. [CometVLA: Co-Training on an Embodied Data Pyramid towards Physical Understanding](/202609/07/2608.30289v1-cometvla-co-training-on-an-embodied-data-pyramid-towards-physical-understanding)  
   标签：评分：9.0/10、query:vla-policy
   evidence：直接以机器人操控为目标改进VLA模型的物理理解能力
10. [PAVE: Predictive Alignment and Value-Guided Evolution for World-Action Policies](/202609/07/2608.30378v1-pave-predictive-alignment-and-value-guided-evolution-for-world-action-policies)  
   标签：评分：9.0/10、query:world-models
   evidence：提出一种直接世界动作策略，将多时间跨度预测对齐与价值引导提升引入视觉语言动作模型。
11. [PAVE: Predictive Alignment and Value-Guided Evolution for World-Action Policies](/202609/07/2608.30378v2-pave-predictive-alignment-and-value-guided-evolution-for-world-action-policies)  
   标签：评分：9.0/10、query:world-models
   evidence：面向世界-动作策略的预测对齐与价值引导进化，直接结合状态预测和动作策略
12. [Non-Prehensile Throwing: A Reinforcement Learning Perspective](/202609/07/2609.00771v1-non-prehensile-throwing-a-reinforcement-learning-perspective)  
   标签：评分：9.0/10、query:robot-rl
   evidence：用深度强化学习直接优化关节空间轨迹实现非抓取投掷，属于机器人操作。
13. [Knowing When to Stop: Adaptive Action Chunking via Internal Cross-Attention Dynamics in VLAs](/202609/07/2609.00908v2-knowing-when-to-stop-adaptive-action-chunking-via-internal-cross-attention-dynamics-in-vlas)  
   标签：评分：9.0/10、query:vla-policy
   evidence：基于VLA内部交叉注意力熵提出自适应动作分块，优化机器人动作执行
14. [REFACTOR-VLA: Unsupervised Library Learning of Typed Motor Programs](/202609/07/2609.01215v1-refactor-vla-unsupervised-library-learning-of-typed-motor-programs)  
   标签：评分：9.0/10、query:vla-policy
   evidence：面向VLA模型，利用潜世界模型滚动推出行为等价核，学习可复用类型化动作程序
15. [EmbodiedSkills: A Unified Framework for Orchestrating, Training, and Deploying VLA Agents](/202609/07/2609.01281v1-embodiedskills-a-unified-framework-for-orchestrating-training-and-deploying-vla-agents)  
   标签：评分：9.0/10、query:vla-policy
   evidence：面向长程机器人任务，统一编排、训练和部署VLA智能体的框架，强调执行前提检查与结果验证。
16. [Evaluating Multimodal LLMs as Generalist Vision-Language-Action Agents for Drone Control: Commanding, Approaching, Tracking and Searching](/202609/07/2609.01404v1-evaluating-multimodal-llms-as-generalist-vision-language-action-agents-for-drone-control-commanding-approaching-tracking-and-searching)  
   标签：评分：9.0/10、query:vla-policy
   evidence：将多模态大语言模型直接放入无人机控制回路作为通用VLA智能体。
17. [Facet-0: A Robotic Foundation Model for Contact-Rich Precise Manipulation](/202609/07/2609.01596v1-facet-0-a-robotic-foundation-model-for-contact-rich-precise-manipulation)  
   标签：评分：9.0/10、query:vla-policy
   evidence：Facet-0 面向接触丰富精密操作，统一视觉语言语义、力/力矩历史与强化学习后训练，构成机器人基础模型。
18. [One Demonstration, Many Objects: Generalizing Manipulation via Local Contact Geometry](/202609/07/2609.01938v1-one-demonstration-many-objects-generalizing-manipulation-via-local-contact-geometry)  
   标签：评分：9.0/10、query:robot-rl
   evidence：使用接触中心奖励的仿真到现实强化学习实现灵巧操作，增强对新物体和真实世界的泛化
19. [One Demonstration, Many Objects: Generalizing Manipulation via Local Contact Geometry](/202609/07/2609.01938v2-one-demonstration-many-objects-generalizing-manipulation-via-local-contact-geometry)  
   标签：评分：9.0/10、query:robot-rl
   evidence：面向灵巧操作的含接触奖励的示范强化学习方法
20. [World-Coherent Decoding: Self-Verifying Test-Time Planning for World Action Models](/202609/07/2609.02159v1-world-coherent-decoding-self-verifying-test-time-planning-for-world-action-models)  
   标签：评分：9.0/10、query:world-models
   evidence：针对WAM随机生成视觉未来后解码动作的样本敏感性，提出自验证测试时规划，用视频惊奇度和动作代价选择可信未来
21. [Spatially Aware World Action Model via Geometric Latent Diffusion](/202609/07/2609.02531v1-spatially-aware-world-action-model-via-geometric-latent-diffusion)  
   标签：评分：9.0/10、query:world-models
   evidence：提出在预训练视频扩散模型上联合预测动作、RGB与深度的空间感知世界动作模型
22. [HINT: Human-Intent Inception for Long-Horizon Robot Manipulation](/202609/07/2609.02653v1-hint-human-intent-inception-for-long-horizon-robot-manipulation)  
   标签：评分：9.0/10、query:vla-policy
   evidence：在语言引导的长时程操作中，用稀疏的人类语义意图约束VLA策略，避免视觉相关性覆盖真实目标
23. [Scaling Bimanual Household Manipulation from 1,500 hours of Demonstrations to On-Policy Corrections](/202609/07/2609.03591v1-scaling-bimanual-household-manipulation-from-1500-hours-of-demonstrations-to-on-policy-corrections)  
   标签：评分：9.0/10、query:vla-policy
   evidence：利用1500小时示范数据和策略内校正训练通用双手操作VLA策略的规模化研究
24. [WISE: World-model-guided Imagination Scheduling for Efficient Post-training of Vision-Language-Action Models](/202609/07/2609.03681v1-wise-world-model-guided-imagination-scheduling-for-efficient-post-training-of-vision-language-action-models)  
   标签：评分：9.0/10、query:vla-policy
   evidence：利用世界模型引导的想象调度高效后训练VLA模型
25. [MINERVA: How Small Can a Manipulation Policy Be and Still Solve LIBERO?](/202609/07/2609.03715v1-minerva-how-small-can-a-manipulation-policy-be-and-still-solve-libero)  
   标签：评分：9.0/10、query:vla-policy
   evidence：研究在LIBERO上解决操作任务所需VLA容量下限，并构建紧凑的机器人视觉-动作策略族。
26. [FWBC-VLA: Force-Aware Whole-Body Compensation for Contact-Rich Loco-Manipulation](/202609/07/2609.03889v2-fwbc-vla-force-aware-whole-body-compensation-for-contact-rich-loco-manipulation)  
   标签：评分：9.0/10、query:vla-policy
   evidence：面向接触密集的移动操纵，将VLA与力感知全身补偿结合
27. [Reasoning Without Inference Cost: Latent Semantic Scaffolding for Robot VLA Policies](/202609/07/2609.04893v1-reasoning-without-inference-cost-latent-semantic-scaffolding-for-robot-vla-policies)  
   标签：评分：9.0/10、query:vla-policy
   evidence：通过训练期对齐物理推理语义嵌入来增强机器人VLA策略，且不增加部署时推理开销
28. [TacPAC: Tactile Prediction and Real-Time Action Correction in World-Action Models for Contact-Rich Manipulation](/202609/07/2609.05266v1-tacpac-tactile-prediction-and-real-time-action-correction-in-world-action-models-for-contact-rich-manipulation)  
   标签：评分：9.0/10、query:world-models
   evidence：面向接触丰富操作，在世界动作模型中加入触觉预测和实时动作修正
29. [Towards Neuro-Symbolic Procedural Reasoning for Long-Horizon Vision-Language-Action Manipulation](/202609/07/2609.05369v1-towards-neuro-symbolic-procedural-reasoning-for-long-horizon-vision-language-action-manipulation)  
   标签：评分：9.0/10、query:vla-policy
   evidence：将VLA控制与显式任务图和多模态过程记忆结合的神经符号框架，面向长时程操作

### 速读区论文标签
1. [Diffusion Policies for Short-Horizon Planning in Robot Crowd Navigation](/202609/07/2608.27158v1-diffusion-policies-for-short-horizon-planning-in-robot-crowd-navigation)  
   标签：评分：8.0/10、query:robot-rl
   evidence：面向实际机器人人群导航的离线到在线强化学习扩散策略
2. [CLAP: Cross-Embodiment Video World Models are Zero-Shot Physical Simulators](/202609/07/2608.27406v1-clap-cross-embodiment-video-world-models-are-zero-shot-physical-simulators)  
   标签：评分：8.0/10、query:world-models
   evidence：跨具身动作条件视频世界模型，可作零样本物理模拟器用于机器人控制
3. [Contact-Guided Exploration for Non-Prehensile Locomanipulation with Multi-Critic RL](/202609/07/2608.28140v1-contact-guided-exploration-for-non-prehensile-locomanipulation-with-multi-critic-rl)  
   标签：评分：8.0/10、query:robot-rl
   evidence：用于非抓取移动操作的多评判器强化学习与接触引导探索
4. [AcrossVAM1.0: Particle World Modeling for Text-Assisted Robot Video Prediction](/202609/07/2608.28491v1-acrossvam10-particle-world-modeling-for-text-assisted-robot-video-prediction)  
   标签：评分：8.0/10、query:world-models
   evidence：基于粒子世界模型的文本辅助机器人视频预测
5. [$\mathcal{N}_0$-Foundation: Towards the Age of Tactile Intelligence](/202609/07/2608.29601v1-mathcaln0-foundation-towards-the-age-of-tactile-intelligence)  
   标签：评分：8.0/10、query:vla-policy
   evidence：面向机器人操作的触觉基础模型，覆盖多实体多任务与大规模数据
6. [Three Steps at a Time: Learning Representations from Action Sequences in Contrastive RL](/202609/07/2608.30640v1-three-steps-at-a-time-learning-representations-from-action-sequences-in-contrastive-rl)  
   标签：评分：7.0/10、query:world-models
   evidence：在对比RL中用动作块而非单步动作学习状态-动作表征，可迁移到机器人动作表示学习
7. [Autonomously Acquiring Robot Manipulation Skills with Language-Driven Quality-Diversity](/202609/07/2608.30983v1-autonomously-acquiring-robot-manipulation-skills-with-language-driven-quality-diversity)  
   标签：评分：7.0/10、query:vla-policy
   evidence：使用语言驱动的质量-多样性算法与LLM奖励塑形，仅凭自由文本任务描述自动获取机器人操作技能
8. [SUN: Persistent Programs For Language-Grounded Control-to-Learning-to-Real Policies](/202609/07/2608.31167v1-sun-persistent-programs-for-language-grounded-control-to-learning-to-real-policies)  
   标签：评分：7.0/10、query:vla-policy
   evidence：用语言和场景合成统一语义程序，连接MPC、RL奖励与操控状态转移，实现语言条件下的长程操作
9. [Selective Agent Guidance via Entropy: Learning Autonomous Policies from Imperfect VLM Teachers](/202609/07/2609.01567v1-selective-agent-guidance-via-entropy-learning-autonomous-policies-from-imperfect-vlm-teachers)  
   标签：评分：7.0/10、query:vla-policy
   evidence：将VLM教师指导在不确定性驱动下蒸馏为轻量强化学习自主策略
10. [Uncertainty-Driven Replay Memory for Reinforcement Learning](/202609/07/2608.29860v1-uncertainty-driven-replay-memory-for-reinforcement-learning)  
   标签：评分：6.0/10、query:robot-rl
   evidence：提出不确定性驱动的经验重放记忆以提升RL样本效率，可迁移到机器人RL。
11. [Recursive Value Learning for Long-Horizon Offline Goal-Conditioned RL](/202609/07/2609.02237v1-recursive-value-learning-for-long-horizon-offline-goal-conditioned-rl)  
   标签：评分：6.0/10、query:robot-rl
   evidence：面向长视距任务的通用离线目标条件RL算法，可迁移到机器人操作策略学习
12. [R2S-Eval: Robot Evaluation with Real-to-Sim Calibration via Vision-Language Models](/202609/07/2609.03276v1-r2s-eval-robot-evaluation-with-real-to-sim-calibration-via-vision-language-models)  
   标签：评分：6.0/10、query:vla-policy
   evidence：使用视觉语言模型对通用VLA机器人策略进行真实到仿真校准的评测框架
13. [Multi-step Proximal Policy Improvement in Offline Reinforcement Learning](/202609/07/2609.03842v1-multi-step-proximal-policy-improvement-in-offline-reinforcement-learning)  
   标签：评分：6.0/10、query:robot-rl
   evidence：提出离线RL多步近端策略改进的通用机制，可用于机器人策略微调与RL-for-VLA下的策略优化


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
