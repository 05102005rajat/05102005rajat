# Rajat Choudhary

Software Engineer building reliable backend systems, distributed infrastructure, and AI-powered applications.

**Now**
- SWE Intern @ **Built By The Trades** (Jun 2026 to present) — gamified performance layer on a home-services SaaS
- Research with **Prof. Ian G. Harris**, UCI CS — encoding physical-safety constraints into PDDL planning domains

**Previously**
- SWE Intern @ **[Spacebourne](https://spacebourne.com)** (Apr to Jun 2026) — CLARITY, a satellite RF interference SaaS. Spring 2026 Delta-V Capstone Award
- AI/ML Intern @ **Adani Green Energy** (Jun to Sep 2025) — RAG chatbot with LangChain + FAISS, 60% faster query resolution

CS @ UC Irvine, graduating December 2026.

---

## Selected projects

**[HN Search](https://github.com/05102005rajat/hn-search)** — a from-scratch information retrieval engine over Hacker News, built without Lucene, Elasticsearch or Whoosh. Var-byte and delta-encoded postings behind an LRU cache, field-weighted TF-IDF, bigram phrase index. 0.78s index build, sub-millisecond queries.

**[cf_ai_docs_tutor](https://github.com/05102005rajat/cf_ai_docs_tutor)** — RAG documentation tutor on a single Cloudflare Worker: Workers AI embeddings, Vectorize retrieval, Durable Object session state. Citations are cross-checked against what the model actually cited. [Live](https://cf-ai-docs-tutor.05102005rajat.workers.dev)

**[distributed-rate-limiter](https://github.com/05102005rajat/distributed-rate-limiter)** — rate limiter in Go with state shared across instances through Redis. Token bucket and sliding-window log as atomic Lua scripts. A naive-vs-atomic demo admits 500 of 500 against a limit of 100; the atomic path holds exactly 100.

**[mech-interp-rajat](https://github.com/05102005rajat/mech-interp-rajat)** — reproduced the Indirect Object Identification circuit (Wang et al. 2022) in GPT-2 small with TransformerLens. A 9-head circuit isolated by activation patching, validated against size-matched random-control ablation (z = -21.5).

**[JobScope AI](https://github.com/05102005rajat/jobscope-ai)** — job application tracker driven by a 5-tool LangGraph agent. Match accuracy went 43% to 80% via semantic JD-vs-resume comparison; agent reliability went 70% to 98% through tool design rather than larger models. [Live](https://jobscope-ai-yov1.vercel.app)

**[cerebras-asset-tracking](https://github.com/05102005rajat/cerebras-asset-tracking)** — multi-site asset reconciliation across operations, facilities and finance. A server-side three-way join classifies drift by the action an operator would take, not by raw diff. 59 tests, all 8 seeded drift cases caught. [Live](https://cerebras-asset-tracking-starter.vercel.app)

Also: **[cerebras-topk-knn](https://github.com/05102005rajat/cerebras-topk-knn)**, a top-K k-NN kernel in Cerebras CSL for the WSE-2, one of ~49 perfect-passing kernels out of 1,000+ submissions to the Cerebras Kernel Challenge.

## Tech

Go, Python, TypeScript, React, FastAPI, PostgreSQL, Redis, LangGraph, PyTorch, Cloudflare Workers, Cerebras CSL

## Contact

05102005rajat@gmail.com
