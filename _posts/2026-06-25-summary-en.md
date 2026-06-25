---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 328 items, 26 important content pieces were selected

---

1. [OpenAI unveils first custom AI inference chip 'Jalapeno' with Broadcom](#item-1) ⭐️ 9.0/10
2. [Comprehensive Guide to Building Agentic AI Systems](#item-2) ⭐️ 9.0/10
3. [Wan-Streamer v0.1: Real-Time Multimodal Foundation Model](#item-3) ⭐️ 9.0/10
4. [SoK: AI Secure Code Generation Framework](#item-4) ⭐️ 9.0/10
5. [iLLaDA: 8B Masked Diffusion Model Challenges Autoregressive LLMs](#item-5) ⭐️ 9.0/10
6. [Model-Native Computing Architecture: A Visionary Survey](#item-6) ⭐️ 9.0/10
7. [Anthropic Accuses Alibaba of Illicitly Extracting Claude AI Capabilities](#item-7) ⭐️ 8.0/10
8. [Qualcomm Acquires Modular to Challenge NVIDIA's CUDA](#item-8) ⭐️ 8.0/10
9. [LLM-Generated Job Apps Obscure Candidate Identity](#item-9) ⭐️ 8.0/10
10. [Engineering jobs prove most resilient to AI, new data shows](#item-10) ⭐️ 8.0/10
11. [VLMs mimic human visual search via reasoning tokens](#item-11) ⭐️ 8.0/10
12. [Efficient Polynomial-Time Algorithms for Asymmetric Shapley Values](#item-12) ⭐️ 8.0/10
13. [Minimum Requirements for Safe Autonomous AI Prescribing](#item-13) ⭐️ 8.0/10
14. [OpenAI Rolls Out GPT-5.5 Instant Model](#item-14) ⭐️ 8.0/10
15. [Blogging Can Be Stating the Obvious](#item-15) ⭐️ 7.0/10
16. [NVIDIA's 45°C Cooling Slashes Data Center Water Use](#item-16) ⭐️ 7.0/10
17. [PR Spam on GitHub Echoes Early Email Spam](#item-17) ⭐️ 7.0/10
18. [Google Adds Computer Use to Gemini 3.5 Flash](#item-18) ⭐️ 7.0/10
19. [Nub: All-in-one Node.js toolkit mimicking Bun's DX](#item-19) ⭐️ 7.0/10
20. [Europe pushes back on US chip war restrictions](#item-20) ⭐️ 7.0/10
21. [Google loses two more top AI researchers to Anthropic](#item-21) ⭐️ 7.0/10
22. [Companies Shift from Tokenmaxxing to Token Rationing](#item-22) ⭐️ 7.0/10
23. [OpenMontage: First Open-Source Agentic Video Production System](#item-23) ⭐️ 7.0/10
24. [Fund Aims to End All Respiratory Infections](#item-24) ⭐️ 6.0/10
25. [MDN Browser Compat Data Converted to SQLite](#item-25) ⭐️ 6.0/10
26. [Cerebras stock plunges after earnings, CEO blames margin misunderstanding](#item-26) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI unveils first custom AI inference chip 'Jalapeno' with Broadcom](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI has unveiled its first custom AI inference chip, named 'Jalapeno', designed in collaboration with Broadcom and manufactured by TSMC. The chip was developed from design to production in just nine months, accelerated by OpenAI's own AI models. This marks a major strategic shift for OpenAI toward vertical integration in AI hardware, reducing reliance on NVIDIA GPUs for inference. It could reshape the AI hardware landscape by demonstrating the viability of custom inference chips optimized for specific workloads. The Jalapeno chip is specifically designed for AI inference tasks, such as running ChatGPT queries, and is not intended for training. Broadcom provided custom ASIC design expertise, while TSMC handles manufacturing using advanced process nodes.

hackernews · TechCrunch AI · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: AI inference is the process of using a trained model to make predictions or generate responses, as opposed to training which involves learning from data. Custom chips like Google's TPUs have shown that specialized hardware can offer significant efficiency gains over general-purpose GPUs for inference. OpenAI's move follows a broader industry trend of AI companies designing their own silicon to optimize performance and cost.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/06/24/technology/openai-broadcom-chip-jalapeno.html">OpenAI and Broadcom Unveil Custom A.I. Chip Design - The New York Times</a></li>
<li><a href="https://kelo.com/2026/06/24/openai-unveils-custom-chip-it-designed-with-broadcom-to-boost-its-ai-infrastructure/">OpenAI unveils custom chip it designed with Broadcom to boost its AI infrastructure | KELO-AM</a></li>
<li><a href="https://www.broadcom.com/products/custom-silicon">Custom Silicon</a></li>

</ul>
</details>

**Discussion**: Commenters expressed curiosity about how AI-assisted design accelerated development, with some skepticism about whether it was truly impactful or just marketing. Others discussed the potential of burning model weights into silicon for extreme efficiency, referencing startups like Taalas. The omission of TSMC as manufacturer in the original post was noted and clarified.

**Tags**: `#AI hardware`, `#OpenAI`, `#inference chip`, `#semiconductors`, `#AI industry`

---

<a id="item-2"></a>
## [Comprehensive Guide to Building Agentic AI Systems](https://arxiv.org/abs/2606.24937) ⭐️ 9.0/10

A new arXiv paper titled 'The Hitchhiker's Guide to Agentic AI' provides a comprehensive practitioner's reference covering the full stack of building autonomous AI systems, from transformer foundations to multi-agent coordination and production deployment. This guide bridges the gap between isolated research areas—LLMs, alignment, reasoning, and agentic systems—offering a unified resource for practitioners and researchers. It could accelerate the development of reliable, production-ready agentic AI by providing both theoretical foundations and implementation guidance. The book covers topics including SFT, LoRA, MoE, model compression, inference optimization, RLHF with PPO/DPO/GRPO, chain-of-thought reasoning, agentic training with trajectory-based RL, RAG and Agentic RAG, memory systems, MCP and A2A protocols, and multi-agent architectures.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Agentic AI refers to autonomous systems that can perceive, reason, and act to achieve goals, often using LLMs as their core reasoning engine. Building such systems requires integrating multiple layers: the underlying LLM, alignment techniques to ensure safe behavior, reasoning capabilities, and agent-specific components like tool use, memory, and multi-agent coordination. This guide aims to provide a holistic view of these interconnected layers.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.accubits.com/how-to-fine-tune-llama-2-using-sft-lora/">How to fine-tune LLaMA 2 using SFT, LORA</a></li>
<li><a href="https://yugeten.github.io/posts/2025/01/ppogrpo/">A vision researcher’s guide to some RL stuff: PPO & GRPO - Yuge (Jimmy) Shi</a></li>
<li><a href="https://huggingface.co/blog/LinkedIn/gpt-oss-agentic-rl">Unlocking Agentic RL Training for GPT-OSS: A Practical Retrospective</a></li>

</ul>
</details>

**Tags**: `#agentic AI`, `#LLM`, `#RLHF`, `#RAG`, `#AI systems`

---

<a id="item-3"></a>
## [Wan-Streamer v0.1: Real-Time Multimodal Foundation Model](https://arxiv.org/abs/2606.25041) ⭐️ 9.0/10

Wan-Streamer v0.1 is a native-streaming, end-to-end interactive foundation model that jointly models language, audio, and video in a single Transformer, achieving approximately 200 ms model-side response latency and 550 ms total interaction latency for full-duplex audio-visual communication. This unified architecture eliminates cascaded modules like VAD, ASR, TTS, and video generation, reducing pipeline latency and error accumulation, which marks a paradigm shift for real-time interactive AI systems and could enable more natural human-AI interaction. The model uses block-causal attention for incremental streaming, with streaming units as short as 160 ms at 25 fps, and jointly learns perception, reasoning, generation, response timing, turn management, and cross-modal synchronization without external modules.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Traditional interactive systems rely on separate modules for voice activity detection (VAD), automatic speech recognition (ASR), language modeling, text-to-speech (TTS), and video generation, leading to high latency and error accumulation. Full-duplex interaction allows simultaneous two-way communication, like a natural conversation. Block-causal attention is an attention mechanism that processes input in blocks, enabling streaming generation without waiting for the full sequence.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/block-wise-causal-attention">Block-wise Causal Attention</a></li>
<li><a href="https://www.emergentmind.com/topics/full-duplex-voice-interaction-system">Full-Duplex Voice Interaction Systems</a></li>

</ul>
</details>

**Tags**: `#multimodal AI`, `#real-time interaction`, `#foundation model`, `#audio-visual`, `#Transformer`

---

<a id="item-4"></a>
## [SoK: AI Secure Code Generation Framework](https://arxiv.org/abs/2606.25195) ⭐️ 9.0/10

This SoK paper introduces a three-level framework to measure AI models' understanding and actuation of secure coding principles, revealing knowledge-actuation gaps where models recognize security principles but fail to produce secure code. This work provides a systematic understanding of AI secure code generation, helping researchers and practitioners identify where models fail and how to improve security, which is critical for safe deployment of AI coding tools. The framework was instantiated across models and coding agents on benchmarks covering function-level and full web-application security, showing that secure-coding-principle understanding is a strong predictor of code outcomes, yet knowledge-actuation gaps persist.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: AI code generation tools like GitHub Copilot and ChatGPT are increasingly used, but they often produce insecure code. Existing research has explored various techniques to improve security, but lacked a systematic framework to evaluate and compare them. This SoK paper fills that gap by introducing a principle-centered evaluation approach.

<details><summary>References</summary>
<ul>
<li><a href="https://papers.ssrn.com/sol3/Delivery.cfm/64864869-7e00-47aa-8e34-9521276b4101-MECA.pdf?abstractid=6779013">[PDF] On the Gap Between Declarative Vulnerability Knowledge and ...</a></li>
<li><a href="https://www.veracode.com/blog/ai-coding-tools-security-gaps/">Why AI Coding Tools Are Creating Security Gaps - Veracode</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#code generation`, `#security`, `#LLM`, `#software engineering`

---

<a id="item-5"></a>
## [iLLaDA: 8B Masked Diffusion Model Challenges Autoregressive LLMs](https://arxiv.org/abs/2606.25331) ⭐️ 9.0/10

Researchers introduced iLLaDA, an 8B-parameter masked diffusion language model trained from scratch with fully bidirectional attention on 12T tokens, achieving competitive results with autoregressive models like Qwen2.5 7B on multiple benchmarks. This work demonstrates that masked diffusion models with bidirectional attention can scale to 8B parameters and match autoregressive models, challenging the dominant paradigm in large language model architecture and opening new directions for generative AI. iLLaDA uses a masked diffusion objective throughout pre-training and supervised fine-tuning, with variable-length generation for efficiency and confidence-based scoring for multiple-choice evaluation. It improves over LLaDA by 21.6 points on BBH and 14.9 points on ARC-Challenge for the base model, and 14.5 points on MATH and 16.5 points on HumanEval for the instruct model.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Most large language models today use autoregressive factorization and causal attention, generating tokens one by one in a fixed order. Masked diffusion language models instead iteratively reconstruct text by reversing a noising process over token masks, allowing bidirectional context. iLLaDA is a follow-up to LLaDA, scaling up the masked diffusion approach to 8B parameters and 12T tokens.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/GSAI-ML/iLLaDA-8B-Base">GSAI-ML/iLLaDA-8B-Base - Hugging Face</a></li>
<li><a href="https://louiswang524.github.io/blog/diffusion-llm/">Diffusion Language Models: How They Work, How They Compare to...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#diffusion models`, `#language modeling`, `#AI research`, `#scaling`

---

<a id="item-6"></a>
## [Model-Native Computing Architecture: A Visionary Survey](https://arxiv.org/abs/2606.00288) ⭐️ 9.0/10

This paper proposes treating LLMs as CPUs, KV cache as processor cache, and agent frameworks as operating systems, then uses decades of computer architecture wisdom to design a six-layer Intelligent Computing Architecture (ICA) for model-native systems. This work provides a unified framework that bridges classical computer architecture with modern LLM systems, potentially guiding future system design and research in AI infrastructure. The ICA consists of six functional layers with interface contracts and design axioms, and introduces a dual-plane architecture separating probabilistic execution from deterministic control. The paper also proposes three Amdahl-style design heuristics: Semantic Locality, Context Budget, and Agent Speedup.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Large language models (LLMs) generate text autoregressively, and the KV cache stores intermediate key-value vectors to avoid recomputation, speeding up inference. Computer architecture has long used hierarchical memory and operating systems to manage resources; this paper draws an analogy between those concepts and LLM system components.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/data-science-collective/understanding-the-kv-cache-in-llms-822446560161">Understanding the KV-Cache In LLMs | by Dr. Leon Eversberg | Medium</a></li>
<li><a href="https://lzwjava.github.io/kv-cache-inference-en">Understanding KV Cache in LLM Inference</a></li>
<li><a href="https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms">Understanding and Coding the KV Cache in LLMs from Scratch</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#computer architecture`, `#agent systems`, `#systems research`, `#AI infrastructure`

---

<a id="item-7"></a>
## [Anthropic Accuses Alibaba of Illicitly Extracting Claude AI Capabilities](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

Anthropic has accused Alibaba of illicitly extracting capabilities from its Claude AI model through a process known as model distillation, where a weaker model is trained on the outputs of a stronger one. This dispute highlights growing tensions in the AI industry over intellectual property and competitive practices, potentially influencing future regulations on model distillation and data usage. Chinese resellers reportedly offer Claude tokens at 70-90% below official API prices by pooling accounts and reselling outputs, which may be used as training data for other models.

hackernews · htrp · Jun 24, 19:48 · [Discussion](https://news.ycombinator.com/item?id=48664814)

**Background**: Model distillation is a machine learning technique that transfers knowledge from a large, powerful model to a smaller, more efficient one. Anthropic's Claude is a large language model trained to be helpful, honest, and harmless. The practice of using outputs from one model to train another is common but raises legal and ethical questions when done without permission.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments express irony, noting that Anthropic itself trained Claude on vast internet data without paying creators, and that reverse-engineering competitors is standard industry practice. Some draw parallels to historical tech disputes, like Apple vs. Xerox.

**Tags**: `#AI industry`, `#model distillation`, `#intellectual property`, `#regulation`, `#ethics`

---

<a id="item-8"></a>
## [Qualcomm Acquires Modular to Challenge NVIDIA's CUDA](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

Qualcomm announced the acquisition of AI startup Modular for nearly $4 billion, aiming to build an alternative to NVIDIA's CUDA stack for low-cost AI inference on ARM chips. This move could disrupt NVIDIA's dominance in AI inference by enabling efficient AI workloads on Qualcomm's ARM-based chips, potentially lowering costs and expanding AI deployment in data centers and edge devices. Modular's compiler stack, including the Mojo programming language and MAX platform, allows AI models to run efficiently across different hardware architectures, providing a portable alternative to CUDA.

hackernews · timmyd · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: NVIDIA's CUDA is a proprietary parallel computing platform that has become the de facto standard for AI workloads, locking developers into NVIDIA hardware. Qualcomm's ARM chips are widely used in mobile devices but have limited AI inference capabilities in data centers. Modular, founded by Chris Lattner (creator of LLVM and Swift), develops an open AI-native software stack that decouples AI software from specific hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://semiwiki.com/forum/threads/qualcomm-buys-buzzy-chip-startup-modular-for-nearly-4-billion.25364/">Qualcomm Buys Buzzy Chip Startup Modular for Nearly $4 Billion</a></li>
<li><a href="https://www.reddit.com/r/hardware/comments/1uefqv2/qualcomm_inks_deal_for_ai_startup_modular_to/">Qualcomm inks deal for AI startup Modular to bolster software stack ...</a></li>

</ul>
</details>

**Discussion**: The community expressed mixed feelings: some see it as a strategic move to challenge NVIDIA, while others question whether Modular's technology will deliver on its promises. Comments also noted the timing with China's ARM-based supercomputer and Qualcomm's broader RISC-V investments.

**Tags**: `#AI industry`, `#acquisition`, `#Qualcomm`, `#Modular`, `#AI hardware`

---

<a id="item-9"></a>
## [LLM-Generated Job Apps Obscure Candidate Identity](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 8.0/10

Tom MacWright observes that job applications, portfolios, and GitHub projects are increasingly co-written by LLMs, making candidates generic and impersonal, revealing nothing about their true skills or personality. This trend undermines the hiring process by eroding authenticity, making it harder for employers to assess genuine talent and for candidates to stand out based on real achievements. MacWright notes that even commit messages are purely LLM-generated, and the entire application chain—from resume to portfolio to code—is AI-produced, leaving no trace of the individual's own voice or work.

rss · Simon Willison · Jun 24, 18:13

**Background**: LLMs like GPT-4 can generate convincing text, code, and project documentation. Job seekers increasingly use these tools to automate application materials, but over-reliance can erase personal expression and make candidates indistinguishable.

**Tags**: `#AI & society`, `#careers`, `#personal branding`, `#ethics`, `#hiring`

---

<a id="item-10"></a>
## [Engineering jobs prove most resilient to AI, new data shows](https://techcrunch.com/2026/06/24/ai-was-supposed-to-kill-engineering-jobs-but-new-data-suggests-theyre-the-most-resilient/) ⭐️ 8.0/10

SignalFire's data reveals that engineering headcount is growing faster than most other tech job functions, despite widespread AI-driven layoff narratives. The finding challenges the assumption that AI is replacing engineers. This data-driven counter-narrative matters because it shifts the conversation from fear of job loss to understanding how AI is reshaping roles. Engineers may be more resilient than previously thought, influencing career planning and corporate strategy. SignalFire's head of research Asher Bantock noted that if AI were truly substituting for engineering talent, engineering hiring would be the first to fall during the tech hiring contraction. Instead, engineering roles are growing faster than other functions.

rss · TechCrunch AI · Jun 24, 21:56

**Background**: There has been a widespread narrative that AI, especially generative AI, will automate many engineering tasks and lead to job losses. However, this narrative may be overstated, with some companies using 'AI-washing' to justify layoffs. The SignalFire report provides concrete hiring data to assess the real impact.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/ai-was-supposed-to-kill-engineering-jobs-but-new-data-suggests-theyre-the-most-resilient/">AI was supposed to kill engineering jobs, but new data... | TechCrunch</a></li>
<li><a href="https://newsgab.com/engineering-jobs-most-resilient-to-ai-new-data/">Despite Fears, New Data Finds Engineering Jobs Most Resilient To AI</a></li>
<li><a href="https://www.signalfire.com/blog/signalfire-state-of-talent-report-2025">The SignalFire State of Tech Talent Report - 2025</a></li>

</ul>
</details>

**Discussion**: Comments on the TechCrunch article and related discussions largely agree that the AI-replacing-engineers narrative is overblown. Some developers point out that AI tools increase productivity but do not eliminate the need for skilled engineers, especially those who can ship AI in production.

**Tags**: `#AI & society`, `#employment impact`, `#engineering jobs`, `#data analysis`

---

<a id="item-11"></a>
## [VLMs mimic human visual search via reasoning tokens](https://arxiv.org/abs/2606.25066) ⭐️ 8.0/10

This paper adapts classic visual-search paradigms to vision-language models (VLMs), using the number of reasoning tokens as a proxy for reaction time, and finds that frontier models reproduce key human search signatures. This work bridges cognitive science and AI by providing a behavioral probe for machine visual cognition, revealing both similarities and informative divergences from human search behavior. The study tests four paradigms: feature vs. conjunction search, T-vs-L search, enumeration, and search asymmetry, comparing model reasoning-token counts against human reaction times from a large benchmark.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Visual search paradigms measure how reaction time scales with the number of items, distinguishing parallel pop-out from serial attention-demanding search. Reasoning tokens are internal tokens generated by some LLMs during inference that represent intermediate thinking steps, not visible in the final output.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S2666920X2100014X">sciencedirect.com/science/article/pii/S2666920X2100014X</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC3253411/">Mechanisms and Representations of Language-Mediated Visual...</a></li>
<li><a href="https://aicodereview.cc/blog/input-vs-output-vs-reasoning-tokens-cost/">Input vs Output vs Reasoning Tokens Cost - LLM Pricing Explained</a></li>

</ul>
</details>

**Tags**: `#vision-language models`, `#visual attention`, `#cognitive science`, `#reasoning tokens`, `#AI behavior`

---

<a id="item-12"></a>
## [Efficient Polynomial-Time Algorithms for Asymmetric Shapley Values](https://arxiv.org/abs/2606.25103) ⭐️ 8.0/10

This paper introduces polynomial-time algorithms for computing Asymmetric Shapley Values (ASV) in causal graphs, overcoming the #P-hardness of standard SHAP in certain contexts. This work makes causal-aware model explanations computationally feasible, enabling practical use of ASV for interpretable AI in domains with causal structure. The algorithm runs in polynomial time in the number of equivalence classes of topological orderings, and is exact for rooted directed trees. For arbitrary DAGs, an approximation algorithm using uniform sampling of topological orderings is provided.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Shapley values from cooperative game theory are widely used for feature attribution in ML, but standard SHAP ignores causal structure and is #P-hard to compute in general. Asymmetric Shapley Values (ASV) incorporate causal knowledge via a causal graph, but their computation was previously intractable. This paper bridges that gap.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/1910.06358">[1910.06358] Asymmetric Shapley values: incorporating causal...</a></li>
<li><a href="https://norskregnesentral.github.io/shapr/articles/asymmetric_causal.html">Asymmetric and causal Shapley value explanations • shapr</a></li>
<li><a href="https://proceedings.neurips.cc/paper/2020/file/0d770c496aa3da6d2c3f2bd19e7b9d6b-Paper.pdf">Asymmetric Shapley values: incorporating causal</a></li>

</ul>
</details>

**Tags**: `#AI/ML`, `#Explainability`, `#Causal Inference`, `#Shapley Values`, `#Algorithm`

---

<a id="item-13"></a>
## [Minimum Requirements for Safe Autonomous AI Prescribing](https://arxiv.org/abs/2606.25108) ⭐️ 8.0/10

A new arXiv paper argues that autonomous AI prescribing systems must include calibrated confidence, differentiated uncertainty communication, and inferential transparency, based on a survey of 136 U.S. clinicians. This research provides concrete architectural requirements that could shape future regulation of autonomous AI in healthcare, addressing critical issues of trust, liability, and safety as legislation like H.R. 238 advances. Clinicians preferred a calibrated confidence-based escalation mechanism, a competing-options summary for aleatoric uncertainty, and abstention for epistemic uncertainty; they accepted liability only when inferential transparency allowed substantive judgment.

rss · ArXiv CS.AI · Jun 25, 04:00

**Background**: Autonomous AI systems are moving from advisory roles to directly prescribing medications, as seen in U.S. bill H.R. 238 and Utah's pilot program. Current regulatory guidelines focus on aggregate model performance but lack requirements for per-prediction confidence calibration, distinguishing epistemic vs. aleatoric uncertainty, and decision-time transparency for liability allocation.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2501.12868v1">Exploring the Effect of AI Confidence on Human Self-confidence ... - arXiv</a></li>
<li><a href="https://link.springer.com/article/10.1007/s10994-021-05946-3">Aleatoric and epistemic uncertainty in machine learning: an...</a></li>
<li><a href="https://hdsr.mitpress.mit.edu/pub/aelql9qy">AI Transparency in the Age of LLMs: A Human-Centered Research ...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#healthcare AI`, `#autonomous systems`, `#regulation`, `#uncertainty quantification`

---

<a id="item-14"></a>
## [OpenAI Rolls Out GPT-5.5 Instant Model](https://www.reddit.com/r/OpenAI/comments/1uen1zv/gpt55_instant_now_rolling_out/) ⭐️ 8.0/10

OpenAI has begun rolling out GPT-5.5 Instant, a new incremental update to its language model series, as reported by users on Reddit. This release signals OpenAI's continued rapid iteration in the AI model space, potentially offering improved performance or efficiency over previous versions, which could affect developers and businesses relying on OpenAI's API. The model is named 'GPT-5.5 Instant', suggesting it may be optimized for lower latency or faster inference. No official changelog or benchmark data has been released yet.

reddit · r/OpenAI · /u/imfrom_mars_ · Jun 24, 19:17

**Background**: OpenAI's GPT series has evolved from GPT-3 to GPT-4 and beyond, with each version bringing improvements in reasoning, creativity, and accuracy. 'Instant' variants typically indicate a faster, more cost-effective model tier.

**Discussion**: The Reddit thread shows mixed reactions: some users are excited about potential speed improvements, while others question the lack of transparency and whether this is a minor tweak rather than a major upgrade.

**Tags**: `#AI/ML`, `#OpenAI`, `#GPT-5.5`, `#model release`, `#industry`

---

<a id="item-15"></a>
## [Blogging Can Be Stating the Obvious](https://blog.jim-nielsen.com/2026/blogging-stating-the-obvious/) ⭐️ 7.0/10

Jim Nielsen argues that blogging can be as simple as stating what seems obvious to you but not to others, leveraging the 'curse of knowledge' to provide value. This insight encourages more people to share their knowledge without fear of redundancy, potentially enriching the blogging ecosystem with diverse perspectives. The post highlights that the 'curse of knowledge' makes experts assume others share their understanding, so stating the obvious can be valuable for newcomers.

hackernews · Curiositry · Jun 24, 23:46 · [Discussion](https://news.ycombinator.com/item?id=48666927)

**Background**: The 'curse of knowledge' is a cognitive bias where individuals with specialized knowledge overestimate how much others know. In blogging, this bias often prevents experts from writing about basic topics, assuming everyone already knows them. However, for many readers, especially beginners, these 'obvious' insights are new and helpful.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Curse_of_knowledge">Curse of knowledge</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with the premise, sharing personal experiences where stating the obvious helped others. Some note that there is always a new cohort of people who haven't heard the information before, making such posts valuable.

**Tags**: `#blogging`, `#personal branding`, `#writing`, `#knowledge sharing`, `#curse of knowledge`

---

<a id="item-16"></a>
## [NVIDIA's 45°C Cooling Slashes Data Center Water Use](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA announced a 45°C liquid cooling design for AI data centers that uses direct-to-chip cooling with warm water, reducing water consumption to near zero by enabling heat rejection via dry coolers instead of evaporative cooling towers. This innovation addresses the massive water footprint of AI data centers—conventional cooling can use 2.6 million gallons per megawatt annually—and opens the door to waste heat reuse for district heating, benefiting both operators and local communities. The design uses single-phase direct liquid cooling with a supply temperature of 45°C (113°F), which is higher than typical norms and allows dry coolers to operate using ambient air without energy-intensive chillers. NVIDIA's Vera Rubin NVL72 is one product supporting this architecture.

hackernews · nitin_flanker · Jun 24, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48660178)

**Background**: Data centers generate enormous heat from high-density AI compute, traditionally requiring energy-hungry chillers or water-intensive evaporative cooling. Liquid cooling directly removes heat from chips, and higher coolant temperatures improve efficiency and enable heat reuse. District heating networks distribute hot water from a central source to buildings for space heating.

<details><summary>References</summary>
<ul>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45°C Liquid Cooling Design for AI Data Centers</a></li>
<li><a href="https://www.techbuzz.ai/articles/nvidia-s-45-c-liquid-cooling-redefines-ai-data-center-energy">NVIDIA's 45°C Liquid Cooling Redefines AI Data Center Energy</a></li>
<li><a href="https://www.networkworld.com/article/4149069/why-ai-rack-densities-make-liquid-cooling-nonnegotiable.html">Why AI rack densities make liquid cooling... | Network World</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the potential for district heating synergy, noting that 45°C is workable for heating loops and could provide millions in annual community value. Some questioned what makes this design innovative compared to existing liquid cooling, while others asked about climate constraints and efficiency correlations with outside temperatures.

**Tags**: `#data center`, `#cooling`, `#energy efficiency`, `#NVIDIA`, `#infrastructure`

---

<a id="item-17"></a>
## [PR Spam on GitHub Echoes Early Email Spam](https://www.greptile.com/blog/prs-on-openclaw) ⭐️ 7.0/10

A blog post by Greptile draws a parallel between the rise of spammy pull requests on GitHub and the email spam epidemic of the early 2000s, arguing that open source maintainers now face a similar deluge of low-quality, AI-generated contributions. This comparison highlights a growing threat to open source sustainability, as maintainers waste time triaging spam instead of reviewing genuine contributions, potentially driving burnout and reducing project health. The article notes that spam PRs often include AI-generated code, SEO link injection, or Hacktoberfest-related noise, and suggests that reputation systems similar to email's sender scores could help mitigate the problem.

hackernews · dakshgupta · Jun 24, 14:32 · [Discussion](https://news.ycombinator.com/item?id=48660579)

**Background**: Open source projects on GitHub rely on pull requests for contributions, but the rise of generative AI has made it easy to produce large volumes of low-effort code. Without effective filtering, maintainers must manually review each PR, a task that becomes unsustainable at scale.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/PThorpe92/fossier">GitHub - PThorpe92/fossier: Vouch-compatible PR-spam reduction...</a></li>
<li><a href="https://hugovk.dev/blog/2026/gh-triage/">A CLI to fight GitHub spam · Hugo van Kemenade</a></li>
<li><a href="https://mansoorbarri.medium.com/how-can-github-fix-spamming-14e9bab59294">How Can GitHub Fix Spamming?. Background | by Mansoor... | Medium</a></li>

</ul>
</details>

**Discussion**: Commenters noted that GitHub recently added configurable PR limits for maintainers, but some argued that email spam solutions relied on server-level reputation, which doesn't directly apply to individual GitHub users. Others expressed interest in reputation infrastructure and unsubscribe lists akin to uBlock Origin.

**Tags**: `#open source`, `#spam`, `#GitHub`, `#maintainer tools`, `#tech ethics`

---

<a id="item-18"></a>
## [Google Adds Computer Use to Gemini 3.5 Flash](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 7.0/10

Google has integrated computer use capabilities directly into the Gemini 3.5 Flash model, allowing the AI to interact with desktop applications and perform agentic tasks. This feature was previously only available as a separate Gemini 2.5 model. This advancement enables AI to automate complex workflows involving multiple software tools, potentially boosting productivity. However, community feedback highlights significant reliability and safety concerns that could limit real-world adoption. The computer use tool is now a built-in feature of Gemini 3.5 Flash, delivering improved performance for agentic tasks. Users have reported issues such as the AI running destructive commands like 'git reset --hard' and giving up on simple data extraction tasks.

hackernews · swolpers · Jun 24, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48662999)

**Background**: Computer use refers to an AI model's ability to directly control a computer's graphical user interface, similar to a human using a mouse and keyboard. This is part of a broader trend toward AI agents that can autonomously perform multi-step tasks across different applications.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/">Introducing computer use in Gemini 3.5 Flash</a></li>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3.5 Flash — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/generate-content/whats-new-gemini-3.5">What's new in Gemini 3.5 Flash | Gemini Generate Content API...</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism and frustration: users report the AI making destructive mistakes (e.g., running 'git reset --hard') and failing at simple tasks like extracting a table from a PDF. Some criticize the term 'computer use' as vague, and others note that Gemini 3.5 Flash is outperformed by competitors in benchmarks.

**Tags**: `#AI/ML`, `#Gemini`, `#AI agent`, `#product review`, `#AI safety`

---

<a id="item-19"></a>
## [Nub: All-in-one Node.js toolkit mimicking Bun's DX](https://github.com/nubjs/nub) ⭐️ 7.0/10

Colin McDonnell released Nub, an all-in-one toolkit for Node.js that adds transpilation via the oxc compiler, module resolution hooks, and polyfills for APIs like Worker and Temporal through a --require preload hook, aiming to replicate Bun's developer experience. Nub brings Bun-like developer experience to Node.js without switching runtimes, potentially improving productivity for Node.js developers who want modern features like TypeScript transpilation and built-in polyfills. Nub uses a --require preload hook rather than --import, which raises questions about ESM support nuances like top-level await. The transpiler is powered by oxc, a high-performance Rust-based tool, packaged as a Node-API add-on.

hackernews · colinmcd · Jun 24, 14:14 · [Discussion](https://news.ycombinator.com/item?id=48660267)

**Background**: Bun is a fast all-in-one JavaScript runtime that includes a transpiler, package manager, and test runner. Node.js lacks built-in TypeScript support and certain modern APIs, requiring third-party tools. Nub fills this gap by augmenting Node.js with similar capabilities via hooks.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/oxc-project/oxc">oxc-project/oxc: ⚓ A collection of high-performance JavaScript tools.</a></li>

</ul>
</details>

**Discussion**: The community is positive, with users praising the idea and speed. One user migrated their entire monorepo with zero issues. However, there are technical questions about ESM support due to the use of --require instead of --import, and some wonder why a transpiler is needed given Node's recent TypeScript support.

**Tags**: `#Node.js`, `#Bun`, `#developer tools`, `#TypeScript`, `#open source`

---

<a id="item-20"></a>
## [Europe pushes back on US chip war restrictions](https://techcrunch.com/2026/06/24/europe-is-pushing-back-on-washingtons-chip-war/) ⭐️ 7.0/10

Europe is resisting the US-led chip war against China, with ASML CEO Christophe Fouquet noting that proposed US legislation (the MATCH Act) would ban sales of older-generation deep ultraviolet (DUV) lithography tools to China, which are currently permitted. This pushback highlights growing transatlantic tensions over semiconductor export controls, which could disrupt global chip supply chains and impact the availability of AI hardware, as DUV tools are critical for producing mature-node chips used in various industries. The MATCH Act, a bipartisan US bill, aims to close loopholes by restricting all ASML DUV shipments to China, which currently account for about a fifth of ASML's expected revenue. ASML argues that these older tools, first shipped a decade ago, are not cutting-edge and should remain exportable.

rss · TechCrunch AI · Jun 25, 00:08

**Background**: The US has been tightening export controls on advanced semiconductor technology to China, citing national security concerns. ASML is the world's leading supplier of lithography systems, essential for chip manufacturing. EUV (extreme ultraviolet) tools are the most advanced, while DUV tools are older but still widely used for less advanced chips. The MATCH Act would extend restrictions to DUV tools, which are currently not fully banned.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/19/the-us-says-asmls-top-chip-tool-may-be-in-china-asml-says-it-isnt/">The US says ASML's top chip tool may be in China, but... | TechCrunch</a></li>
<li><a href="https://overcentral.com/en/netherlands-opposes-match-act-asml-china/">Netherlands Opposes US Bill Restricting ASML Chip Sales to China</a></li>
<li><a href="https://www.manufacturingdive.com/news/lawmakers-push-restrictions-chipmaking-equipment-exports-china-match-act/816945/">Lawmakers push to restrict chipmaking... | Manufacturing Dive</a></li>

</ul>
</details>

**Tags**: `#chip war`, `#semiconductors`, `#geopolitics`, `#AI hardware`, `#Europe`

---

<a id="item-21"></a>
## [Google loses two more top AI researchers to Anthropic](https://techcrunch.com/2026/06/24/ai-researchers-continue-to-leave-google-for-its-rivals/) ⭐️ 7.0/10

Top AI researchers Jonas Adler and Alexander Pritzel are leaving Google for Anthropic, following earlier departures of Noam Shazeer and John Jumper. This trend signals a talent drain from Google to rivals like Anthropic, potentially shifting the competitive balance in AI development. Adler worked on Google's AI coding efforts and Pritzel was involved in training AI systems; both were key contributors to DeepMind and Gemini.

rss · TechCrunch AI · Jun 24, 21:42

**Background**: Google has long been a leader in AI research, but recent high-profile departures to startups like Anthropic highlight growing competition for talent. Anthropic, founded by former OpenAI employees, focuses on safe AI development.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/ai-researchers-continue-to-leave-google-for-its-rivals/">AI researchers continue to leave Google for its rivals - TechCrunch</a></li>
<li><a href="https://mezha.net/eng/bukvy/ce3ab401_jonas_adler_and/">Jonas Adler and Alexander Pritzel leave Google for Anthropic, raising ...</a></li>

</ul>
</details>

**Discussion**: On Reddit, users expressed concern about Google's ability to retain talent, with some noting that Anthropic's focus on safety may attract researchers seeking more impactful work.

**Tags**: `#AI industry`, `#talent flow`, `#Google`, `#Anthropic`

---

<a id="item-22"></a>
## [Companies Shift from Tokenmaxxing to Token Rationing](https://techcrunch.com/2026/06/24/companies-are-scrambling-to-stop-employees-from-maxing-out-ai-budgets-with-small-tasks/) ⭐️ 7.0/10

Companies are moving from allowing unlimited AI usage to implementing token rationing systems as employees exhaust budgets on trivial tasks, marking the end of the 'tokenmaxxing' era. This shift highlights a critical challenge in enterprise AI adoption: balancing productivity gains with cost control. It may lead to more efficient AI usage but also risks stifling innovation if rationing is too restrictive. Tokenmaxxing refers to maximizing token consumption as a productivity metric, but critics argue it leads to wasteful usage and higher costs. Token rationing aims to curb this by limiting per-user or per-task token allowances.

rss · TechCrunch AI · Jun 24, 20:09

**Background**: AI services charge per token, which represents units of processing effort. Some employees began treating high token usage as a badge of productivity, a practice called 'tokenmaxxing'. This led to spiraling costs for companies, prompting a move toward rationing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Token_maxxing">Token maxxing</a></li>
<li><a href="https://www.techbuzz.ai/articles/enterprise-ai-s-token-rationing-era-begins-as-costs-spiral">Enterprise AI's Token Rationing Era Begins as Costs... | The Tech Buzz</a></li>

</ul>
</details>

**Tags**: `#AI industry`, `#enterprise AI`, `#AI adoption`, `#cost management`, `#AI ethics`

---

<a id="item-23"></a>
## [OpenMontage: First Open-Source Agentic Video Production System](https://github.com/calesthio/OpenMontage) ⭐️ 7.0/10

OpenMontage has been released as the world's first open-source, agentic video production system, featuring 12 pipelines, 52 tools, and over 500 agent skills. This project transforms AI coding assistants into full video production studios, democratizing professional-grade video creation and enabling automated end-to-end workflows. The system provides modular video pipelines for scripting, composition, animation, and rendering, with real quality enforcement orchestrated by an AI assistant.

ossinsight · calesthio · Jun 25, 04:06

**Background**: Traditional AI video tools typically generate a single clip from a prompt, lacking the structured, multi-step process of professional production. OpenMontage automates the entire pipeline that a real production team follows, using an agentic approach where an AI assistant orchestrates multiple tools and skills.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/calesthio/OpenMontage">GitHub - calesthio/OpenMontage: World's first open-source, agentic...</a></li>
<li><a href="https://topai.tools/t/openmontage">OpenMontage - AI Video Tool</a></li>
<li><a href="https://zread.ai/calesthio/OpenMontage">Overview | calesthio/OpenMontage | Zread</a></li>

</ul>
</details>

**Tags**: `#AI/ML`, `#open-source`, `#agent`, `#video production`, `#Python`

---

<a id="item-24"></a>
## [Fund Aims to End All Respiratory Infections](https://blog.interceptfund.com/p/ending-respiratory-infections) ⭐️ 6.0/10

A $500 million philanthropic fund has been launched with the ambitious goal of ending all respiratory infections through research and startup investments. If successful, this could dramatically reduce the global burden of respiratory illnesses, which affect billions annually, but the feasibility and resource allocation are hotly debated. The fund is managed by Intercept Fund and focuses on both scientific research and supporting startups. Critics question whether $500 million is sufficient given the complexity of respiratory viruses.

hackernews · EthanFantl · Jun 25, 01:14 · [Discussion](https://news.ycombinator.com/item?id=48667588)

**Background**: Respiratory infections like the common cold, flu, and COVID-19 cause millions of deaths and billions of illnesses each year. Current treatments are often symptomatic, and vaccines exist for only a few pathogens. A universal solution would require breakthroughs in virology and immunology.

**Discussion**: Comments show mixed sentiment: some share personal tragedies and hope for success, while others doubt the feasibility and argue that simpler public health measures (e.g., sugar taxes) could achieve more with less money.

**Tags**: `#health`, `#philanthropy`, `#biotech`, `#public health`

---

<a id="item-25"></a>
## [MDN Browser Compat Data Converted to SQLite](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 6.0/10

Simon Willison converted Mozilla's mdn/browser-compat-data repository into a ~66MB SQLite database using AI-generated scripts from Claude Code for Web (Opus 4.8) and Codex Desktop (GPT-5.5), and made it accessible via GitHub CDN with open CORS headers. This makes MDN's comprehensive browser compatibility data easily queryable via SQL, enabling developers to quickly check feature support across browsers without parsing JSON. It also demonstrates a practical workflow for using AI coding tools to automate data conversion and deployment. The database is built via a GitHub Actions workflow that force-pushes the SQLite file to an orphan 'db' branch, enabling direct download with open CORS headers. Users can explore the data interactively using Datasette Lite.

rss · Simon Willison · Jun 24, 23:59

**Background**: MDN (Mozilla Developer Network) maintains a browser-compat-data repository that tracks which web platform features are supported in which browser versions. Simon Willison is a well-known developer who created sqlite-utils and Datasette, tools for easily creating and exploring SQLite databases. The MDN MCP server, announced in June 2026, provides AI agents with programmatic access to MDN data.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server - MDN Web Docs</a></li>
<li><a href="https://sqlite-utils.datasette.io/">sqlite-utils</a></li>

</ul>
</details>

**Tags**: `#browser compatibility`, `#SQLite`, `#AI coding tools`, `#MDN`, `#data tooling`

---

<a id="item-26"></a>
## [Cerebras stock plunges after earnings, CEO blames margin misunderstanding](https://techcrunch.com/2026/06/24/cerebras-stock-plunges-after-earnings-as-ceo-says-margin-outlook-was-misunderstood/) ⭐️ 6.0/10

Cerebras stock dropped sharply after its first earnings report as a public company, following a forecast of narrower gross margins in its core business. CEO Andrew Feldman clarified that investors misunderstood the margin outlook, partly due to a need to rent back equipment from a major customer. This event highlights the intense competition in the AI chip market, where Cerebras's projected margins (38-41%) are far below those of Nvidia (mid-70%) and AMD (mid-50%). It underscores the challenges new entrants face in achieving profitability while scaling their business. Cerebras forecast full-year 2026 core gross margins of 38% to 41%, down from 47% in Q1 2026, and Q2 margins of 36% to 38%. The company beat revenue estimates but the margin outlook spooked investors.

rss · TechCrunch AI · Jun 24, 22:41

**Background**: Cerebras is an AI chipmaker known for its wafer-scale engine, which is designed for ultra-fast AI training. The company went public recently and this was its first earnings report. Gross margin is a key profitability metric, and lower margins relative to competitors like Nvidia and AMD raise concerns about Cerebras's competitive position.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/cerebras-stock-plunges-after-earnings-as-ceo-says-margin-outlook-was-misunderstood/">Cerebras stock plunges after earnings as CEO says margin outlook...</a></li>
<li><a href="https://au.finance.yahoo.com/news/cerebras-revenue-nearly-doubles-margin-132812966.html">Cerebras Revenue Nearly Doubles but Margin Outlook Sends Shares...</a></li>
<li><a href="https://particle.news/story/cerebras-beats-revenue-estimates-but-flags-much-lower-margins-than-rivals">Cerebras Beats Revenue Estimates but Flags Much Lower Margins...</a></li>

</ul>
</details>

**Tags**: `#AI industry`, `#company strategies`, `#Cerebras`, `#stock market`

---