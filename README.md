<div align="center">

<img src="./assets/header.svg" width="100%" alt="Nikhil Patil. Generative AI, MLOps, Machine Learning. Mumbai, India. Open to work." />

<br />

<a href="https://www.linkedin.com/in/nikhilsatyawanpatil/"><img src="https://img.shields.io/badge/LinkedIn-1C2128?style=for-the-badge&logo=linkedin&logoColor=E9C46A&labelColor=0D1117" alt="LinkedIn" /></a>
<a href="mailto:nikhilsatyawanpatil@gmail.com"><img src="https://img.shields.io/badge/Email-1C2128?style=for-the-badge&logo=gmail&logoColor=E9C46A&labelColor=0D1117" alt="Email" /></a>
<a href="https://www.youtube.com/channel/UCpakmXio90uAd4RBZqimG8Q"><img src="https://img.shields.io/badge/YouTube-1C2128?style=for-the-badge&logo=youtube&logoColor=E9C46A&labelColor=0D1117" alt="YouTube" /></a>
<a href="https://www.instagram.com/nikhilpatil.ai/"><img src="https://img.shields.io/badge/Instagram-1C2128?style=for-the-badge&logo=instagram&logoColor=E9C46A&labelColor=0D1117" alt="Instagram" /></a>

<br />

<sub>I build generative AI that keeps working after the demo, and I teach AI from first principles to Indian students.</sub>

</div>

<br />

