# Jev AI Radar

**Daily curated Jev AI projects, System One community models, and real-world use cases.**

[Explore the interactive project ranking](https://jevai.dev/projects/) · [Browse real use cases](https://jevai.dev/user-cases/) · [Try Jev for free](https://jevai.dev/playground/) · [Read official Jev information](https://typesafe.ai/)

> Jev AI Radar is an independent community resource maintained by [Jev AI Dev](https://jevai.dev/). It is not affiliated with or endorsed by TypeSafe AI.

## Latest radar — September 22, 2026

- **26 ranked GitHub projects** tracked with stars, licenses, languages, creation dates, and last commit times.
- **10 community System One projects** tracked separately from official Jev releases.
- **25 selected use cases** from developers, product teams, X posts, and YouTube demonstrations.
- The first daily editorial snapshot is available in [`daily/2026/09/2026-09-22.md`](daily/2026/09/2026-09-22.md).

## Jev GitHub ranking

Stars are a discovery signal, not a quality or safety guarantee. The complete machine-readable collection lives in [`data/projects.json`](data/projects.json).

| Rank | Project | Stars | Type | What it does |
| ---: | --- | ---: | --- | --- |
| 1 | [Jev Ultrafast](https://github.com/browser-use/jev-ultrafast) | 16,112 | Tool | Uses Jev to choose browser operations and page elements from live DOM state. |
| 2 | [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | 6,014 | Tool | Keeps, trims, or drops tool calls while preserving conversation text. |
| 3 | [jev-trader](https://github.com/jarrodwatts/jev-trader) | 1,871 | App | Explores bounded buy or sell decisions in an order-book bot. |
| 4 | [Jev Review](https://github.com/devagrawal09/jev-review) | 496 | Tool | Reviews code through structured risk, evidence, and severity judgments. |
| 5 | [Foreman](https://github.com/thruwire/foreman) | 468 | Tool | Supervises coding agents and flags when intervention is needed. |
| 6 | [Jev Search](https://github.com/superagents-lab/jev-search) | 382 | App | Selects search sources and ranks linked results. |
| 7 | [Mobile Jev](https://github.com/droidrun/mobile-jev) | 328 | App | Chooses actions for an Android agent with visible execution traces. |
| 8 | [jev-router](https://github.com/gargpratyush/jev-router) | 314 | Tool | Routes coding-agent turns to an appropriate model tier. |
| 9 | [jev-align](https://github.com/sutro-sh/jev-align) | 270 | Tool | Evaluates and improves fixed-output classifiers with labelled data. |
| 10 | [Jev MCP](https://github.com/jkudish/jev-mcp) | 241 | Tool | Exposes Jev-backed verification, ranking, classification, and review tools over MCP. |

[View the live sortable ranking on jevai.dev →](https://jevai.dev/projects/)

## System One community ecosystem

These are independent experiments, open models, and compatible interfaces inspired by fast, typed decision systems. They are **not official TypeSafe Jev releases**.

| Project | Base or approach | Form |
| --- | --- | --- |
| [Bespoke Nimble](https://github.com/bespokelabsai/nimble) | Qwen3.5-9B | Model |
| [NanoJev](https://github.com/TianyuCodings/NanoJev) | Qwen3-0.6B | Model |
| [decider](https://github.com/Mapika/decider) | Qwen3.5-2B | Model |
| [Verdict](https://github.com/Heman10x-NGU/Verdict-open-jev) | ModernBERT 151M | Model |
| [Dohnuts](https://github.com/PsiACE/dohnuts) | Qwen3.5-0.8B | Model |
| [OpenJev](https://github.com/razorback16/openjev) | DiffusionGemma 26B-A4B | Interface |
| [Simple Jev](https://github.com/featherless-ai/simple-jev) | Open-model logits | Interface |
| [Rizzo Flow](https://github.com/Rizzo-AI-Academy/rizzo-flow) | Spark-X2.5-4B | Interface |
| [AnyJev](https://github.com/nokia-applied-research/AnyJev) | Any causal LLM | Interface |
| [local-jev](https://github.com/amithgc/local-jev) | Qwen3.5 / DeBERTa | Interface |

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

## Contribute

Found a new Jev project, System One experiment, or real-world use case? [Open a submission issue](../../issues/new?template=submit.yml) or read [`CONTRIBUTING.md`](CONTRIBUTING.md).

If this radar helps you discover something useful, please **Star the repository** and share it with another developer.

## License and attribution

Original summaries and curated metadata in this repository are licensed under [CC BY 4.0](LICENSE.md). Linked repositories, posts, videos, names, and trademarks remain the property of their respective owners.

