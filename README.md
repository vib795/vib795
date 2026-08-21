## Utkarsh Singh

AI engineer. Production RAG and agentic systems at EY, on eleven years of building the platforms that move money in financial services.

Most of what I ship is built for environments where the answer to "can we install that?" is no. That constraint shapes the engineering more than anything else does.

---

### Things that run

#### [agent-memory](https://github.com/vib795/agent-memory) · [npm](https://www.npmjs.com/package/@vib795/agent-memory) · [architecture](https://github.com/vib795/agent-memory/blob/main/ARCHITECTURE.md)

Durable cross-repo memory for Claude Code, GitHub Copilot, and Codex.

Markdown is the source of truth. A `node:sqlite` index sits on top of it as a disposable cache that rebuilds byte-identically from the notes and can be deleted at any time. **Zero runtime and zero dev dependencies**, no daemon, no scheduled task, and no network call anywhere in the source. Published from CI on a signed tag with Sigstore provenance attestation, behind 93 tests and a 12-job Linux/macOS/Windows matrix.

Built because Obsidian, Notion, and every hosted memory tool die at the client's door, and adding a vendor to an approved list takes longer than the engagement does. The review here is reading 2,600 dependency-free lines, not assessing a vendor.

```bash
npm i -g @vib795/agent-memory
```

#### [Yantra: Second Brain](https://apps.apple.com/us/app/yantra-second-brain/id6775635658) · iOS

An on-device RAG note system. Apple Speech transcribes, NLEmbedding vectorizes, and retrieval runs on the phone, so capture and semantic search work in airplane mode. Only the matched snippets and your question ever leave the device, under your own API key, through a proxy that stores nothing. English, Hindi, and Hinglish.

#### [copilot-howto](https://github.com/vib795/copilot-howto)

A full Copilot tutorial for the much larger group of developers who have Copilot at work and nothing else. Ten modules, open source, no signup.

---

### Writing

- **LLM Evals: The Complete Field Guide** — inter-annotator reliability, judge calibration, cost-routed annotation, and why an eval system nobody chooses to use is a failed eval system. At [singhcodes.dev](https://www.singhcodes.dev)
- [Advanced Guide to Asyncio, Threading, and Multiprocessing in Python](https://medium.com/p/c4dc50971d24)
- [Understanding and Setting Up Cron Jobs in AWS for Batch Job Automation](https://medium.com/p/d15cdf334596)
- [How to Turn Your Raspberry Pi into a Secure Travel Router](https://medium.com/p/138377eb7e02)

Archive at [singhcodes.dev](https://www.singhcodes.dev) and [Medium](https://medium.com/@connectwithutkarshsingh).

---

### At work

Lead Engineer, AI & Platform at EY.

Code intelligence over large commercial financial platforms, where retrieval is a different problem than it is over prose: chunking on AST boundaries rather than token windows, a graph store because "what calls this" is not a similarity question, and BM25 because identifiers are exactly the rare tokens embeddings handle worst. Fused with Reciprocal Rank Fusion and cross-encoder reranking, with promotion gated on RAGAS scores against golden datasets.

Alongside it, an agentic infrastructure-onboarding system that cut application provisioning from weeks to hours, with human approval gates on anything destructive.

Before that, four years embedded at Fidelity Investments on retail investing and institutional separately-managed-account platforms.

---

### Also

[India Passport Photo Seva](https://apps.apple.com/us/app/india-passport-photo-seva/id6776499863) (iOS, fully on-device) · [always-decimal](https://github.com/vib795/always-decimal) on PyPI · [everyday-developer-tools](https://github.com/vib795/everyday-developer-tools) and [wrench.tools](https://wrench.tools) · three Go CLIs ([pull-vids](https://github.com/vib795/pull-vids), [convert-vid](https://github.com/vib795/convert-video-formats), [epub2pdf](https://github.com/vib795/epub2pdf)) via `brew tap vib795/tap`

---

📬 hello@singhcodes.dev · [LinkedIn](https://www.linkedin.com/in/connectwithutkarshsingh/) · [singhcodes.dev](https://www.singhcodes.dev)
