<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-08
- 运行时间：2026-09-08 22:24:37 UTC
- 运行状态：成功
- 本次总论文数：21
- 精读区：8
- 速读区：13

### 今日简报（AI）
今日精读21篇论文，其中8篇精读、13篇速读，核心聚焦VLA（视觉-语言-动作）模型改进。最值得关注的是两篇9分精读：通过内部交叉注意力动力学实现自适应动作分块，以及用证据门控正则化增强VLA策略的鲁棒性。建议优先从这两篇VLA方法入手，结合速读中的Zeva、LightNav-0和IMPACT，可系统掌握具身智能的最新进展。
- 详情：[/202609/08/README](/202609/08/README)

### 精读区论文标签
1. [Knowing When to Stop: Adaptive Action Chunking via Internal Cross-Attention Dynamics in VLAs](/202609/08/2609.00908v1-knowing-when-to-stop-adaptive-action-chunking-via-internal-cross-attention-dynamics-in-vlas)  
   标签：评分：9.0/10、query:vla-policy
   evidence：针对VLA框架提出基于内部交叉注意力熵的自适应动作分块方法
2. [Sensing Which Modality Matters: Evidence-Gated Regularization for Robust VLA Policies](/202609/08/2609.03142v1-sensing-which-modality-matters-evidence-gated-regularization-for-robust-vla-policies)  
   标签：评分：9.0/10、query:vla-policy
   evidence：提出证据门控正则化，提升VLA策略在模态纠缠、传感器缺失或干扰下的鲁棒性
3. [Toward Physically Grounded JEPA World Models for Goal-Conditioned Robotic Planning](/202609/08/2609.03565v1-toward-physically-grounded-jepa-world-models-for-goal-conditioned-robotic-planning)  
   标签：评分：9.0/10、query:world-models
   evidence：提出动作条件下的 JEPA 世界模型，结合逆动力学与状态对齐用于目标条件机器人规划。
4. [FWBC-VLA: Force-Aware Whole-Body Compensation for Contact-Rich Loco-Manipulation](/202609/08/2609.03889v1-fwbc-vla-force-aware-whole-body-compensation-for-contact-rich-loco-manipulation)  
   标签：评分：9.0/10、query:vla-policy
   evidence：将力感知与全身控制引入 VLA 策略，以处理富含接触的移动操作任务。
5. [RoboSPA: Can VLA Models Go Beyond Simple Scenes and Short-Horizon Tasks?](/202609/08/2609.05324v1-robospa-can-vla-models-go-beyond-simple-scenes-and-short-horizon-tasks)  
   标签：评分：9.0/10、query:vla-policy
   evidence：构建面向VLA模型语言条件操作的大型基准，评估空间与程序复杂度下的具身推理
6. [AcrossWAM1.0:A Modular Latent World-Action Stack for Compact Robot Policies](/202609/08/2608.29937v1-acrosswam10a-modular-latent-world-action-stack-for-compact-robot-policies)  
   标签：评分：8.0/10、query:world-models
   evidence：将潜在世界-动作栈模块化为策略适配器、潜在世界解码器和流匹配动作专家，支撑紧凑机器人策略
7. [Behavior-Skill: A Fine-Grained Benchmark for Evaluating Vision-Language-Action Policies in Long-Horizon Tasks](/202609/08/2608.30536v1-behavior-skill-a-fine-grained-benchmark-for-evaluating-vision-language-action-policies-in-long-horizon-tasks)  
   标签：评分：8.0/10、query:vla-policy
   evidence：提供50个家庭任务、34类语义技能的23万余个技能实例，把VLA策略跨任务评估从整任务分解为技能粒度
8. [Continuous Actions from Discrete Minds: Latent-Aligned Planning for End-to-End Autonomous Driving](/202609/08/2609.04070v1-continuous-actions-from-discrete-minds-latent-aligned-planning-for-end-to-end-autonomous-driving)  
   标签：评分：8.0/10、query:world-models
   evidence：用VQ-VAE动作分词器将轨迹表示为结构化潜在动作空间，属于自动驾驶VLA中的潜在动作建模

### 速读区论文标签
1. [Zeva: In-Context Causal Learning for Generalizable Embodied Manipulation](/202609/08/2608.30880v1-zeva-in-context-causal-learning-for-generalizable-embodied-manipulation)  
   标签：评分：8.0/10、query:vla-policy
   evidence：Zeva面向泛化具身操作，在冻结策略下利用机器人自身物理交互经验做上下文因果学习
