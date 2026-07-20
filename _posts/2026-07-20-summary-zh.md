---
layout: default
title: "Horizon Summary: 2026-07-20 (ZH)"
date: 2026-07-20
lang: zh
---

> 从 31 条内容中筛选出 13 条重要资讯。

---

1. [泄露邮件揭示 OpenAI 开源策略](#item-1) ⭐️ 9.0/10
2. [保龄球馆老板用 1600 美元的 ESP32 替代 12 万美元系统](#item-2) ⭐️ 8.0/10
3. [Claude Code 采用 Rust 重写的 Bun](#item-3) ⭐️ 8.0/10
4. [阿里巴巴发布 Qwen 3.8，2.4 万亿参数开源大模型](#item-4) ⭐️ 8.0/10
5. [AI 狂热正在摧毁全球决策能力](#item-5) ⭐️ 8.0/10
6. [研究发现 AI 建议降低准确性，增加过度自信](#item-6) ⭐️ 7.0/10
7. [开发者烧光 Token 只为学会节省 Token](#item-7) ⭐️ 7.0/10
8. [苹果诉讼威胁 OpenAI 的硬件与 IPO 计划](#item-8) ⭐️ 7.0/10
9. [非营利组织 Current AI 打造免费通用 AI 生态系统](#item-9) ⭐️ 7.0/10
10. [OpenAI 高管称开源权重模型主导地位为“AI 共产主义”](#item-10) ⭐️ 7.0/10
11. [英伟达开放权重或使开源模型超越闭源](#item-11) ⭐️ 7.0/10
12. [浮游植物碳移除：自然实验显示前景](#item-12) ⭐️ 6.0/10
13. [Ollama 融资 8800 万美元，但社区批评其性能不佳](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [泄露邮件揭示 OpenAI 开源策略](https://simonwillison.net/2026/Jul/20/sam-altman/#atom-everything) ⭐️ 9.0/10

一封 2022 年 Sam Altman 发给 OpenAI 董事会的泄露邮件显示，计划发布一个具备 GPT-3 能力的开源模型，以阻止竞争对手并限制新进入者。 这一披露提供了对 OpenAI 战略思维的罕见洞察，表明开源模型被视为一种竞争策略而非纯粹利他行为。这引发了关于开源 AI 发布背后动机的伦理问题。 这封日期为 2022 年 10 月 1 日的邮件在 2026 年 Musk 诉 Altman 案中被曝光。Altman 特别提到希望在 Stability AI 或其他公司之前发布该模型。

rss · Simon Willison · 7月20日 03:47

**背景**: GPT-3 是一个拥有 1750 亿参数的大型语言模型，能够生成类似人类的文本。开源 AI 模型的能力日益增强，有些以更低成本媲美专有模型。Stability AI 以其开源图像生成模型 Stable Diffusion 而闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-3">GPT-3 - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stability_AI">Stability AI</a></li>
<li><a href="https://www.teachfloor.com/blog/gpt-3">What Is GPT-3? Architecture, Capabilities, and Use Cases</a></li>

</ul>
</details>

**标签**: `#open-source`, `#openai`, `#sam-altman`, `#ai-ethics`, `#ai-industry`

---

<a id="item-2"></a>
## [保龄球馆老板用 1600 美元的 ESP32 替代 12 万美元系统](https://news.ycombinator.com/item?id=48968606) ⭐️ 8.0/10

一位保龄球馆老板使用 ESP32 微控制器、ESPNow 网状网络和树莓派构建了名为 OpenLaneLink 的开源计分系统，每对球道成本约 200 美元，而商业替换通常需要 8 万到 12 万美元。 该项目展示了现代低成本嵌入式系统如何替代利基行业中昂贵的传统基础设施，可能为小企业节省数万美元并减少供应商锁定。 该系统使用 ESP32 节点，通过 ESPNow 星型拓扑连接传感器和继电器，并配有 RS485 有线回退方案，树莓派作为球道计算机运行 Redis 和状态机。整个技术栈计划开源。

hackernews · section33 · 7月19日 14:41

**背景**: 保龄球计分系统很复杂，集成了基于摄像头的球瓶检测、球速测量以及控制排瓶机和回球系统。商业系统是专有的且昂贵，一个 8 球道的场馆通常要花费超过 10 万美元，替换部件每对球道要 4000 美元。ESP32 是一种低成本、支持 Wi-Fi 和蓝牙的微控制器，广泛用于物联网项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.espressif.com/en/products/socs/esp32">ESP32 Wi-Fi & Bluetooth SoC | Espressif Systems</a></li>
<li><a href="https://en.wikipedia.org/wiki/Automatic_scorer">Automatic scorer - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Pinsetter">Pinsetter - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了类似的使用现代技术改造旧系统的经验，例如用 1970 年代的 Intel 微控制器改造迷你保龄球道，以及用现代运动控制改造大型机床。一位评论者兴奋地表示计划添加 LED 追逐灯和由球运动触发的 DMX 控制激光秀。

**标签**: `#embedded systems`, `#cost reduction`, `#engineering`, `#retrofit`, `#ESP32`

---

<a id="item-3"></a>
## [Claude Code 采用 Rust 重写的 Bun](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/#atom-everything) ⭐️ 8.0/10

Claude Code v2.1.181（6 月 17 日发布）现在使用 Rust 移植版的 Bun，在 Linux 上启动速度提升了 10%。通过检查二进制文件中的 Rust 源文件和 Bun 版本字符串（1.4.0，高于公开版本）确认了这一变化。 这一转变表明，对性能敏感的 AI 编码工具可以从 Rust 重写运行时中受益，并凸显了 Anthropic 收购 Bun 母公司 Oven 后的战略。它还引发了关于 Zig 与 Rust 工程权衡以及 AI 在代码重写中作用的讨论。 Rust 移植版的 Bun 尚未作为稳定版本公开发布；Claude Code 附带了一个预览版（v1.4.0），可通过 Bun canary 构建访问。原始 Bun 是用 Zig 编写的，而 Rust 重写是在 AI 辅助下完成的，在一个月内合并了超过 100 万行的 PR。

rss · Simon Willison · 7月19日 03:54 · [社区讨论](https://news.ycombinator.com/item?id=48966569)

**背景**: Bun 是一个快速的全能 JavaScript 运行时、打包器和包管理器，最初用 Zig 编写。Claude Code 是 Anthropic 的 AI 编码助手，运行在终端中。从 Zig 重写为 Rust 旨在利用 Rust 的自动内存管理来提高内存安全性并减少错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些人称赞技术改进和 Rust 的安全性优势，而另一些人则批评重写过程中的沟通问题，并质疑为什么一个 TUI 需要 JavaScript 运行时。还有人担心 Bun 的治理以及悄然偏离原始 Zig 版本的问题。

**标签**: `#AI coding tools`, `#Claude Code`, `#Bun`, `#Rust`, `#performance`

---

<a id="item-4"></a>
## [阿里巴巴发布 Qwen 3.8，2.4 万亿参数开源大模型](https://twitter.com/Alibaba_Qwen/status/2078759124914098291) ⭐️ 8.0/10

阿里巴巴宣布推出 Qwen 3.8，一个拥有 2.4 万亿参数的开源权重大型语言模型，声称其性能仅次于 Fable 5。预览版已通过阿里巴巴的 Token 计划以 10%的标准价格提供。 此次发布加剧了开源大模型领域的竞争，特别是与 Moonshot AI 的 Kimi K3（2.8 万亿参数）的竞争，可能加速创新并使强大模型更易获取。开源权重的方式允许开发者本地运行模型，增强了隐私性和定制能力。 Qwen 3.8 拥有 2.4 万亿参数，而 Kimi K3 拥有 2.8 万亿参数并采用名为 Kimi Delta Attention 的混合线性注意力机制。阿里巴巴尚未公布 Qwen 3.8 的基准测试分数，开源权重预计很快发布。

hackernews · nh43215rgb · 7月19日 08:44 · [社区讨论](https://news.ycombinator.com/item?id=48966120)

**背景**: 大型语言模型（LLM）是在海量文本数据上训练的人工智能系统，能够生成类似人类的文本。参数数量是模型能力的粗略衡量标准，万亿级参数表示极大的模型。开源权重模型允许任何人下载并运行，促进了社区创新和透明度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://the-decoder.com/alibabas-qwen-takes-on-kimi-k3-with-open-weight-qwen-3-8-says-model-is-second-only-to-fable-5/">Alibaba's Qwen takes on Kimi K3 with open-weight Qwen 3.8, says model is "second only to Fable 5"</a></li>
<li><a href="https://techsy.io/en/blog/qwen-3-8">Qwen3.8: 2.4T Parameters, Open Weights, No Benchmarks</a></li>
<li><a href="https://x.com/Alibaba_Qwen/status/2078759124914098291">Qwen on X: "Qwen3.8 is launching and going open-weight soon!🌐 With a massive 2.4T parameters, this model is continuously evolving. We believe it’s one of the most powerful model available today, compatible to leading frontier AI models , second only to Fable 5. You don't have to wait to https://t.co/JS3ID73IYS" / X</a></li>

</ul>
</details>

**社区讨论**: 社区情绪复杂：一些用户欢迎竞争并期待用于本地使用的较小变体，而另一些用户则批评 Qwen 3.7 Pro 在软件工程任务中不可用。还有用户期待开源权重发布以避免 API 成本和访问限制。

**标签**: `#AI/ML`, `#open-source LLM`, `#Qwen`, `#model competition`, `#Alibaba`

---

<a id="item-5"></a>
## [AI 狂热正在摧毁全球决策能力](https://simonwillison.net/2026/Jul/19/ai-mania/#atom-everything) ⭐️ 8.0/10

Nik Suresh 发表了一篇批判性文章，揭露 AI 狂热如何导致大企业做出非理性、无知的决策，其中包含高管从未使用过 AI 工具却推动 AI 战略的轶事。 这篇文章突出了一个危险趋势：AI 炒作压倒了基于证据的决策，可能浪费数十亿美元并损害组织信誉。 一位高管承认在为一营收超 20 亿美元的公司制定以 AI 为中心的战略之前，从未使用过 ChatGPT 或任何 AI 工具；另一名工程师将 Go 仓库重写为 Zig，只是为了在 token 排行榜上显得活跃。

rss · Simon Willison · 7月19日 05:06

**背景**: 这篇文章评论了企业环境中普遍的 AI 炒作现象，高管们感到有压力去采用 AI，却不了解其能力或局限性。它通过咨询师和工程师的匿名轶事，说明了当前决策的荒谬性。

**社区讨论**: Hacker News 上的讨论（文章中有链接）可能包含赞同和更多轶事，但此处未提供具体评论。

**标签**: `#AI & society`, `#AI ethics`, `#corporate decision-making`, `#AI hype`, `#critical analysis`

---

<a id="item-6"></a>
## [研究发现 AI 建议降低准确性，增加过度自信](https://thenextweb.com/news/ai-advice-suppresses-critical-thinking-wrong-answers-study) ⭐️ 7.0/10

一项研究发现，当人们从已知会给出错误答案的 AI 系统获得建议时，他们的准确性降低，但对自己的回答更加自信，这表明 AI 建议可能抑制批判性思维。 这凸显了随着 AI 工具普及可能带来的社会风险：用户可能过度依赖 AI 而丧失批判性思维能力，导致对错误答案更加自信。 该研究使用了一个研究人员已知会在某些问题上给出错误答案的 LLM，参与者如果不确定可以选择不回答。结果显示，当 AI 建议可用时，准确性下降而自信度上升。

hackernews · rbanffy · 7月19日 21:18 · [社区讨论](https://news.ycombinator.com/item?id=48971738)

**背景**: 批判性思维是指独立评估信息而非盲目接受。随着 ChatGPT 等 AI 助手变得普遍，人们担心人们可能停止批判性思考，仅仅信任 AI 的输出，即使这些输出是错误的。

**社区讨论**: 社区评论批评了该研究的方法论，认为它测试的是通用的建议提供行为，而非 AI 特有的问题。一位评论者指出，该研究让参与者访问一个已知会给出错误答案的 LLM，这类似于测试来自任何来源的坏建议的效果，而非 AI 独有的影响。

**标签**: `#AI & society`, `#critical thinking`, `#AI safety`, `#study critique`

---

<a id="item-7"></a>
## [开发者烧光 Token 只为学会节省 Token](https://quesma.com/blog/custom-deep-research-pipeline/) ⭐️ 7.0/10

Quesma 的一位开发者构建了一个自定义深度研究管道，用于调查其 AI 代理管道为何消耗过多 Token，结果发现管道本身才是主要成本来源。 这种元分析凸显了 AI 管道中 Token 优化的讽刺性和实际挑战，为开发者在构建代理系统时降低成本提供了见解。 该管道使用更便宜的模型进行初步探索，然后将结果逐步传递给更强大的模型，深度研究步骤被保留为最后阶段，以最小化 Token 浪费。

hackernews · bkotrys · 7月19日 12:01 · [社区讨论](https://news.ycombinator.com/item?id=48967355)

**背景**: Token 优化对于 LLM 管道的成本效率至关重要，因为每次 API 调用都会消耗 Token 并产生费用。许多开发者使用多阶段管道，让廉价模型处理早期任务，昂贵模型优化输出，但若设计不当，管道本身可能成为主要的 Token 消耗源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://quesma.com/blog/custom-deep-research-pipeline/">I burned all my tokens researching how to save tokens - Quesma Blog</a></li>
<li><a href="https://tianpan.co/blog/2026-04-11-hidden-token-tax-production-llm-pipelines">The Hidden Token Tax: How Overhead Silently Drains Your LLM...</a></li>
<li><a href="https://myengineeringpath.dev/genai-engineer/deep-research/">Deep Research AI Agent — Build Your Own... | MyEngineeringPath</a></li>

</ul>
</details>

**社区讨论**: 评论者指出了用 AI 优化 AI 成本的讽刺性，有人评论说答案就是“深度研究管道本身”。其他人建议用本地模型处理 90%的任务，将前沿模型留给剩余的 10%，还有人强调从廉价模型开始，逐步使用更强大的模型。

**标签**: `#AI/ML`, `#LLM`, `#token optimization`, `#AI pipelines`, `#cost efficiency`

---

<a id="item-8"></a>
## [苹果诉讼威胁 OpenAI 的硬件与 IPO 计划](https://techcrunch.com/2026/07/19/can-an-apple-lawsuit-derail-openais-hardware-plans/) ⭐️ 7.0/10

TechCrunch 的 Equity 播客讨论苹果起诉 OpenAI 窃取硬件商业机密是否可能破坏 OpenAI 开发消费设备及上市的计划。 该诉讼可能严重推迟 OpenAI 的硬件雄心与 IPO 时间表，影响 AI 硬件竞争格局及投资者对 OpenAI 未来的信心。 苹果的诉讼特别针对 OpenAI 的消费硬件计划，包括代号为'Sweetpea'的设备，并要求阻止 OpenAI 使用争议信息并归还苹果材料。

rss · TechCrunch AI · 7月19日 19:24

**背景**: 以 GPT-4 等 AI 模型闻名的 OpenAI 据报道计划进入硬件市场，推出多款设备，并与富士康合作生产。苹果的诉讼指控 OpenAI 和 Jony Ive 的公司窃取了与硬件设计相关的商业机密。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/07/10/technology/apple-openai-lawsuit.html">Apple Sues OpenAI, Accusing It of Stealing Company Secrets</a></li>
<li><a href="https://dallasexpress.com/business-markets/apple-says-openai-hardware-push-relied-on-stolen-trade-secrets/">Apple Says OpenAI Hardware Push Relied On Stolen Trade Secrets</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#OpenAI`, `#Apple`, `#regulation`, `#hardware`

---

<a id="item-9"></a>
## [非营利组织 Current AI 打造免费通用 AI 生态系统](https://techcrunch.com/2026/07/19/nonprofit-current-ai-is-racing-to-build-the-world-wide-web-of-ai-free-for-all/) ⭐️ 7.0/10

非营利组织 Current AI 正在开发一个包容性的跨设备 AI 聊天平台，旨在创建一个免费、人人可及的 AI 生态系统，不落下任何文化。 这一举措可能使 AI 访问民主化，确保多元文化和 underserved 社区受益于 AI 进步，而非被少数营利公司主导。 Current AI 在跨设备和 AI 聊天方面取得了显著进展，但具体技术细节或发布日期尚未披露。

rss · TechCrunch AI · 7月19日 14:00

**背景**: Current AI 是一个非营利组织，专注于构建尊重并包容所有文化的 AI。其目标是创建一个类似万维网的开放、免费 AI 生态系统，任何人都可以不受设备或背景限制地访问 AI 工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/19/nonprofit-current-ai-is-racing-to-build-the-world-wide-web-of-ai-free-for-all/">Nonprofit Current AI is racing to build the World Wide Web of AI, free for all | TechCrunch</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#AI & society`, `#open-source`, `#nonprofit`

---

<a id="item-10"></a>
## [OpenAI 高管称开源权重模型主导地位为“AI 共产主义”](https://www.reddit.com/r/OpenAI/comments/1v0nx8b/openai_head_of_strategic_futures_says_openweight/) ⭐️ 7.0/10

OpenAI 战略未来负责人声称，开源权重 AI 模型的主导地位类似于共产主义，引发了关于开源 AI 角色和风险的辩论。 OpenAI 高管的这一挑衅性表述凸显了开源与专有 AI 开发之间日益紧张的关系，将影响行业战略和监管讨论。 开源权重模型允许任何人下载并使用核心组件，但 OpenAI 高管警告称，不受限制的主导地位可能导致类似于共产主义相关的风险。

reddit · r/OpenAI · /u/AloneCoffee4538 · 7月19日 11:19

**背景**: 开源权重模型是核心组件公开发布的 AI 模型，允许广泛访问和定制。“AI 共产主义”一词被用作隐喻，批评免费、无限制访问强大 AI 的想法，认为这可能削弱安全和创新的动力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#open-source`, `#AI ethics`, `#OpenAI`, `#AI regulation`

---

<a id="item-11"></a>
## [英伟达开放权重或使开源模型超越闭源](https://www.reddit.com/r/OpenAI/comments/1v0qr60/with_nvidia_going_for_open_weights_will_open/) ⭐️ 7.0/10

英伟达为其 Nemotron 系列大语言模型采用了开放权重策略，标志着行业向开源模型方向的重要转变。 此举可能加速开放权重模型超越闭源模型的趋势，重塑 AI 实验室之间的竞争格局，并影响全球 AI 发展态势。 Nemotron 模型包括针对智能体 AI、推理、多模态视觉和安全等优化的变体，部分可通过 DeepInfra 和 OpenRouter 等 API 获取。

reddit · r/OpenAI · /u/maferase · 7月19日 13:34

**背景**: 开放权重模型公开训练参数，允许修改和本地使用，而闭源模型则限制访问。历史上，开源与闭源之争常与地缘政治分歧相关，西方实验室往往偏好闭源路线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/ai-data-science/foundation-models/nemotron/">Build Agentic AI with Multimodal Foundation Models | NVIDIA Nemotron</a></li>
<li><a href="https://www.ai21.com/glossary/foundational-llm/open-weights-model/">What is an Open-Weights Model? | AI21</a></li>
<li><a href="https://deepinfra.com/nemotron">Nemotron AI Model APIs via DeepInfra</a></li>

</ul>
</details>

**标签**: `#open weights`, `#NVIDIA`, `#AI industry`, `#LLMs`, `#model competition`

---

<a id="item-12"></a>
## [浮游植物碳移除：自然实验显示前景](https://www.onepercentbrighter.com/p/natural-experiments-prove-feeding) ⭐️ 6.0/10

一篇新文章认为，自然实验表明浮游植物施肥可以可靠地刺激水华并移除碳，挑战了先前对其可行性的质疑。 如果可规模化，浮游植物碳移除每年可贡献高达十亿吨二氧化碳移除，为应对气候变化提供重要工具，但关于持久性和副作用的问题依然存在。 浮游植物仅占全球生物量的 1-2%，却贡献了 40%的碳捕获，且近期研究表明生物泵捕获的碳量是先前认为的两倍。

hackernews · getnormality · 7月19日 14:51 · [社区讨论](https://news.ycombinator.com/item?id=48968701)

**背景**: 浮游植物是微小的海洋植物，通过光合作用吸收二氧化碳。它们死亡后，部分沉入深海，长期封存碳。海洋施肥通过添加铁等营养物质刺激水华，但过去的实验显示效率低且存在潜在生态风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://oceanvisions.org/phytoplankton-carbon-solutions/">Phytoplankton-Based Carbon Dioxide Removal | Ocean Visions</a></li>
<li><a href="https://researchfeatures.com/phytoplankton-future-carbon-reduction/">Phytoplankton: The future of carbon reduction?</a></li>
<li><a href="https://www.whoi.edu/oceanus/feature/what-are-the-possible-side-effects/">What Are the Possible Side Effects? - Woods Hole Oceanographic Institution</a></li>

</ul>
</details>

**社区讨论**: 评论者质疑水华是否能导致永久性碳移除，指出腐烂和消耗问题。其他人警告不要傲慢，并担心意外后果，将其与过去的生态干预相比较。文章作者被认为过于专注于这一单一解决方案。

**标签**: `#climate`, `#carbon removal`, `#ocean fertilization`, `#geoengineering`

---

<a id="item-13"></a>
## [Ollama 融资 8800 万美元，但社区批评其性能不佳](https://ollama.com/blog/all-aboard-open-models) ⭐️ 6.0/10

Ollama 于 2026 年 7 月 9 日宣布完成 8800 万美元融资，由 Benchmark、Theory Ventures 等领投，同时为开放模型在 AI 中的作用辩护。 这笔巨额投资表明投资者对开源 AI 充满信心，但社区的批评凸显了资金与技术质量之间的差距，可能影响用户信任和采用。 社区成员批评 Ollama 推理速度慢、量化模型质量低于 llama.cpp 和 Unsloth，并指出其未解决选择性将 MoE 层卸载到 CPU 等问题。

hackernews · inferhaven · 7月19日 07:59 · [社区讨论](https://news.ycombinator.com/item?id=48965880)

**背景**: Ollama 是一个流行的本地运行大语言模型的工具，但它基于 llama.cpp 构建。量化可以减小模型大小和内存需求，但不同工具产生的质量不同。社区经常将 Ollama 与 llama.cpp 和 Unsloth 比较，认为其性能和量化质量较差。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://machinelearningmastery.com/using-quantized-models-with-ollama-for-application-development/">Using Quantized Models with Ollama for Application Development - MachineLearningMastery.com</a></li>
<li><a href="https://computingforgeeks.com/ollama-models-cheat-sheet/">Ollama Models Cheat Sheet 2026 | ComputingForGeeks</a></li>
<li><a href="https://dev.to/skomfi/running-gemma-4-on-a-modest-machine-unsloth-vs-lm-studio-vs-llamacpp-vs-ollama-11cp">Running Gemma 4 on a Modest Machine: Unsloth vs LM Studio vs...</a></li>

</ul>
</details>

**社区讨论**: 评论几乎全是负面，用户敦促他人停止使用 Ollama，因为其性能较慢且量化质量差。有人对这样一个备受批评的项目能融资 8800 万美元表示困惑，也有人承认 Ollama 在普及本地 AI 方面的作用。

**标签**: `#ollama`, `#open-source`, `#local-ai`, `#llama.cpp`, `#funding`

---