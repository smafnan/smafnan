<div align="center">

<!-- ── Banner ──────────────────────────────────────────────────────────────── -->
<img src="assets/banner.svg" alt="Afnan — AI engineer · full-stack developer" width="100%">

<p>
  <a href="https://afnancodes.com"><img src="https://img.shields.io/badge/afnancodes.com-0F172A?style=flat-square&logo=googlechrome&logoColor=22D3EE" alt="Website"></a>&nbsp;
  <a href="mailto:smafnan5@gmail.com"><img src="https://img.shields.io/badge/say%20hi-0F172A?style=flat-square&logo=gmail&logoColor=7C3AED" alt="Email"></a>&nbsp;
  <a href="https://www.linkedin.com/in/afnancodes"><img src="https://img.shields.io/badge/linkedin-0F172A?style=flat-square&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"></a>&nbsp;
  <a href="https://x.com/afnancodes"><img src="https://img.shields.io/badge/@afnancodes-0F172A?style=flat-square&logo=x&logoColor=94A3B8" alt="X"></a>&nbsp;
  <!-- Add when ready:
  <a href="YOUR_5CALE_URL"><img src="https://img.shields.io/badge/5cale-0F172A?style=flat-square&logo=diagramsdotnet&logoColor=22D3EE" alt="5cale"></a>
  -->
</p>

</div>

I design things that scale and build AI that ships. I run **5cale**, a design studio, and I trained myself as an AI engineer the hard way — a 23-project curriculum I built and shipped end-to-end, from hand-written backprop to CI/CD-gated ML pipelines. Every claim below has a repo behind it.

## ⚡ Now

- 🎨 Rebuilding the **5cale** site — Next.js 15, Three.js, GSAP, and a chrome "5" that follows your scroll
- 🤖 Shipped a **23-project AI-engineering roadmap** — foundations → deep learning → LLM systems → MLOps
- 🧪 Going deeper on **evals & agent reliability** — the unglamorous parts that make AI products trustworthy

## ⭐ Featured builds

<table>
<tr>
<td width="50%" valign="top">

