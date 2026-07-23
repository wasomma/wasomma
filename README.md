# Wesley Fine

Senior Director of Solution Engineering at BAE Systems OneArc. I lead solutions
engineering, proposal operations, and customer success for a defense
technology business, and I'm a hands-on practitioner of agentic AI: agentic
workflows for proposal and estimation automation, RAG interfaces over business
systems, and MCP-based integration between simulation environments.

Most of my professional work lives in cleared and proprietary environments, so
the repositories here are demonstration pieces built on personal time. The best
place to start is [fpv-sim](https://github.com/wasomma/fpv-sim), a single-file
FPV sUAS vs cUAS force-on-force simulation with a
[live demo](https://wasomma.github.io/fpv-sim/), where emissions discipline
decides the fight. That claim is now backed by a 22,800-engagement Monte Carlo
study with a [live results dashboard](https://wasomma.github.io/fpv-sim/dashboard.html) —
equally single-file and dependency-free — showing headline win rates with
confidence intervals, a dose-response curve of uplink duty cycle against win
rate, paired same-seed comparisons, and notable engagements that deep-link back
into the sim, so every statistic opens as a watchable battle. Its companion,
[fpv-sim-mcp](https://github.com/wasomma/fpv-sim-mcp),
extracts that simulation into a headless engine — the same engine the Monte
Carlo study runs on — and serves it over the Model Context Protocol: five
typed tools that let an AI agent run deterministic
engagements, sweep seeds, and settle doctrine questions with paired
experiments — and discover for itself that the side that transmits less is
harder to fix. It runs locally over stdio or as a hosted remote endpoint
(Streamable HTTP behind TLS), so an agent anywhere can connect without
building anything.

Formerly: simulation training product development at MAG Aerospace, SIGINT test
and training on Army ISR programs, and six years as a USAF airborne cryptologic
linguist with 2,000+ combat hours.

[LinkedIn](https://www.linkedin.com/in/wesleyfine/)
