<div align="center">
# Muhammad Faizan · `@faizzyhon`
 
**AI engineer & full-stack developer · B.S. Artificial Intelligence · KSA**
 
I build language-model systems that actually run: small models fine-tuned, compressed and shipped, with measured results and honest limits. Focus: multilingual NLP and LLMs (Arabic, English, Urdu). Open to full-time work in AI/ML and full-stack engineering (onsite, hybrid or remote).
 
[`portfolio`](https://faizzyhon.github.io) · [`faizzyhon.com`](https://www.faizzyhon.com) · [`linkedin`](https://www.linkedin.com/in/faizzyhon) · `KSA · open to hire`
 
![Profile views](https://komarev.com/ghpvc/?username=faizzyhon&style=flat-square&color=blue)
![Followers](https://img.shields.io/github/followers/faizzyhon?style=flat-square&label=followers&color=blue)
![GitHub Pull Shark](https://img.shields.io/badge/achievement-Pull%20Shark-blueviolet?style=flat-square)
![YOLO](https://img.shields.io/badge/achievement-YOLO-orange?style=flat-square)
![Quickdraw](https://img.shields.io/badge/achievement-Quickdraw-yellow?style=flat-square)
 
</div>
---
 
## Now
 
- Maintaining **[PocketBot](https://github.com/faizzyhon/PocketBot)**: train a small chatbot on your own FAQ and run it inside the web page, with no server and no API key
- Building **[rihla-llm](https://github.com/faizzyhon/rihla-llm)**: a multilingual (Arabic / English / Urdu) LLM pipeline from data cleaning to serving
- Building **[KORA](https://github.com/faizzyhon/kora)**: an open-source execution-control layer for AI workloads (task graphs, deterministic-first execution, validation, model escalation only when needed); currently alpha
- Recently landed **2 merged bug fixes** in **[keon/algorithms](https://github.com/keon/algorithms)** (25.4k★), Python corrections to `roman_to_int` and `_remove_punctuation` ([commits](https://github.com/keon/algorithms/commits?author=faizzyhon))
---
 
## Selected work
 
### Machine learning
 
| Project | What it is | Measured |
|---|---|---|
| **[PocketBot](https://github.com/faizzyhon/PocketBot)** | Offline chatbot pipeline: fine-tunes SmolLM2-135M on a FAQ, compresses it to 4-bit (about 89 MB) with quantization-aware training, and runs it in the browser with ONNX Runtime (WebGPU or WebAssembly). Extracted from Fuzz, the guide robot on [faizzyhon.com](https://faizzyhon.com). | 97.0% next-token accuracy with quantization-aware training, vs 88.8% for plain 4-bit rounding (97.2% at full precision). About 8 of 12 unseen questions answered correctly. Limits are written up in the README. |
| **[rihla-llm](https://github.com/faizzyhon/rihla-llm)** | Multilingual (Arabic / English / Urdu) LLM pipeline: PII scrubbing, MinHash dedup, tokenizer extension, QLoRA and DPO, hybrid retrieval, release gate, guardrails. | Work in progress: the evaluation suites are small and results are not yet published. |
| **[KORA](https://github.com/faizzyhon/kora)** | Execution-control layer for AI workloads: task graphs, deterministic-first execution, validation, model escalation only when needed. | Alpha benchmark: 80% fewer model invocations on a deterministic-heavy workload. |
 
### Open source contributions
 
| Repo | Stars | Status | Contribution |
|---|---|---|---|
| [keon/algorithms](https://github.com/keon/algorithms) | 25.4k★ | **Merged** | Two Python bug fixes: `roman_to_int` raised `IndexError` on empty string ([`f39a07e`](https://github.com/keon/algorithms/commit/f39a07ee95664ec3c1c15b947f5cd2d5134188ef)); `_remove_punctuation` was stripping digits and producing false palindrome positives ([`b8f9dca`](https://github.com/keon/algorithms/commit/b8f9dca0a6515f77dc9a4daf346ed952ea8cb07f)) |
| [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 389k★ | Closed (not merged) | Proposed `last updated` notation for podcast/screencast entries, targeting [#12348](https://github.com/EbookFoundation/free-programming-books/issues/12348) |
| [RetroShare/RetroShare](https://github.com/RetroShare/RetroShare) | 1.9k★ | PR open | Contributions to the decentralized F2F communication platform |
| [RetroShare/libretroshare](https://github.com/RetroShare/libretroshare) | n/a | PR open | Library-side contributions |
 
A public log of every contribution lives at **[faizzyhon/open-source-journey](https://github.com/faizzyhon/open-source-journey)**, including a tested "first OSS PR" playbook for newcomers.
 
### Also built
 
- **[Gale](https://github.com/faizzyhon/Gale)**: an open-source Windows download manager
- **[faizzyhon.com](https://faizzyhon.com)**: developer tools and a blog
- Production web software for hotels and clinics in Saudi Arabia: a hotel finance system, a billing and booking platform, and a bilingual Arabic/English clinic site
---
 
## Stack
 
**Languages**  &nbsp; Python · TypeScript · JavaScript · PHP · SQL · C++ · Shell
**AI / ML**  &nbsp; PyTorch · TensorFlow · scikit-learn · Hugging Face Transformers · LangChain · ONNX Runtime · Ollama · OpenAI and Anthropic APIs
**Model serving**  &nbsp; FastAPI · Flask · Docker · PostgreSQL
**Web**  &nbsp; Next.js · React · Tailwind
**Infra**  &nbsp; Vercel · Supabase · GitHub Actions
 
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
</p>
---
 
## Credentials
 
- **B.S. Artificial Intelligence**, The Islamia University of Bahawalpur (2024)
- **Advanced Machine Learning** professional training program, Systems Limited Training & Development (2026)
- **ML Engineer**, Systems Limited (remote, 2023–2024): text-classification and NLP pipelines served via FastAPI and Flask
- **Certified Ethical Hacker (CEH)**, EC-Council
---
 
## GitHub
 
<div align="center">
<a href="https://github.com/faizzyhon">
  <img src="https://github-readme-stats.vercel.app/api?username=faizzyhon&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=faizzyhon&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="160" />
</a>
</div>
---
 
## Reach me
 
- Website &nbsp;·&nbsp; [www.faizzyhon.com](https://www.faizzyhon.com)
- Email &nbsp;·&nbsp; faizzyhon@gmail.com
- GitHub &nbsp;·&nbsp; [@faizzyhon](https://github.com/faizzyhon)
- Based in KSA &nbsp;·&nbsp; open to full-time roles
 
