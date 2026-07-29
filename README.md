<div align="center">

<img src="./assets/header.svg" width="100%" alt="Nikhil Patil — Generative AI, MLOps, Machine Learning. Mumbai, India." />

<br />

<a href="https://www.linkedin.com/in/nikhilsatyawanpatil/"><img src="https://img.shields.io/badge/LinkedIn-1C2128?style=flat-square&logo=linkedin&logoColor=E9C46A&labelColor=0D1117" alt="LinkedIn" /></a>
&nbsp;<a href="mailto:nikhilsatyawanpatil@gmail.com"><img src="https://img.shields.io/badge/Email-1C2128?style=flat-square&logo=maildotru&logoColor=E9C46A&labelColor=0D1117" alt="Email" /></a>
&nbsp;<a href="https://www.youtube.com/channel/UCpakmXio90uAd4RBZqimG8Q"><img src="https://img.shields.io/badge/YouTube-1C2128?style=flat-square&logo=youtube&logoColor=E9C46A&labelColor=0D1117" alt="YouTube" /></a>
&nbsp;<a href="https://www.instagram.com/nikhilpatil.ai/"><img src="https://img.shields.io/badge/Instagram-1C2128?style=flat-square&logo=instagram&logoColor=E9C46A&labelColor=0D1117" alt="Instagram" /></a>
&nbsp;<img src="https://komarev.com/ghpvc/?username=NAME-NikhilPatil&style=flat-square&color=E9C46A&labelColor=0D1117&label=views" alt="Profile views" />

</div>

<br />

