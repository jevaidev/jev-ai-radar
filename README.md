# Jev AI Radar

**Daily curated Jev AI projects, System One community models, and real-world use cases.**

[Explore the interactive project ranking](https://jevai.dev/projects/) · [Browse real use cases](https://jevai.dev/user-cases/) · [Try Jev for free](https://jevai.dev/playground/) · [Read official Jev information](https://typesafe.ai/)

> Jev AI Radar is an independent community resource maintained by [Jev AI Dev](https://jevai.dev/). It is not affiliated with or endorsed by TypeSafe AI.

## Latest radar — September 23, 2026

- **48 ranked GitHub projects** tracked with Stars, licenses, languages, creation dates, and last commit times.
- **21 community System One projects** tracked separately from official Jev releases.
- **25 selected use cases** from developers, product teams, X posts, and YouTube demonstrations.
- The latest editorial snapshot is available in [`daily/2026/09/2026-09-23.md`](daily/2026/09/2026-09-23.md).

## Jev GitHub ranking

Stars are a discovery signal, not a quality or safety guarantee. The complete machine-readable collection lives in [`data/projects.json`](data/projects.json).

| Rank | Project | Stars | Type | What it does |
| ---: | --- | ---: | --- | --- |
| 1 | [Jev Ultrafast](https://github.com/browser-use/jev-ultrafast) | 18,893 | Tool | A browser agent that asks Jev to choose an operation and page element from live DOM state; a separate text model handles typing. |
| 2 | [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | 6,504 | Tool | A Claude Code plugin that uses Jev to keep, trim or drop tool calls and results while preserving conversation text. |
| 3 | [Jev Chat Jarvis](https://github.com/jev-chat/jev-chat-jarvis) | 5,140 | App | An Android chat companion that reads visible messages through Accessibility or OCR, asks Jev about intent and risk, and ranks draft replies without sending them. |
| 4 | [jev-trader](https://github.com/jarrodwatts/jev-trader) | 2,152 | App | A Monad order-book bot with an optional Jev mode for buy or sell decisions; its default run uses a mock heuristic. |
| 5 | [Jev Review](https://github.com/devagrawal09/jev-review) | 573 | Tool | Reviews diffs or codebases through staged Jev judgments about risk, evidence and severity, with a local dashboard. |
| 6 | [Foreman](https://github.com/thruwire/foreman) | 529 | Tool | Supervises coding agents with Jev judgments about progress, verification and when a worker needs intervention. |
| 7 | [Jev Skill](https://github.com/wuyoscar/jev-skill) | 460 | Examples | Installable Jev skills and editable agent workflows with scenario templates, recorded examples and tests. |
| 8 | [Jev Search](https://github.com/superagents-lab/jev-search) | 431 | App | Uses Jev to choose search sources and rank results returned through Search1API, showing links instead of generated answers. |
| 9 | [Jev Chat for Windows](https://github.com/jev-chat/jev-chat-windows) | 428 | App | A Windows WeChat helper using local screenshots and OCR, Jev judgments and ranked reply candidates; filling is explicit and sending remains manual. |
| 10 | [Mobile Jev](https://github.com/droidrun/mobile-jev) | 368 | App | A mobile agent that uses Jev to choose actions on an Android device through Mobilerun, with a live studio and execution traces. |

[View the live sortable ranking on jevai.dev →](https://jevai.dev/projects/)

## System One community ecosystem

These are independent experiments, open models, and compatible interfaces inspired by fast, typed decision systems. They are **not official TypeSafe Jev releases**.

| Project | Base or approach | Form |
| --- | --- | --- |
| [Bespoke Nimble](https://github.com/bespokelabsai/nimble) | Qwen3.5-9B | Model |
| [NanoJev](https://github.com/TianyuCodings/NanoJev) | Qwen3-0.6B | Model |
| [decider](https://github.com/Mapika/decider) | Qwen3.5-2B | Model |
| [Verdict](https://github.com/Heman10x-NGU/openJev-verdict-2.0) | ModernBERT 151M / Verdict 2.0 | Model |
| [Dohnuts](https://github.com/PsiACE/dohnuts) | Qwen3.5-0.8B | Model |
| [OpenJev](https://github.com/razorback16/openjev) | DiffusionGemma 26B-A4B | Interface |
| [Simple Jev](https://github.com/featherless-ai/simple-jev) | Open-model logits | Interface |
| [Rizzo Flow](https://github.com/Rizzo-AI-Academy/rizzo-flow) | Spark-X2.5-4B | Interface |
| [AnyJev](https://github.com/nokia-applied-research/AnyJev) | Any causal LLM | Interface |
| [local-jev](https://github.com/amithgc/local-jev) | Qwen3.5 / DeBERTa | Interface |
| [AgentJev](https://github.com/malevrigns/agent-jev) | Qwen3-0.6B | Model |
| [LLM2Jev](https://github.com/Yinsongxu/LLM2Jev) | Causal LMs / SGLang | Interface |
| [Laya](https://github.com/receptron/laya) | Laya / ONNX Runtime | Interface |
| [OpenThai System One](https://github.com/iapp-technology/openthai-systemone) | Qwen3.5-0.8B | Model |
| [Laya Server](https://github.com/1Panel-dev/laya-server) | Laya multilingual | Interface |
| [stuntd](https://github.com/bladedevoff/stuntd) | Laya / learned heads | Interface |
| [jevper](https://github.com/zhulinchng/jevper) | OpenAI-compatible models | Interface |
| [Valen](https://github.com/Liuziyu77/Valen) | Qwen3.5-2B / multimodal | Model |
| [MoJev](https://github.com/MoLeMo-Lab/mojev) | 0.85B multimodal | Model |
| [Qwev](https://github.com/HopLee6/Qwev) | Qwen3 / Qwen3.5 | Interface |
| [Dynajev](https://github.com/strangeloopcanon/dynajev) | Open-weight causal LMs | Interface |

[Explore the System One ecosystem on jevai.dev →](https://jevai.dev/system-one/)

## Selected use cases

| Use case | Decision pattern | Source |
| --- | --- | --- |
| Voice-controlled browser actions | Choice + Noul | [Moritz Kremb on YouTube](https://www.youtube.com/watch?v=Nq_lu5QT-fI&t=359s) |
| Browser agent action selection | Choice | [Gregor Zunic on X](https://x.com/gregpr07/status/2100411066966749359) |
| Instant context compaction | Score + Noul | [Tamara Tran on X](https://x.com/tamarajtran/status/2100694549362553153) |
| Box incident routing | Choice + Score | [Aaron Levie on X](https://x.com/levie/status/2101007708044574906) |
| Gmail intent search | Noul + Score | [Nader Dabit on X](https://x.com/dabit3/status/2100960281769738433) |
| Structured pull-request review | Noul + Score | [Paolo Rosson on X](https://x.com/redp314/status/2100585126652481915) |
| Agent evaluation judge | Noul + Score | [LangChain on X](https://x.com/LangChain/status/2101454284927959080) |
| TypeSafe team interview and live demos | Choice + Score + Noul | [ThursdAI on YouTube](https://www.youtube.com/watch?v=QkPnAoHBXwo) |

[Browse the complete curated use-case library →](https://jevai.dev/user-cases/)

## Open data

The first release intentionally keeps the infrastructure simple:

- [`data/projects.json`](data/projects.json): ranked Jev repositories and GitHub metadata.
- [`data/system-one-models.json`](data/system-one-models.json): independent models and interfaces in the wider ecosystem.
- [`data/use-cases.json`](data/use-cases.json): selected demonstrations with decisions, takeaways, sources, and review dates.
- [`daily/`](daily/): short editorial snapshots designed for future newsletter reuse.

Data is reviewed before publication. Project descriptions summarize public sources and should not be treated as security, performance, or quality endorsements.

## Discovery sources

Radar candidates may be discovered through community indexes such as [awesome-jev](https://github.com/yibie/awesome-jev). Every published entry is checked against its original repository, post, video, or another primary source. We do not copy third-party summaries, classifications, or endorsements.

## Contribute

Found a new Jev project, System One experiment, or real-world use case? [Open a submission issue](../../issues/new?template=submit.yml) or read [`CONTRIBUTING.md`](CONTRIBUTING.md).

If this radar helps you discover something useful, please **Star the repository** and share it with another developer.

## License and attribution

Original summaries and curated metadata in this repository are licensed under [CC BY 4.0](LICENSE.md). Linked repositories, posts, videos, names, and trademarks remain the property of their respective owners.
