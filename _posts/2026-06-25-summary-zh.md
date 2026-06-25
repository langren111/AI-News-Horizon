---
layout: default
title: "Horizon Summary: 2026-06-25 (ZH)"
date: 2026-06-25
lang: zh
---

> 从 328 条内容中筛选出 26 条重要资讯。

---

1. [OpenAI 发布首款定制 AI 推理芯片 'Jalapeno'，与 Broadcom 合作](#item-1) ⭐️ 9.0/10
2. [构建自主 AI 系统的全面指南](#item-2) ⭐️ 9.0/10
3. [Wan-Streamer v0.1：实时多模态基础模型](#item-3) ⭐️ 9.0/10
4. [SoK：AI 安全代码生成框架](#item-4) ⭐️ 9.0/10
5. [iLLaDA：8B 掩码扩散模型挑战自回归大语言模型](#item-5) ⭐️ 9.0/10
6. [模型原生计算架构：一份前瞻性综述](#item-6) ⭐️ 9.0/10
7. [Anthropic 指控阿里巴巴非法提取 Claude AI 能力](#item-7) ⭐️ 8.0/10
8. [高通收购 Modular，挑战 NVIDIA 的 CUDA](#item-8) ⭐️ 8.0/10
9. [LLM 生成的求职申请掩盖了候选人身份](#item-9) ⭐️ 8.0/10
10. [新数据表明工程岗位对 AI 最具韧性](#item-10) ⭐️ 8.0/10
11. [视觉语言模型通过推理标记模拟人类视觉搜索](#item-11) ⭐️ 8.0/10
12. [非对称 Shapley 值的高效多项式时间算法](#item-12) ⭐️ 8.0/10
13. [安全自主 AI 处方的最低要求](#item-13) ⭐️ 8.0/10
14. [OpenAI 推出 GPT-5.5 Instant 模型](#item-14) ⭐️ 8.0/10
15. [博客可以只是陈述显而易见的事](#item-15) ⭐️ 7.0/10
16. [NVIDIA 45°C 冷却方案大幅降低数据中心用水](#item-16) ⭐️ 7.0/10
17. [GitHub 上的 PR 垃圾信息如同早期电子邮件垃圾](#item-17) ⭐️ 7.0/10
18. [谷歌为 Gemini 3.5 Flash 添加计算机使用功能](#item-18) ⭐️ 7.0/10
19. [Nub：一站式 Node.js 工具包，模仿 Bun 的开发体验](#item-19) ⭐️ 7.0/10
20. [欧洲抵制美国芯片战限制](#item-20) ⭐️ 7.0/10
21. [谷歌再失两名顶尖 AI 研究员，转投 Anthropic](#item-21) ⭐️ 7.0/10
22. [企业从 Tokenmaxxing 转向 Token 配给制](#item-22) ⭐️ 7.0/10
23. [OpenMontage：首个开源智能视频制作系统](#item-23) ⭐️ 7.0/10
24. [基金旨在终结所有呼吸道感染](#item-24) ⭐️ 6.0/10
25. [MDN 浏览器兼容数据转为 SQLite 数据库](#item-25) ⭐️ 6.0/10
26. [Cerebras 财报后股价暴跌，CEO 称利润率预期被误解](#item-26) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 发布首款定制 AI 推理芯片 'Jalapeno'，与 Broadcom 合作](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI 发布了其首款定制 AI 推理芯片 'Jalapeno'，该芯片与 Broadcom 合作设计，并由 TSMC 制造。从设计到生产仅用时九个月，且借助 OpenAI 自身的 AI 模型加速了开发过程。 这标志着 OpenAI 在 AI 硬件领域向垂直整合迈出重大战略转变，减少了对 NVIDIA GPU 进行推理的依赖。通过展示针对特定工作负载优化的定制推理芯片的可行性，可能重塑 AI 硬件格局。 Jalapeno 芯片专为 AI 推理任务（如运行 ChatGPT 查询）设计，不用于训练。Broadcom 提供了定制 ASIC 设计专业知识，而 TSMC 则采用先进工艺节点负责制造。

hackernews · TechCrunch AI · 6月24日 17:47 · [社区讨论](https://news.ycombinator.com/item?id=48663324)

**背景**: AI 推理是使用训练好的模型进行预测或生成响应的过程，而训练则涉及从数据中学习。像 Google 的 TPU 这样的定制芯片已表明，专用硬件在推理方面比通用 GPU 能带来显著的效率提升。OpenAI 此举顺应了 AI 公司自行设计芯片以优化性能和成本的行业趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/06/24/technology/openai-broadcom-chip-jalapeno.html">OpenAI and Broadcom Unveil Custom A.I. Chip Design - The New York Times</a></li>
<li><a href="https://kelo.com/2026/06/24/openai-unveils-custom-chip-it-designed-with-broadcom-to-boost-its-ai-infrastructure/">OpenAI unveils custom chip it designed with Broadcom to boost its AI infrastructure | KELO-AM</a></li>
<li><a href="https://www.broadcom.com/products/custom-silicon">Custom Silicon</a></li>

</ul>
</details>

**社区讨论**: 评论者对 AI 辅助设计如何加速开发表示好奇，部分人怀疑其是否真正有效还是仅为营销手段。其他人讨论了将模型权重固化到硅片中以实现极致效率的潜力，并提及了 Taalas 等初创公司。原始帖子中未提及 TSMC 作为制造商的情况被指出并澄清。

**标签**: `#AI hardware`, `#OpenAI`, `#inference chip`, `#semiconductors`, `#AI industry`

---

<a id="item-2"></a>
## [构建自主 AI 系统的全面指南](https://arxiv.org/abs/2606.24937) ⭐️ 9.0/10

一篇题为《自主 AI 搭车指南》的新 arXiv 论文提供了构建自主 AI 系统的全面实践参考，涵盖从 Transformer 基础到多智能体协调及生产部署的完整技术栈。 该指南弥合了 LLM、对齐、推理和自主系统等孤立研究领域之间的鸿沟，为从业者和研究人员提供了统一资源。通过提供理论基础和实现指导，它可能加速可靠、可投入生产的自主 AI 的开发。 该书涵盖的主题包括 SFT、LoRA、MoE、模型压缩、推理优化、基于 PPO/DPO/GRPO 的 RLHF、思维链推理、基于轨迹的 RL 自主训练、RAG 与 Agentic RAG、记忆系统、MCP 和 A2A 协议，以及多智能体架构。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 自主 AI 指能够感知、推理并采取行动以实现目标的自主系统，通常使用 LLM 作为其核心推理引擎。构建此类系统需要集成多个层次：底层 LLM、确保安全行为的对齐技术、推理能力，以及工具使用、记忆和多智能体协调等智能体特定组件。该指南旨在提供这些相互关联层次的全局视角。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.accubits.com/how-to-fine-tune-llama-2-using-sft-lora/">How to fine-tune LLaMA 2 using SFT, LORA</a></li>
<li><a href="https://yugeten.github.io/posts/2025/01/ppogrpo/">A vision researcher’s guide to some RL stuff: PPO & GRPO - Yuge (Jimmy) Shi</a></li>
<li><a href="https://huggingface.co/blog/LinkedIn/gpt-oss-agentic-rl">Unlocking Agentic RL Training for GPT-OSS: A Practical Retrospective</a></li>

</ul>
</details>

**标签**: `#agentic AI`, `#LLM`, `#RLHF`, `#RAG`, `#AI systems`

---

<a id="item-3"></a>
## [Wan-Streamer v0.1：实时多模态基础模型](https://arxiv.org/abs/2606.25041) ⭐️ 9.0/10

Wan-Streamer v0.1 是一个原生流式、端到端的交互式基础模型，在单个 Transformer 中联合建模语言、音频和视频，实现了约 200 毫秒的模型侧响应延迟和 550 毫秒的总交互延迟，支持全双工音视频通信。 这种统一架构消除了 VAD、ASR、TTS 和视频生成等级联模块，减少了流水线延迟和错误累积，标志着实时交互式 AI 系统的范式转变，有望实现更自然的人机交互。 该模型使用块因果注意力实现增量流式处理，流式单元短至 160 毫秒（25 fps），并联合学习感知、推理、生成、响应时序、话轮管理和跨模态同步，无需外部模块。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 传统交互系统依赖语音活动检测（VAD）、自动语音识别（ASR）、语言建模、文本转语音（TTS）和视频生成等独立模块，导致高延迟和错误累积。全双工交互允许双向同时通信，如同自然对话。块因果注意力是一种按块处理输入的注意力机制，无需等待完整序列即可进行流式生成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/block-wise-causal-attention">Block-wise Causal Attention</a></li>
<li><a href="https://www.emergentmind.com/topics/full-duplex-voice-interaction-system">Full-Duplex Voice Interaction Systems</a></li>

</ul>
</details>

**标签**: `#multimodal AI`, `#real-time interaction`, `#foundation model`, `#audio-visual`, `#Transformer`

---

<a id="item-4"></a>
## [SoK：AI 安全代码生成框架](https://arxiv.org/abs/2606.25195) ⭐️ 9.0/10

这篇 SoK 论文引入了一个三级框架，用于衡量 AI 模型对安全编码原则的理解和执行，揭示了知识-执行差距：模型能识别安全原则，但无法生成安全代码。 这项工作系统性地理解了 AI 安全代码生成，帮助研究人员和从业者识别模型失败之处及改进方向，对 AI 编码工具的安全部署至关重要。 该框架在多个模型和编码代理上实例化，基准测试涵盖函数级和完整 Web 应用安全，表明安全编码原则理解是代码结果的强预测因子，但知识-执行差距仍然存在。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 像 GitHub Copilot 和 ChatGPT 这样的 AI 代码生成工具被广泛使用，但经常生成不安全的代码。现有研究探索了多种改进安全性的技术，但缺乏系统性的评估和比较框架。这篇 SoK 论文通过引入以原则为中心的评估方法填补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://papers.ssrn.com/sol3/Delivery.cfm/64864869-7e00-47aa-8e34-9521276b4101-MECA.pdf?abstractid=6779013">[PDF] On the Gap Between Declarative Vulnerability Knowledge and ...</a></li>
<li><a href="https://www.veracode.com/blog/ai-coding-tools-security-gaps/">Why AI Coding Tools Are Creating Security Gaps - Veracode</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#code generation`, `#security`, `#LLM`, `#software engineering`

---

<a id="item-5"></a>
## [iLLaDA：8B 掩码扩散模型挑战自回归大语言模型](https://arxiv.org/abs/2606.25331) ⭐️ 9.0/10

这项工作表明，具有双向注意力的掩码扩散模型可以扩展到 8B 参数并匹配自回归模型，挑战了大语言模型架构的主导范式，为生成式 AI 开辟了新方向。 iLLaDA 在预训练和监督微调中全程使用掩码扩散目标，采用可变长度生成以提高效率，并基于置信度评分进行多项选择评估。基础模型在 BBH 上比 LLaDA 提升 21.6 分，在 ARC-Challenge 上提升 14.9 分；指令模型在 MATH 上提升 14.5 分，在 HumanEval 上提升 16.5 分。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 目前大多数大语言模型使用自回归分解和因果注意力，按固定顺序逐个生成 token。掩码扩散语言模型则通过逆转 token 掩码上的加噪过程来迭代重建文本，允许双向上下文。iLLaDA 是 LLaDA 的后续工作，将掩码扩散方法扩展到 8B 参数和 12T token。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/GSAI-ML/iLLaDA-8B-Base">GSAI-ML/iLLaDA-8B-Base - Hugging Face</a></li>
<li><a href="https://louiswang524.github.io/blog/diffusion-llm/">Diffusion Language Models: How They Work, How They Compare to...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#diffusion models`, `#language modeling`, `#AI research`, `#scaling`

---

<a id="item-6"></a>
## [模型原生计算架构：一份前瞻性综述](https://arxiv.org/abs/2606.00288) ⭐️ 9.0/10

该论文提出将 LLM 视为 CPU、KV 缓存视为处理器缓存、智能体框架视为操作系统，并利用数十年的计算机架构智慧，为模型原生系统设计了一个六层智能计算架构（ICA）。 这项工作提供了一个统一框架，将经典计算机架构与现代 LLM 系统联系起来，有望指导未来 AI 基础设施的系统设计和研究。 ICA 由六个功能层组成，包含接口契约和设计公理，并引入了一个双平面架构，将概率执行与确定性控制分离。论文还提出了三个类似 Amdahl 的设计启发式：语义局部性、上下文预算和智能体加速比。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 大型语言模型（LLM）以自回归方式生成文本，KV 缓存存储中间键值向量以避免重复计算，从而加速推理。计算机架构长期以来使用层次化内存和操作系统来管理资源；本文将这些概念与 LLM 系统组件进行类比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/data-science-collective/understanding-the-kv-cache-in-llms-822446560161">Understanding the KV-Cache In LLMs | by Dr. Leon Eversberg | Medium</a></li>
<li><a href="https://lzwjava.github.io/kv-cache-inference-en">Understanding KV Cache in LLM Inference</a></li>
<li><a href="https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms">Understanding and Coding the KV Cache in LLMs from Scratch</a></li>

</ul>
</details>

**标签**: `#LLM`, `#computer architecture`, `#agent systems`, `#systems research`, `#AI infrastructure`

---

<a id="item-7"></a>
## [Anthropic 指控阿里巴巴非法提取 Claude AI 能力](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

Anthropic 指控阿里巴巴通过模型蒸馏（model distillation）过程非法提取其 Claude AI 模型的能力，即用较强模型的输出来训练较弱模型。 这一争议凸显了 AI 行业在知识产权和竞争实践方面日益紧张的关系，可能影响未来对模型蒸馏和数据使用的监管。 据报道，中国转售商通过合并账户和转售输出来提供比官方 API 价格低 70-90%的 Claude 代币，这些输出可能被用作其他模型的训练数据。

hackernews · htrp · 6月24日 19:48 · [社区讨论](https://news.ycombinator.com/item?id=48664814)

**背景**: 模型蒸馏是一种机器学习技术，将知识从大型、强大的模型转移到更小、更高效的模型。Anthropic 的 Claude 是一个大型语言模型，旨在成为有用、诚实且无害的 AI 助手。使用一个模型的输出来训练另一个模型的做法很常见，但未经许可进行时会引发法律和伦理问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了讽刺，指出 Anthropic 本身也使用大量互联网数据训练 Claude 而未向创作者付费，并且逆向工程竞争对手是行业标准做法。一些人将其与历史上的技术纠纷（如苹果对施乐）相提并论。

**标签**: `#AI industry`, `#model distillation`, `#intellectual property`, `#regulation`, `#ethics`

---

<a id="item-8"></a>
## [高通收购 Modular，挑战 NVIDIA 的 CUDA](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

高通宣布以近 40 亿美元收购 AI 初创公司 Modular，旨在构建 NVIDIA CUDA 的替代方案，用于 ARM 芯片上的低成本 AI 推理。 此举可能打破 NVIDIA 在 AI 推理领域的主导地位，使高通基于 ARM 的芯片能够高效运行 AI 工作负载，从而降低成本并扩展 AI 在数据中心和边缘设备中的部署。 Modular 的编译器栈（包括 Mojo 编程语言和 MAX 平台）使 AI 模型能够在不同硬件架构上高效运行，提供了 CUDA 的可移植替代方案。

hackernews · timmyd · 6月24日 13:49 · [社区讨论](https://news.ycombinator.com/item?id=48659798)

**背景**: NVIDIA 的 CUDA 是一种专有并行计算平台，已成为 AI 工作负载的事实标准，将开发者锁定在 NVIDIA 硬件上。高通的 ARM 芯片广泛应用于移动设备，但在数据中心的 AI 推理能力有限。Modular 由 Chris Lattner（LLVM 和 Swift 的创建者）创立，开发开放的 AI 原生软件栈，将 AI 软件与特定硬件解耦。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://semiwiki.com/forum/threads/qualcomm-buys-buzzy-chip-startup-modular-for-nearly-4-billion.25364/">Qualcomm Buys Buzzy Chip Startup Modular for Nearly $4 Billion</a></li>
<li><a href="https://www.reddit.com/r/hardware/comments/1uefqv2/qualcomm_inks_deal_for_ai_startup_modular_to/">Qualcomm inks deal for AI startup Modular to bolster software stack ...</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人认为这是挑战 NVIDIA 的战略举措，而另一些人则质疑 Modular 的技术能否兑现承诺。评论还提到了中国基于 ARM 的超级计算机的时机以及高通在 RISC-V 方面的广泛投资。

**标签**: `#AI industry`, `#acquisition`, `#Qualcomm`, `#Modular`, `#AI hardware`

---

<a id="item-9"></a>
## [LLM 生成的求职申请掩盖了候选人身份](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 8.0/10

Tom MacWright 观察到，越来越多的求职申请、作品集和 GitHub 项目是由 LLM 共同撰写的，这使得候选人变得千篇一律、缺乏个性，无法展现其真实技能或人格。 这一趋势侵蚀了招聘过程中的真实性，使雇主更难评估真正的人才，也让候选人难以凭借真实成就脱颖而出。 MacWright 指出，甚至连提交信息都是纯 LLM 生成的，从简历到作品集再到代码的整个申请链条都由 AI 产出，没有留下任何个人声音或工作的痕迹。

rss · Simon Willison · 6月24日 18:13

**背景**: 像 GPT-4 这样的 LLM 可以生成令人信服的文本、代码和项目文档。求职者越来越多地使用这些工具来自动化申请材料，但过度依赖会抹去个人表达，使候选人难以区分。

**标签**: `#AI & society`, `#careers`, `#personal branding`, `#ethics`, `#hiring`

---

<a id="item-10"></a>
## [新数据表明工程岗位对 AI 最具韧性](https://techcrunch.com/2026/06/24/ai-was-supposed-to-kill-engineering-jobs-but-new-data-suggests-theyre-the-most-resilient/) ⭐️ 8.0/10

SignalFire 的数据显示，尽管 AI 驱动的裁员叙事盛行，工程岗位的招聘增速却超过大多数其他技术职能。这一发现挑战了 AI 正在取代工程师的假设。 这一基于数据的反叙事意义重大，因为它将讨论从失业恐惧转向理解 AI 如何重塑角色。工程师可能比预想的更具韧性，这将影响职业规划和企业战略。 SignalFire 研究主管 Asher Bantock 指出，如果 AI 真的在替代工程人才，那么在技术招聘收缩期间工程招聘应最先下降。然而，工程岗位的增长速度却快于其他职能。

rss · TechCrunch AI · 6月24日 21:56

**背景**: 长期以来存在一种普遍叙事，认为 AI（尤其是生成式 AI）将自动化许多工程任务并导致失业。然而，这种叙事可能被夸大，一些公司利用“AI 洗白”来为裁员辩护。SignalFire 的报告提供了具体的招聘数据来评估真实影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/ai-was-supposed-to-kill-engineering-jobs-but-new-data-suggests-theyre-the-most-resilient/">AI was supposed to kill engineering jobs, but new data... | TechCrunch</a></li>
<li><a href="https://newsgab.com/engineering-jobs-most-resilient-to-ai-new-data/">Despite Fears, New Data Finds Engineering Jobs Most Resilient To AI</a></li>
<li><a href="https://www.signalfire.com/blog/signalfire-state-of-talent-report-2025">The SignalFire State of Tech Talent Report - 2025</a></li>

</ul>
</details>

**社区讨论**: TechCrunch 文章及相关讨论的评论普遍认为 AI 取代工程师的叙事被夸大了。一些开发者指出，AI 工具提高了生产力，但并未消除对熟练工程师的需求，尤其是那些能将 AI 投入生产的工程师。

**标签**: `#AI & society`, `#employment impact`, `#engineering jobs`, `#data analysis`

---

<a id="item-11"></a>
## [视觉语言模型通过推理标记模拟人类视觉搜索](https://arxiv.org/abs/2606.25066) ⭐️ 8.0/10

该论文将经典视觉搜索范式应用于视觉语言模型（VLM），使用推理标记数量作为反应时间的代理，发现前沿模型再现了人类搜索的关键特征。 这项工作通过为机器视觉认知提供行为探针，揭示了与人类搜索行为的相似性和有信息价值的差异，从而连接了认知科学和人工智能。 该研究测试了四种范式：特征搜索与联合搜索、T-vs-L 搜索、计数和搜索不对称性，将模型的推理标记计数与大型基准中的人类反应时间进行比较。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 视觉搜索范式通过测量反应时间随项目数量的变化来区分并行弹出搜索和串行注意力需求搜索。推理标记是一些大语言模型在推理过程中生成的内部标记，代表中间思考步骤，在最终输出中不可见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S2666920X2100014X">sciencedirect.com/science/article/pii/S2666920X2100014X</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC3253411/">Mechanisms and Representations of Language-Mediated Visual...</a></li>
<li><a href="https://aicodereview.cc/blog/input-vs-output-vs-reasoning-tokens-cost/">Input vs Output vs Reasoning Tokens Cost - LLM Pricing Explained</a></li>

</ul>
</details>

**标签**: `#vision-language models`, `#visual attention`, `#cognitive science`, `#reasoning tokens`, `#AI behavior`

---

<a id="item-12"></a>
## [非对称 Shapley 值的高效多项式时间算法](https://arxiv.org/abs/2606.25103) ⭐️ 8.0/10

本文提出了在因果图中计算非对称 Shapley 值（ASV）的多项式时间算法，克服了标准 SHAP 在某些情况下的#P-hard 难题。 这项工作使因果感知的模型解释在计算上变得可行，从而在具有因果结构的领域中实现 ASV 在可解释 AI 中的实际应用。 该算法在拓扑排序等价类数量上运行于多项式时间，并且对于有根有向树是精确的。对于任意 DAG，提供了一种使用拓扑排序均匀采样的近似算法。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 合作博弈论中的 Shapley 值广泛用于机器学习中的特征归因，但标准 SHAP 忽略了因果结构且通常计算为#P-hard。非对称 Shapley 值（ASV）通过因果图引入因果知识，但其计算此前难以处理。本文填补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/1910.06358">[1910.06358] Asymmetric Shapley values: incorporating causal...</a></li>
<li><a href="https://norskregnesentral.github.io/shapr/articles/asymmetric_causal.html">Asymmetric and causal Shapley value explanations • shapr</a></li>
<li><a href="https://proceedings.neurips.cc/paper/2020/file/0d770c496aa3da6d2c3f2bd19e7b9d6b-Paper.pdf">Asymmetric Shapley values: incorporating causal</a></li>

</ul>
</details>

**标签**: `#AI/ML`, `#Explainability`, `#Causal Inference`, `#Shapley Values`, `#Algorithm`

---

<a id="item-13"></a>
## [安全自主 AI 处方的最低要求](https://arxiv.org/abs/2606.25108) ⭐️ 8.0/10

一篇新的 arXiv 论文基于对 136 名美国临床医生的调查，主张自主 AI 处方系统必须包含校准置信度、差异化不确定性沟通和推理透明度。 这项研究提出了具体的架构要求，可能影响未来医疗领域自主 AI 的监管，解决了随着 H.R. 238 等立法推进而出现的信任、责任和安全等关键问题。 临床医生倾向于基于校准置信度的升级机制、针对偶然不确定性的竞争选项摘要，以及针对认知不确定性的弃权；他们仅在推理透明度允许实质性判断时才接受责任。

rss · ArXiv CS.AI · 6月25日 04:00

**背景**: 自主 AI 系统正从咨询角色转向直接开具处方，如美国 H.R. 238 法案和犹他州的试点项目所示。当前的监管指南侧重于整体模型性能，但缺乏对每次预测的置信度校准、区分认知不确定性与偶然不确定性，以及决策时透明度以分配责任的要求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2501.12868v1">Exploring the Effect of AI Confidence on Human Self-confidence ... - arXiv</a></li>
<li><a href="https://link.springer.com/article/10.1007/s10994-021-05946-3">Aleatoric and epistemic uncertainty in machine learning: an...</a></li>
<li><a href="https://hdsr.mitpress.mit.edu/pub/aelql9qy">AI Transparency in the Age of LLMs: A Human-Centered Research ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#healthcare AI`, `#autonomous systems`, `#regulation`, `#uncertainty quantification`

---

<a id="item-14"></a>
## [OpenAI 推出 GPT-5.5 Instant 模型](https://www.reddit.com/r/OpenAI/comments/1uen1zv/gpt55_instant_now_rolling_out/) ⭐️ 8.0/10

OpenAI 已开始推出 GPT-5.5 Instant，这是其语言模型系列的一次增量更新，据 Reddit 用户报道。 此次发布表明 OpenAI 在 AI 模型领域持续快速迭代，可能提供比先前版本更优的性能或效率，从而影响依赖 OpenAI API 的开发者和企业。 该模型名为 'GPT-5.5 Instant'，暗示可能针对更低延迟或更快推理进行了优化。目前尚未发布官方更新日志或基准数据。

reddit · r/OpenAI · /u/imfrom_mars_ · 6月24日 19:17

**背景**: OpenAI 的 GPT 系列从 GPT-3 发展到 GPT-4 及更高版本，每一版都在推理、创造力和准确性上有所提升。'Instant' 变体通常表示更快、更具成本效益的模型层级。

**社区讨论**: Reddit 帖子中反应不一：一些用户对潜在的速度提升感到兴奋，而另一些用户则质疑缺乏透明度，并认为这可能是小修小补而非重大升级。

**标签**: `#AI/ML`, `#OpenAI`, `#GPT-5.5`, `#model release`, `#industry`

---

<a id="item-15"></a>
## [博客可以只是陈述显而易见的事](https://blog.jim-nielsen.com/2026/blogging-stating-the-obvious/) ⭐️ 7.0/10

Jim Nielsen 认为，博客可以只是陈述那些对你显而易见但对他人并非如此的事情，利用“知识的诅咒”来提供价值。 这一见解鼓励更多人分享知识，无需担心重复，从而可能丰富博客生态系统的多样性视角。 文章指出，“知识的诅咒”使专家假设他人也拥有相同的理解，因此陈述显而易见的事对新手来说可能很有价值。

hackernews · Curiositry · 6月24日 23:46 · [社区讨论](https://news.ycombinator.com/item?id=48666927)

**背景**: “知识的诅咒”是一种认知偏差，指拥有专业知识的人高估了他人对该知识的了解程度。在博客写作中，这种偏差常使专家不愿写基础话题，认为人人都已知道。然而，对许多读者，尤其是初学者来说，这些“显而易见”的见解是新颖且有帮助的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Curse_of_knowledge">Curse of knowledge</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认同这一观点，分享了个人经历，其中陈述显而易见的事帮助了他人。一些人指出，总有一批新人群未曾听过这些信息，因此这类帖子很有价值。

**标签**: `#blogging`, `#personal branding`, `#writing`, `#knowledge sharing`, `#curse of knowledge`

---

<a id="item-16"></a>
## [NVIDIA 45°C 冷却方案大幅降低数据中心用水](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA 宣布了一种用于 AI 数据中心的 45°C 液冷设计，采用直接到芯片的温水冷却，通过干式冷却器而非蒸发冷却塔散热，将用水量降至接近零。 这一创新解决了 AI 数据中心巨大的水足迹问题——传统冷却每兆瓦每年可消耗 260 万加仑水——并为废热用于区域供暖打开了大门，使运营商和当地社区都受益。 该设计采用单相直接液冷，供水温度为 45°C（113°F），高于常规标准，使得干式冷却器可以利用环境空气运行，无需高能耗的冷水机组。NVIDIA 的 Vera Rubin NVL72 是支持该架构的产品之一。

hackernews · nitin_flanker · 6月24日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48660178)

**背景**: 数据中心因高密度 AI 计算产生大量热量，传统上需要高能耗的冷水机组或耗水量大的蒸发冷却。液冷直接从芯片带走热量，更高的冷却液温度可提高效率并实现热量再利用。区域供暖网络将热水从中央热源分配到建筑物用于空间供暖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45°C Liquid Cooling Design for AI Data Centers</a></li>
<li><a href="https://www.techbuzz.ai/articles/nvidia-s-45-c-liquid-cooling-redefines-ai-data-center-energy">NVIDIA's 45°C Liquid Cooling Redefines AI Data Center Energy</a></li>
<li><a href="https://www.networkworld.com/article/4149069/why-ai-rack-densities-make-liquid-cooling-nonnegotiable.html">Why AI rack densities make liquid cooling... | Network World</a></li>

</ul>
</details>

**社区讨论**: 评论者强调了区域供暖协同的潜力，指出 45°C 可用于供暖回路，每年可为社区带来数百万美元的价值。一些人质疑与现有液冷相比该设计的创新之处，另一些人则询问气候限制以及与室外温度的效率相关性。

**标签**: `#data center`, `#cooling`, `#energy efficiency`, `#NVIDIA`, `#infrastructure`

---

<a id="item-17"></a>
## [GitHub 上的 PR 垃圾信息如同早期电子邮件垃圾](https://www.greptile.com/blog/prs-on-openclaw) ⭐️ 7.0/10

Greptile 的一篇博客文章将 GitHub 上垃圾拉取请求（PR）的增加与 21 世纪初的电子邮件垃圾泛滥相提并论，认为开源维护者现在面临着类似的大量低质量、AI 生成的贡献。 这种比较凸显了对开源可持续性日益增长的威胁，维护者将时间浪费在分类垃圾信息上，而不是审查真正的贡献，可能导致倦怠并降低项目健康度。 文章指出，垃圾 PR 通常包含 AI 生成的代码、SEO 链接注入或与 Hacktoberfest 相关的噪音，并建议类似电子邮件发送者评分的信誉系统可能有助于缓解问题。

hackernews · dakshgupta · 6月24日 14:32 · [社区讨论](https://news.ycombinator.com/item?id=48660579)

**背景**: GitHub 上的开源项目依赖拉取请求进行贡献，但生成式 AI 的兴起使得大量低质量代码变得容易产生。如果没有有效的过滤，维护者必须手动审查每个 PR，这在规模上变得不可持续。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/PThorpe92/fossier">GitHub - PThorpe92/fossier: Vouch-compatible PR-spam reduction...</a></li>
<li><a href="https://hugovk.dev/blog/2026/gh-triage/">A CLI to fight GitHub spam · Hugo van Kemenade</a></li>
<li><a href="https://mansoorbarri.medium.com/how-can-github-fix-spamming-14e9bab59294">How Can GitHub Fix Spamming?. Background | by Mansoor... | Medium</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，GitHub 最近为维护者添加了可配置的 PR 限制，但有些人认为电子邮件垃圾解决方案依赖于服务器级别的信誉，这并不直接适用于单个 GitHub 用户。其他人对信誉基础设施和类似 uBlock Origin 的退订列表表示兴趣。

**标签**: `#open source`, `#spam`, `#GitHub`, `#maintainer tools`, `#tech ethics`

---

<a id="item-18"></a>
## [谷歌为 Gemini 3.5 Flash 添加计算机使用功能](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 7.0/10

谷歌已将计算机使用功能直接集成到 Gemini 3.5 Flash 模型中，使 AI 能够与桌面应用程序交互并执行代理任务。此前该功能仅作为独立的 Gemini 2.5 模型提供。 这一进步使 AI 能够自动化涉及多个软件工具的复杂工作流程，可能提高生产力。然而，社区反馈指出了显著的可信性和安全性问题，可能限制其实际应用。 计算机使用工具现已成为 Gemini 3.5 Flash 的内置功能，在代理任务上性能有所提升。用户报告了 AI 执行破坏性命令（如'git reset --hard'）以及在简单数据提取任务上放弃等问题。

hackernews · swolpers · 6月24日 17:21 · [社区讨论](https://news.ycombinator.com/item?id=48662999)

**背景**: 计算机使用指的是 AI 模型直接控制计算机图形用户界面的能力，类似于人类使用鼠标和键盘。这是 AI 代理更广泛趋势的一部分，这些代理可以自主执行跨不同应用程序的多步骤任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/">Introducing computer use in Gemini 3.5 Flash</a></li>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3.5 Flash — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/generate-content/whats-new-gemini-3.5">What's new in Gemini 3.5 Flash | Gemini Generate Content API...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了怀疑和沮丧：用户报告 AI 犯下破坏性错误（例如运行'git reset --hard'）以及在简单任务（如从 PDF 提取表格）上失败。一些人批评'计算机使用'这一术语过于模糊，另一些人指出 Gemini 3.5 Flash 在基准测试中被竞争对手超越。

**标签**: `#AI/ML`, `#Gemini`, `#AI agent`, `#product review`, `#AI safety`

---

<a id="item-19"></a>
## [Nub：一站式 Node.js 工具包，模仿 Bun 的开发体验](https://github.com/nubjs/nub) ⭐️ 7.0/10

Colin McDonnell 发布了 Nub，这是一个面向 Node.js 的一站式工具包，通过--require 预加载钩子添加了基于 oxc 编译器的转译、模块解析钩子以及 Worker 和 Temporal 等 API 的 polyfill，旨在复制 Bun 的开发体验。 Nub 将类似 Bun 的开发体验带到了 Node.js，无需切换运行时，可能提高希望获得 TypeScript 转译和内置 polyfill 等现代功能的 Node.js 开发者的生产力。 Nub 使用--require 预加载钩子而非--import，这引发了关于 ESM 支持细节（如顶层 await）的疑问。转译器由基于 Rust 的高性能工具 oxc 驱动，并打包为 Node-API 插件。

hackernews · colinmcd · 6月24日 14:14 · [社区讨论](https://news.ycombinator.com/item?id=48660267)

**背景**: Bun 是一个快速的一体化 JavaScript 运行时，包含转译器、包管理器和测试运行器。Node.js 缺乏内置的 TypeScript 支持和某些现代 API，需要第三方工具。Nub 通过钩子为 Node.js 添加类似能力，填补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/oxc-project/oxc">oxc-project/oxc: ⚓ A collection of high-performance JavaScript tools.</a></li>

</ul>
</details>

**社区讨论**: 社区反响积极，用户称赞其创意和速度。有用户将整个 monorepo 迁移到 Nub，未遇到任何问题。但也有技术疑问：由于使用--require 而非--import，ESM 支持存在细节问题；还有人质疑既然 Node 已支持 TypeScript，为何还需要转译器。

**标签**: `#Node.js`, `#Bun`, `#developer tools`, `#TypeScript`, `#open source`

---

<a id="item-20"></a>
## [欧洲抵制美国芯片战限制](https://techcrunch.com/2026/06/24/europe-is-pushing-back-on-washingtons-chip-war/) ⭐️ 7.0/10

欧洲正在抵制美国主导的对华芯片战，ASML 首席执行官 Christophe Fouquet 指出，美国拟议的 MATCH 法案将禁止向中国销售目前允许的老一代深紫外（DUV）光刻工具。 这一抵制凸显了跨大西洋在半导体出口管制问题上日益紧张的关系，可能扰乱全球芯片供应链并影响 AI 硬件的可用性，因为 DUV 工具对于生产各行业使用的成熟制程芯片至关重要。 MATCH 法案是一项美国两党法案，旨在通过限制 ASML 向中国出口所有 DUV 设备来堵住漏洞，这些设备目前约占 ASML 预期收入的五分之一。ASML 认为，这些十年前首次出货的老旧工具并非尖端技术，应继续允许出口。

rss · TechCrunch AI · 6月25日 00:08

**背景**: 美国以国家安全为由，一直在收紧对华先进半导体技术的出口管制。ASML 是全球领先的光刻系统供应商，其设备对芯片制造至关重要。EUV（极紫外）工具是最先进的，而 DUV 工具较老，但仍广泛用于制造不那么先进的芯片。MATCH 法案将把限制扩大到目前尚未完全禁止的 DUV 工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/19/the-us-says-asmls-top-chip-tool-may-be-in-china-asml-says-it-isnt/">The US says ASML's top chip tool may be in China, but... | TechCrunch</a></li>
<li><a href="https://overcentral.com/en/netherlands-opposes-match-act-asml-china/">Netherlands Opposes US Bill Restricting ASML Chip Sales to China</a></li>
<li><a href="https://www.manufacturingdive.com/news/lawmakers-push-restrictions-chipmaking-equipment-exports-china-match-act/816945/">Lawmakers push to restrict chipmaking... | Manufacturing Dive</a></li>

</ul>
</details>

**标签**: `#chip war`, `#semiconductors`, `#geopolitics`, `#AI hardware`, `#Europe`

---

<a id="item-21"></a>
## [谷歌再失两名顶尖 AI 研究员，转投 Anthropic](https://techcrunch.com/2026/06/24/ai-researchers-continue-to-leave-google-for-its-rivals/) ⭐️ 7.0/10

顶尖 AI 研究员 Jonas Adler 和 Alexander Pritzel 离开谷歌，加入 Anthropic，此前已有 Noam Shazeer 和 John Jumper 离职。 这一趋势表明人才从谷歌流向 Anthropic 等竞争对手，可能改变 AI 开发的竞争格局。 Adler 曾参与谷歌的 AI 编码项目，Pritzel 负责训练 AI 系统；两人都是 DeepMind 和 Gemini 的关键贡献者。

rss · TechCrunch AI · 6月24日 21:42

**背景**: 谷歌长期以来一直是 AI 研究的领导者，但近期多位知名研究员离职加入 Anthropic 等初创公司，凸显了人才竞争加剧。Anthropic 由前 OpenAI 员工创立，专注于安全 AI 开发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/ai-researchers-continue-to-leave-google-for-its-rivals/">AI researchers continue to leave Google for its rivals - TechCrunch</a></li>
<li><a href="https://mezha.net/eng/bukvy/ce3ab401_jonas_adler_and/">Jonas Adler and Alexander Pritzel leave Google for Anthropic, raising ...</a></li>

</ul>
</details>

**社区讨论**: 在 Reddit 上，用户对谷歌留住人才的能力表示担忧，一些人指出 Anthropic 对安全性的关注可能吸引寻求更有影响力工作的研究员。

**标签**: `#AI industry`, `#talent flow`, `#Google`, `#Anthropic`

---

<a id="item-22"></a>
## [企业从 Tokenmaxxing 转向 Token 配给制](https://techcrunch.com/2026/06/24/companies-are-scrambling-to-stop-employees-from-maxing-out-ai-budgets-with-small-tasks/) ⭐️ 7.0/10

企业正从允许无限制使用 AI 转向实施 Token 配给制，因为员工在琐碎任务上耗尽了 AI 预算，这标志着“Tokenmaxxing”时代的结束。 这一转变凸显了企业采用 AI 的关键挑战：平衡生产力提升与成本控制。它可能导致更高效的 AI 使用，但如果配给过于严格，也可能抑制创新。 Tokenmaxxing 指将 Token 消耗最大化作为生产力指标，但批评者认为这导致浪费性使用和更高成本。Token 配给旨在通过限制每用户或每任务的 Token 配额来遏制这种情况。

rss · TechCrunch AI · 6月24日 20:09

**背景**: AI 服务按 Token 收费，Token 代表处理工作的单位。一些员工开始将高 Token 使用量视为生产力标志，这种做法被称为“Tokenmaxxing”。这导致企业成本飙升，促使转向配给制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Token_maxxing">Token maxxing</a></li>
<li><a href="https://www.techbuzz.ai/articles/enterprise-ai-s-token-rationing-era-begins-as-costs-spiral">Enterprise AI's Token Rationing Era Begins as Costs... | The Tech Buzz</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#enterprise AI`, `#AI adoption`, `#cost management`, `#AI ethics`

---

<a id="item-23"></a>
## [OpenMontage：首个开源智能视频制作系统](https://github.com/calesthio/OpenMontage) ⭐️ 7.0/10

OpenMontage 作为全球首个开源智能视频制作系统发布，包含 12 条流水线、52 个工具和超过 500 项智能体技能。 该项目将 AI 编程助手转变为完整的视频制作工作室，使专业级视频创作大众化，并实现自动化的端到端工作流程。 该系统提供模块化视频流水线，涵盖脚本编写、合成、动画和渲染，并由 AI 助手协调实现实时质量管控。

ossinsight · calesthio · 6月25日 04:06

**背景**: 传统的 AI 视频工具通常根据提示生成单个片段，缺乏专业制作的结构化多步骤流程。OpenMontage 采用智能体方法，由 AI 助手协调多个工具和技能，自动化真实制作团队遵循的完整流水线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/calesthio/OpenMontage">GitHub - calesthio/OpenMontage: World's first open-source, agentic...</a></li>
<li><a href="https://topai.tools/t/openmontage">OpenMontage - AI Video Tool</a></li>
<li><a href="https://zread.ai/calesthio/OpenMontage">Overview | calesthio/OpenMontage | Zread</a></li>

</ul>
</details>

**标签**: `#AI/ML`, `#open-source`, `#agent`, `#video production`, `#Python`

---

<a id="item-24"></a>
## [基金旨在终结所有呼吸道感染](https://blog.interceptfund.com/p/ending-respiratory-infections) ⭐️ 6.0/10

一项 5 亿美元的慈善基金启动，旨在通过研究和初创投资终结所有呼吸道感染，目标宏大。 如果成功，这将大幅减轻每年影响数十亿人的呼吸道疾病负担，但其可行性和资源分配引发激烈争论。 该基金由 Intercept Fund 管理，聚焦科学研究和支持初创企业。批评者质疑，考虑到呼吸道病毒的复杂性，5 亿美元是否足够。

hackernews · EthanFantl · 6月25日 01:14 · [社区讨论](https://news.ycombinator.com/item?id=48667588)

**背景**: 普通感冒、流感和 COVID-19 等呼吸道感染每年导致数百万人死亡和数十亿人患病。目前的治疗多为对症治疗，疫苗仅针对少数病原体。通用解决方案需要在病毒学和免疫学上取得突破。

**社区讨论**: 评论情绪复杂：有人分享个人悲剧并希望成功，也有人质疑可行性，认为更简单的公共卫生措施（如糖税）可以用更少的钱取得更大效果。

**标签**: `#health`, `#philanthropy`, `#biotech`, `#public health`

---

<a id="item-25"></a>
## [MDN 浏览器兼容数据转为 SQLite 数据库](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 6.0/10

Simon Willison 使用 Claude Code for Web (Opus 4.8) 和 Codex Desktop (GPT-5.5) 生成的脚本，将 Mozilla 的 mdn/browser-compat-data 仓库转换为约 66MB 的 SQLite 数据库，并通过 GitHub CDN 以开放 CORS 头的方式提供访问。 这使得 MDN 全面的浏览器兼容数据可通过 SQL 轻松查询，开发者无需解析 JSON 即可快速检查跨浏览器的特性支持。同时，它展示了使用 AI 编码工具自动化数据转换和部署的实用工作流。 数据库通过 GitHub Actions 工作流构建，并强制推送到一个孤立的 'db' 分支，从而支持直接下载并带有开放 CORS 头。用户可以使用 Datasette Lite 交互式地探索数据。

rss · Simon Willison · 6月24日 23:59

**背景**: MDN（Mozilla 开发者网络）维护着一个 browser-compat-data 仓库，记录哪些 Web 平台特性在哪些浏览器版本中得到支持。Simon Willison 是知名开发者，他创建了 sqlite-utils 和 Datasette 等工具，用于轻松创建和探索 SQLite 数据库。2026 年 6 月发布的 MDN MCP 服务器为 AI 代理提供了对 MDN 数据的编程访问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server - MDN Web Docs</a></li>
<li><a href="https://sqlite-utils.datasette.io/">sqlite-utils</a></li>

</ul>
</details>

**标签**: `#browser compatibility`, `#SQLite`, `#AI coding tools`, `#MDN`, `#data tooling`

---

<a id="item-26"></a>
## [Cerebras 财报后股价暴跌，CEO 称利润率预期被误解](https://techcrunch.com/2026/06/24/cerebras-stock-plunges-after-earnings-as-ceo-says-margin-outlook-was-misunderstood/) ⭐️ 6.0/10

Cerebras 上市后首份财报发布，因核心业务毛利率预期收窄，股价大幅下跌。CEO Andrew Feldman 澄清称投资者误解了利润率展望，部分原因在于公司需要从一个大客户那里租回设备。 这一事件凸显了 AI 芯片市场的激烈竞争，Cerebras 预计的毛利率（38-41%）远低于 Nvidia（约 75%）和 AMD（约 55%）。这凸显了新进入者在扩大业务规模时实现盈利所面临的挑战。 Cerebras 预测 2026 年全年核心毛利率为 38% 至 41%，低于 2026 年第一季度的 47%，第二季度毛利率为 36% 至 38%。公司营收超出预期，但利润率展望吓坏了投资者。

rss · TechCrunch AI · 6月24日 22:41

**背景**: Cerebras 是一家 AI 芯片制造商，以其晶圆级引擎闻名，该引擎专为超快 AI 训练而设计。该公司近期上市，这是其首份财报。毛利率是关键的盈利指标，与 Nvidia 和 AMD 等竞争对手相比，较低的毛利率引发了对 Cerebras 竞争地位的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/cerebras-stock-plunges-after-earnings-as-ceo-says-margin-outlook-was-misunderstood/">Cerebras stock plunges after earnings as CEO says margin outlook...</a></li>
<li><a href="https://au.finance.yahoo.com/news/cerebras-revenue-nearly-doubles-margin-132812966.html">Cerebras Revenue Nearly Doubles but Margin Outlook Sends Shares...</a></li>
<li><a href="https://particle.news/story/cerebras-beats-revenue-estimates-but-flags-much-lower-margins-than-rivals">Cerebras Beats Revenue Estimates but Flags Much Lower Margins...</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#company strategies`, `#Cerebras`, `#stock market`

---