> ### Open to AI / ML Engineer roles
> **Generative AI · LLM Engineering · MLOps · Machine Learning** — full-time, Mumbai or remote.
> If you're shipping an AI product that has to keep working *after* the demo, I'd like to hear about it.
> [**Start a conversation →**](https://www.linkedin.com/in/nikhilsatyawanpatil/)

<br />

<sub>**01**</sub>
##  Who I am

I'm an AI/ML Engineer in Mumbai who builds **generative AI systems that hold up in production** — retrieval and agent pipelines that are evaluated rather than eyeballed, fine-tuned open models that fit real hardware budgets, and the MLOps scaffolding that keeps both reproducible.

My bias is toward the unglamorous half of the work: evaluation harnesses, tracing, caching, guardrails, and deploy pipelines. A model that scores well once is a demo. A model you can re-train, re-measure, and roll back is a product.

<table>
<tr><td width="120"><sub><b>GENERATIVE&nbsp;AI</b></sub></td><td><sub>Multi-agent RAG with LangGraph · semantic search &amp; reranking · RAGAS evaluation · guardrails · streaming</sub></td></tr>
<tr><td><sub><b>FINE-TUNING</b></sub></td><td><sub>QLoRA · PEFT · TRL on Gemma 4 and Llama 3.2 · leak-free dataset splits · HumanEval-style benchmarking</sub></td></tr>
<tr><td><sub><b>MLOPS</b></sub></td><td><sub>Azure ML · MLflow tracking &amp; registry · Docker · Kubernetes · FastAPI · reproducible training pipelines</sub></td></tr>
<tr><td><sub><b>ALSO</b></sub></td><td><sub>Production computer vision — YOLO + TensorRT deployment, 500K-image dataset curation</sub></td></tr>
</table>

<br />

<sub>**02**</sub>
##  By the numbers

|  |  |  |
|:--|:--|:--|
| **10,000+** <br /> <sub>document embeddings indexed</sub> | **4 agents** <br /> <sub>orchestrated in one graph</sub> | **&lt;3 sec** <br /> <sub>end-to-end query resolution</sub> |
| **5,000** <br /> <sub>curated SFT samples</sub> | **2 models** <br /> <sub>fine-tuned on a single GPU</sub> | **500K+** <br /> <sub>images curated &amp; labelled</sub> |

<br />

<sub>**03**</sub>
##  Selected work

<table>
<tr>
<td width="50%" valign="top">

#### Agentic AI Research Assistant
`Generative AI` · `RAG` · `Evaluation`

A production multi-agent RAG system — four specialized agents chained **research → retrieval → fact-check → synthesis**, with the whole path instrumented.

10,000+ embeddings · semantic search with reranking · RAGAS scoring · Redis caching · WebSocket streaming · guardrails · MLflow tracking

<sub>`LangGraph` `RAGAS` `FastAPI` `Redis` `ChromaDB` `Docker`</sub>

[**Open repository →**](https://github.com/NAME-NikhilPatil/agentic-ai-research-assistant)

</td>
<td width="50%" valign="top">

#### Gemma 4 · Instruction Tuning
`Fine-tuning` · `QLoRA` · `Data curation`

Fine-tuned **Gemma 4 E2B IT** with QLoRA + PEFT to turn a bare topic into a tight, hook-first short-form script.

5,000 samples · **leak-free grouped splits** · automated cleaning · conversational JSONL generation · reproducible eval

<sub>`Gemma 4` `QLoRA` `PEFT` `TRL` `Transformers`</sub>

[**Open repository →**](https://github.com/NAME-NikhilPatil/gemma4-e2b-tech-shorts-finetuning)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Llama 3.2 · Code Generation
`Fine-tuning` · `Benchmarking`

Fine-tuned **Meta Llama 3.2 1B** with 4-bit QLoRA on a single **Tesla T4** — then held it to HumanEval `pass@1` and `pass@10` instead of cherry-picked samples.

<sub>`Llama 3.2` `PyTorch` `TRL` `HumanEval` `bitsandbytes`</sub>

[**Open repository →**](https://github.com/NAME-NikhilPatil/Llama-3.2-1B)

</td>
<td width="50%" valign="top">

#### Retail Vision Pipeline
`MLOps` · `Computer vision` · `Deployment`

End-to-end CV deployment: 500K-image curation → YOLO training → TensorRT compilation → containerized inference on constrained hardware, cutting checkout time ~30%.

<sub>`YOLO` `TensorRT` `ONNX` `OpenCV` `Docker`</sub>

[**Browse all repositories →**](https://github.com/NAME-NikhilPatil?tab=repositories)

</td>
</tr>
</table>

<br />

<sub>**04**</sub>
##  How a model gets to production

```mermaid
%%{init:{'theme':'base','themeVariables':{'primaryColor':'#161B22','primaryTextColor':'#F2F5F8','primaryBorderColor':'#E9C46A','lineColor':'#E76F51','secondaryColor':'#1C2128','tertiaryColor':'#0D1117','fontFamily':'ui-monospace, SFMono-Regular, Consolas, monospace','fontSize':'13px'}}}%%
flowchart LR
    A([raw data]) --> B[curate · dedupe<br/>leak-free splits]
    B --> C[fine-tune<br/>QLoRA · PEFT · TRL]
    C --> D[quantize<br/>4-bit / TensorRT]
    D --> E{eval gate<br/>RAGAS · HumanEval · mAP}
    E -- below threshold --> C
    E -- passes --> F[serve<br/>FastAPI + Docker]
    F --> G[[Azure ML / Kubernetes]]
    G --> H([observe<br/>MLflow · traces · latency])
    H -.->|drift or regression| B
```

<br />

<sub>**05**</sub>
##  Toolkit

| | |
|:--|:--|
| **Generative AI** | `LangGraph` `LangChain` `Transformers` `PEFT` `TRL` `bitsandbytes` `vLLM` |
| **Retrieval** | `ChromaDB` `FAISS` `RAGAS` `Redis` `sentence-transformers` |
| **ML & Vision** | `Python` `PyTorch` `TensorFlow` `Keras` `scikit-learn` `OpenCV` `ONNX` `TensorRT` |
| **MLOps & Cloud** | `Azure ML` `MLflow` `Docker` `Kubernetes` `FastAPI` `GitHub Actions` `Git` |
| **Data** | `NumPy` `Pandas` `PostgreSQL` `MySQL` |

<br />

<sub>**06**</sub>
##  What I'm working on now

**Evaluation-first agents** — treating RAGAS scores, traces, and regression suites as release gates rather than dashboards.
**Small-model economics** — how far QLoRA on compact open models gets you before a frontier API is worth the bill.
**Reproducible pipelines** — one command from raw data to a registered, versioned, rollback-able model.
**Serving efficiency** — quantization, batching, and caching, so latency and cost survive real traffic.

<br />

<sub>**07**</sub>
##  Activity

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=NAME-NikhilPatil&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=E9C46A&text_color=8B949E&icon_color=E76F51" alt="GitHub statistics for NAME-NikhilPatil" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NAME-NikhilPatil&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=E9C46A&text_color=8B949E" alt="Most used languages" />

<img src="https://github-readme-streak-stats.demolab.com/?user=NAME-NikhilPatil&hide_border=true&background=0D1117&stroke=21262D&ring=E9C46A&fire=E76F51&currStreakLabel=E9C46A&sideLabels=8B949E&dates=5C6570" alt="Contribution streak" />

</div>

<br />

<div align="center">

<img src="https://raw.githubusercontent.com/NAME-NikhilPatil/NAME-NikhilPatil/output/snake.svg" alt="Contribution graph animation" />

<br /><br />

<sub>· · ·</sub>

<br />

**Let's build something that survives contact with production.**

<sub>[LinkedIn](https://www.linkedin.com/in/nikhilsatyawanpatil/) · [Email](mailto:nikhilsatyawanpatil@gmail.com) · [YouTube](https://www.youtube.com/channel/UCpakmXio90uAd4RBZqimG8Q) · [Instagram](https://www.instagram.com/nikhilpatil.ai/)</sub>

</div>