**[TestGenRag](https://github.com/smafnan/TestGenRag)** 🧬<br>
Guardrailed, human-in-the-loop RAG agent that drafts citation-backed test cases from your documents. HyDE retrieval, relevance gate, LLM-as-judge grounding check. Live on HF Spaces.<br>
<sub>`LangGraph` · `FAISS` · `FastAPI` · `Docker` · `CI`</sub>

</td>
<td width="50%" valign="top">

**[ClaudeCodeStudent](https://github.com/smafnan/ClaudeCodeStudent)** 🔌<br>
Anthropic-Messages-API-compatible proxy with **17 provider backends** (NVIDIA NIM, OpenRouter, Gemini, Ollama…) — routes Claude Code's model tiers to any LLM, with streaming & tool-use translation.<br>
<sub>`FastAPI` · `SSE` · `Discord/Telegram bots` · `Admin UI`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[tiny-gpt](https://github.com/smafnan/tiny-gpt)** 🧠<br>
A character-level GPT built from scratch in PyTorch — multi-head causal self-attention written by hand, no `nn.MultiheadAttention`. 0.8M params trained on CPU, plus a web playground.<br>
<sub>`PyTorch` · `Transformers` · `React playground`</sub>

</td>
<td width="50%" valign="top">

**[mlops-pipeline](https://github.com/smafnan/mlops-pipeline)** 🏭<br>
Push-triggered ML pipeline: validate → train → **quality gate** → versioned registry → deploy, with PSI drift monitoring. A model below threshold literally cannot reach production — CI fails.<br>
<sub>`GitHub Actions` · `Model registry` · `Drift detection`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[reddit-answer-bot](https://github.com/smafnan/reddit-answer-bot)** 🗣️<br>
7-agent LangGraph pipeline that answers questions by synthesizing Reddit community consensus — SSE streaming, live force-directed knowledge graph, and a Windows 98 theme (of course).<br>
<sub>`LangGraph` · `Multi-agent` · `FastAPI` · `React`</sub>

</td>
<td width="50%" valign="top">

**[eval-harness](https://github.com/smafnan/eval-harness)** 📏<br>
Evaluation framework for non-deterministic LLM systems — labelled cases, pluggable scorers incl. LLM-as-judge, and regression detection that exits non-zero so CI can block bad prompt changes.<br>
<sub>`LLM-as-judge` · `Regression gating` · `Python`</sub>

</td>
</tr>
</table>

## 🧭 The AI-Engineer Roadmap — 0 → production in 23 repos

> A self-built curriculum. Rule: no project counts until it's shipped, measured, and written up honestly.

`NumPy backprop` → `CNNs & transfer learning` → `GPT from scratch` → `RAG + agents + evals` → `Docker, CI/CD & drift monitoring` → `capstones`

<details>
<summary><b>Expand the full journey</b></summary>
<br>

| Phase | Projects |
|---|---|
| **0 · Tooling** | [data-cleaning-cli](https://github.com/smafnan/data-cleaning-cli) · [eda-penguins](https://github.com/smafnan/eda-penguins) — defensive CSV cleaner; EDA that surfaces Simpson's paradox |
| **1 · Classical ML** | [housing-regression](https://github.com/smafnan/housing-regression) · [fraud-classification](https://github.com/smafnan/fraud-classification) · [from-scratch-numpy](https://github.com/smafnan/from-scratch-numpy) — full ML loops, cost-based thresholds, algorithms rebuilt in NumPy |
| **2 · Deep learning** | [neural-net-from-scratch](https://github.com/smafnan/neural-net-from-scratch) (97.7% MNIST, hand-written backprop) · [cifar-pytorch](https://github.com/smafnan/cifar-pytorch) · [training-dashboard](https://github.com/smafnan/training-dashboard) |
| **3 · NLP & LLMs** | [text-classifier](https://github.com/smafnan/text-classifier) (TF-IDF vs DistilBERT) · [tiny-gpt](https://github.com/smafnan/tiny-gpt) · [llm-extractor](https://github.com/smafnan/llm-extractor) (validated JSON from any provider) |
| **4 · AI systems** | [rag-system](https://github.com/smafnan/rag-system) (retrieval measured with Recall@k/MRR) · [agent](https://github.com/smafnan/agent) (fails gracefully, on purpose) · [eval-harness](https://github.com/smafnan/eval-harness) |
| **5 · Production** | [model-service](https://github.com/smafnan/model-service) (Dockerized FastAPI) · [mlops-pipeline](https://github.com/smafnan/mlops-pipeline) · [llm-optimization](https://github.com/smafnan/llm-optimization) (−76% cost, −74% latency, measured) |
| **6 · Capstones** | [resume-tailor](https://github.com/smafnan/resume-tailor) (anti-fabrication guardrail) · [teaching-eval-harnesses](https://github.com/smafnan/teaching-eval-harnesses) (teach-it-back) |
| **★ Bonus** | [quran-rag](https://github.com/smafnan/quran-rag) & [nahjulbalagha-rag](https://github.com/smafnan/nahjulbalagha-rag) (grounded, citation-only answers) · [paper-rag](https://github.com/smafnan/paper-rag) · [business-website-finder](https://github.com/smafnan/business-website-finder) |

</details>

## 🧰 Stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,pytorch,sklearn,fastapi,docker,githubactions,git,ts,react,nextjs,tailwind,threejs,nodejs,figma,netlify,vite&perline=8&theme=dark">
  <img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,fastapi,docker,githubactions,git,ts,react,nextjs,tailwind,threejs,nodejs,figma,netlify,vite&perline=8&theme=light" alt="Tech stack">
</picture>

</div>

## 📊 GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=smafnan&show_icons=true&hide_border=true&bg_color=00000000&title_color=7C3AED&icon_color=22D3EE&text_color=94A3B8&ring_color=7C3AED&rank_icon=github&include_all_commits=true">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=smafnan&show_icons=true&hide_border=true&bg_color=00000000&title_color=6D28D9&icon_color=0891B2&text_color=334155&ring_color=6D28D9&rank_icon=github&include_all_commits=true" alt="GitHub stats">
</picture>&nbsp;&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=smafnan&hide_border=true&background=00000000&ring=7C3AED&fire=22D3EE&currStreakLabel=7C3AED&sideLabels=94A3B8&currStreakNum=C7CEDB&sideNums=C7CEDB&dates=8B94A8">
  <img height="165" src="https://streak-stats.demolab.com?user=smafnan&hide_border=true&background=00000000&ring=6D28D9&fire=0891B2&currStreakLabel=6D28D9" alt="GitHub streak">
</picture>

<br><br>

<!-- ── Contribution snake (generated by .github/workflows/snake.yml) ────────── -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/smafnan/smafnan/output/github-contribution-grid-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/smafnan/smafnan/output/github-contribution-grid-snake.svg" alt="Contribution graph snake animation" width="100%">
</picture>

</div>

<br>

<div align="center">
  <sub><b>5cale</b> · design that scales — systems that ship · <a href="https://afnancodes.com">afnancodes.com</a></sub>
</div>

<!-- profile: smafnan -->