2. [LightNav-0: Eliciting VLM Spatial Intelligence for Generalist Embodied Navigation](/202609/08/2608.30935v1-lightnav-0-eliciting-vlm-spatial-intelligence-for-generalist-embodied-navigation)  
   标签：评分：8.0/10、query:vla-policy
   evidence：激发预训练VLM空间智能并与跨任务跨本体的导航动作对齐
3. [IMPACT: Attention Is the Interaction Map for Scalable Interaction-Aware World Model Training](/202609/08/2609.00161v1-impact-attention-is-the-interaction-map-for-scalable-interaction-aware-world-model-training)  
   标签：评分：8.0/10、query:world-models
   evidence：以注意力作为交互图，改善动作条件世界模型训练的监督分配，实现可扩展交互感知建模
4. [Selective Agent Guidance via Entropy: Learning Autonomous Policies from Imperfect VLM Teachers](/202609/08/2609.01567v2-selective-agent-guidance-via-entropy-learning-autonomous-policies-from-imperfect-vlm-teachers)  
   标签：评分：8.0/10、query:vla-policy
   evidence：将昂贵且不完美的VLM教师知识经选择性查询和加权蒸馏转化为可学习的自主策略，符合多模态模型到策略的主题
5. [Towards Zero-Shot Transfer Across Embodiments For Driving VLAs](/202609/08/2609.02341v1-towards-zero-shot-transfer-across-embodiments-for-driving-vlas)  
   标签：评分：8.0/10、query:vla-policy
   evidence：驾驶VLA的跨本体训练与零样本迁移研究，核心属于VLA机器人控制
6. [Aligning Multi-Trajectory Supervision with Policy Optimization for VLA Driving](/202609/08/2608.30122v1-aligning-multi-trajectory-supervision-with-policy-optimization-for-vla-driving)  
   标签：评分：7.0/10、query:robot-rl
   evidence：对齐多轨迹模仿监督与GRPO策略优化，稳定VLA驾驶策略的强化学习微调
7. [ADAPT: Agile Diffusion Action Priors for Robust and Steerable Online Text-Driven Humanoid Control](/202609/08/2609.00677v1-adapt-agile-diffusion-action-priors-for-robust-and-steerable-online-text-driven-humanoid-control)  
   标签：评分：7.0/10、query:robot-rl
   evidence：在冻结的语言条件扩散动作先验上训练残差强化学习策略，以微调全身人形机器人控制。
8. [Latent Cluster Analysis for Vision-Language-Action Models](/202609/08/2609.02634v1-latent-cluster-analysis-for-vision-language-action-models)  
   标签：评分：7.0/10、query:vla-policy
   evidence：对VLA模型进行潜在簇分析，研究动作解码器的内部表征以提升可解释性
9. [RoboTok: An Internet-Scale Data Engine for Human Demonstration Retrieval and Dexterous Manipulation Learning](/202609/08/2609.03199v1-robotok-an-internet-scale-data-engine-for-human-demonstration-retrieval-and-dexterous-manipulation-learning)  
   标签：评分：7.0/10、query:world-models
   evidence：从3D手部轨迹学习潜在运动表示，用于检索跨视角和场景的人类操作示范以训练灵巧操作策略
10. [How do World Models and Policies Compose in LLM Agents? A Joint Spectral and Behavioral Account](/202609/08/2608.30067v1-how-do-world-models-and-policies-compose-in-llm-agents-a-joint-spectral-and-behavioral-account)  
   标签：评分：6.0/10、query:world-models
   evidence：通过谱与行为实验分析世界模型和策略参数更新之间的组合规律，为理解世界模型与策略整合提供方法视角
11. [PRACTICE: From Experience to Expertise in Self-Evolving Embodied Agents](/202609/08/2608.30760v1-practice-from-experience-to-expertise-in-self-evolving-embodied-agents)  
   标签：评分：6.0/10、query:vla-policy
   evidence：从交互轨迹中归纳技能库，推动多模态大语言模型迈向可执行的具身策略。
12. [Towards Generalizable Visually Grounded Exploration of Household Devices](/202609/08/2609.00845v1-towards-generalizable-visually-grounded-exploration-of-household-devices)  
   标签：评分：6.0/10、query:vla-policy
   evidence：面向家用设备提出可泛化视觉锚定探索，把大模型知识用于具身操作与泛化
13. [Accelerating Reinforcement Learning via MPC Solver-Gradient Guidance for Weights-varying MPC](/202609/08/2609.01061v1-accelerating-reinforcement-learning-via-mpc-solver-gradient-guidance-for-weights-varying-mpc)  
   标签：评分：6.0/10、query:robot-rl
   evidence：融合MPC求解器梯度与RL以缓解采样效率瓶颈，对机器人控制的RL学习具有可迁移价值


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