> ### 🟢 Open to AI / ML Engineer roles
>
> **Generative AI · LLM Engineering · MLOps · Machine Learning** &nbsp;|&nbsp; full-time, Mumbai or remote
>
> If you're shipping an AI product that has to keep working *after* the demo, I'd like to hear about it.
> [**Start a conversation →**](https://www.linkedin.com/in/nikhilsatyawanpatil/)

<br />

<sub>**01**</sub>
## Who I am

I'm an AI/ML Engineer in Mumbai who builds **generative AI systems that hold up in production**: retrieval and agent pipelines that are evaluated rather than eyeballed, fine-tuned open models that fit real hardware budgets, and the MLOps scaffolding that keeps both reproducible.

My bias is toward the unglamorous half of the work: evaluation harnesses, tracing, caching, guardrails, and deploy pipelines. A model that scores well once is a demo. A model you can re-train, re-measure, and roll back is a product.

Outside the terminal I host **AI But Simple**, a 28 episode Hinglish podcast that explains AI from first principles to Indian CS students.

<table>
<tr><td width="140"><sub><b>GENERATIVE&nbsp;AI</b></sub></td><td>Multi-agent RAG with LangGraph · semantic search &amp; reranking · RAGAS evaluation · guardrails · streaming</td></tr>
<tr><td><sub><b>FINE&#8209;TUNING</b></sub></td><td>QLoRA · PEFT · TRL on Gemma 4 and Llama 3.2 · leak-free dataset splits · HumanEval-style benchmarking</td></tr>
<tr><td><sub><b>MLOPS</b></sub></td><td>Azure ML · MLflow tracking &amp; registry · Docker · Kubernetes · FastAPI · reproducible training pipelines</td></tr>
<tr><td><sub><b>VISION</b></sub></td><td>Production computer vision: YOLO + TensorRT deployment, 500K-image dataset curation</td></tr>
</table>

<br />

<sub>**02**</sub>
## By the numbers

<img src="./assets/numbers.svg" width="100%" alt="10,000+ document embeddings indexed for retrieval. 4 specialized agents in one LangGraph. Under 3 seconds end-to-end query resolution. 5,000 curated SFT samples for instruction tuning. 2 open models fine-tuned on a single GPU. 500K+ images curated and labelled. About 30% less checkout time from the vision pipeline. 28 podcast episodes teaching AI in Hinglish." />

<br />

<sub>**03**</sub>
## Selected work

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 Agentic AI Research Assistant
`Generative AI` · `RAG` · `Evaluation`

A production multi-agent RAG system: four specialized agents chained **research → retrieval → fact-check → synthesis**, with the whole path instrumented.

10,000+ embeddings · semantic search with reranking · RAGAS scoring · Redis caching · WebSocket streaming · guardrails · MLflow tracking

<sub>`LangGraph` `RAGAS` `FastAPI` `Redis` `ChromaDB` `Docker`</sub>

[**Open repository →**](https://github.com/NikhilPatilAI/agentic-ai-research-assistant)

</td>
<td width="50%" valign="top">

#### ✍️ Gemma 4 · Instruction Tuning
`Fine-tuning` · `QLoRA` · `Data curation`

Fine-tuned **Gemma 4 E2B IT** with QLoRA + PEFT to turn a bare topic into a tight, hook-first short-form script.

5,000 samples · **leak-free grouped splits** · automated cleaning · conversational JSONL generation · reproducible eval

<sub>`Gemma 4` `QLoRA` `PEFT` `TRL` `Transformers`</sub>

[**Open repository →**](https://github.com/NikhilPatilAI/gemma4-e2b-tech-shorts-finetuning)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💻 Llama 3.2 · Code Generation
`Fine-tuning` · `Benchmarking`

Fine-tuned **Meta Llama 3.2 1B** with 4-bit QLoRA on a single **Tesla T4**, then held it to HumanEval `pass@1` and `pass@10` instead of cherry-picked samples.

<sub>`Llama 3.2` `PyTorch` `TRL` `HumanEval` `bitsandbytes`</sub>

[**Open repository →**](https://github.com/NikhilPatilAI/Llama-3.2-1B)

</td>
<td width="50%" valign="top">

#### 🛒 Retail Vision Pipeline
`MLOps` · `Computer vision` · `Deployment`

End-to-end CV deployment: 500K-image curation → YOLO training → TensorRT compilation → containerized inference on constrained hardware, cutting checkout time ~30%.

<sub>`YOLO` `TensorRT` `ONNX` `OpenCV` `Docker`</sub>

<sub>🔒 Code is private.</sub>

</td>
</tr>
</table>

<p align="center">
<sub>Also shipped: <a href="https://github.com/NikhilPatilAI/tr-alert-gpt54-nano"><b>tr-alert</b></a>, a financial results alert worker (NSE/BSE scrapers → validation → GPT 5.4 nano → Telegram) &nbsp;·&nbsp; <a href="https://github.com/NikhilPatilAI?tab=repositories"><b>Browse all repositories →</b></a></sub>
</p>

<br />

<sub>**04**</sub>
## How a model gets to production

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
## Teaching AI in public

<a href="https://www.youtube.com/channel/UCpakmXio90uAd4RBZqimG8Q"><img src="./assets/podcast.svg" width="100%" alt="AI But Simple. A 28 episode Hinglish podcast by Nikhil Patil that rebuilds one AI idea per episode from first principles, for Indian CS students. Play on YouTube." /></a>

Plenty of engineers can build with AI. Far fewer can explain it. **AI But Simple** takes one idea per episode and rebuilds it from first principles, in Hinglish, for Indian CS students who are tired of jargon and hype. The same approach now continues as short explainers on Instagram Reels and YouTube Shorts.

Teaching is also how I test my own understanding. If I can't explain it simply, I don't understand it well enough yet.

<sub>▶ [YouTube](https://www.youtube.com/channel/UCpakmXio90uAd4RBZqimG8Q) &nbsp;·&nbsp; 📸 [Instagram](https://www.instagram.com/nikhilpatil.ai/)</sub>

<br />

<sub>**06**</sub>
## Toolkit

<img src="./assets/stack.svg" width="100%" alt="Tech stack: Python, PyTorch, TensorFlow, scikit-learn, OpenCV, FastAPI, Docker, Kubernetes, Azure, GitHub Actions, Redis, PostgreSQL, MySQL, Git, Linux" />

| | |
|:--|:--|
| **Generative AI** | `LangGraph` `LangChain` `Transformers` `PEFT` `TRL` `bitsandbytes` `vLLM` |
| **Retrieval** | `ChromaDB` `FAISS` `RAGAS` `Redis` `sentence-transformers` |
| **ML & Vision** | `Python` `PyTorch` `TensorFlow` `Keras` `scikit-learn` `OpenCV` `ONNX` `TensorRT` |
| **MLOps & Cloud** | `Azure ML` `MLflow` `Docker` `Kubernetes` `FastAPI` `GitHub Actions` `Git` |
| **Data** | `NumPy` `Pandas` `PostgreSQL` `MySQL` |

<br />

<sub>**07**</sub>
## What I'm working on now

- 🧪 **Evaluation-first agents:** treating RAGAS scores, traces, and regression suites as release gates rather than dashboards.
- ⚖️ **Small-model economics:** how far QLoRA on compact open models gets you before a frontier API is worth the bill.
- 🔁 **Reproducible pipelines:** one command from raw data to a registered, versioned, rollback-able model.
- ⚡ **Serving efficiency:** quantization, batching, and caching, so latency and cost survive real traffic.

<br />

<sub>**08**</sub>
## Activity

<div align="center">

<img src="./profile/top-langs.svg" alt="Most used languages across public repositories" />

<br />

<img src="./profile/snake.svg" width="100%" alt="Contribution graph being eaten by a snake" />

</div>

<br />

<div align="center">

<img src="./assets/footer.svg" width="100%" alt="Let's build something that survives contact with production." />

<br />

<sub>[LinkedIn](https://www.linkedin.com/in/nikhilsatyawanpatil/) &nbsp;·&nbsp; [Email](mailto:nikhilsatyawanpatil@gmail.com) &nbsp;·&nbsp; [YouTube](https://www.youtube.com/channel/UCpakmXio90uAd4RBZqimG8Q) &nbsp;·&nbsp; [Instagram](https://www.instagram.com/nikhilpatil.ai/)</sub>

<br />

<img src="https://komarev.com/ghpvc/?username=NAME-NikhilPatil&style=flat-square&color=E9C46A&labelColor=0D1117&label=profile%20views" alt="Profile views" />

</div>
