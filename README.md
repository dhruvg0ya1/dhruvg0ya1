<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=2800&pause=900&color=00F0FF&center=true&vCenter=true&width=780&lines=Hey%2C+I'm+Dhruv+Goyal+%E2%9A%A1;AI+Product+Engineer+%40+Times+Internet;Building+Production+Generative+AI+%40+The+Economic+Times;Co-Founder+%40+PickleTech+Advisory+(fakepickle.tech);92K+LOC+%C2%B7+43+Models+%C2%B7+13+Providers+%C2%B7+808+Tests" alt="Dhruv Goyal Typing SVG" />

<br/>

[![Website](https://img.shields.io/badge/PickleTech%20Advisory-fakepickle.tech-00F0FF?style=for-the-badge&logo=googlechrome&logoColor=black)](https://fakepickle.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhruvg0yal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruvg0yal)
[![X / Twitter](https://img.shields.io/badge/X-@dhruvg0yal-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/dhruvg0yal)
[![Email](https://img.shields.io/badge/Email-dhruvg096@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhruvg096@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-dhruvg0yal-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/dhruvg0yal)

</div>

---

### ⚡ Executive Snapshot

- 🏢 **AI Product Engineer @ Times Internet**: Sole engineer owning the **92,000 LOC** production generative media pipeline powering AI video at ***The Economic Times***.
- 🚀 **Co-Founder & Head of Applied AI @ [PickleTech Advisory](https://fakepickle.tech)**: Engineering high-performance enterprise AI agent systems, speculative model routers, and sovereign infrastructure alongside co-founder [Harsh Mistry](https://github.com/fakepickle).
- 📉 **Production Impact**: Slashed per-episode generative inference costs by **58%** (₹9,756 → ₹5,960) with a **4x throughput speedup** and an automated **808-test unattended QC gate**.
- 🔬 **Published Researcher**: Author of *"Breaking Neural Barriers with Transformers Replacing RNN and CNN"*, *AIJR Proceedings*, 2025 ([DOI: 10.21467/proceedings.7.6.51](https://doi.org/10.21467/proceedings.7.6.51)).
- 🎓 **Education**: B.Tech in Artificial Intelligence & Machine Learning @ **GGSIPU**, Delhi NCR.

---

### 🎬 Production AI Video Architecture @ The Economic Times (ETai)

> *Architected and single-handedly maintained the 92K LOC generative media pipeline serving India's premier financial daily.*

```
┌──────────────────────────────────────────────────────────────────────────────────────────────┐
│                  THE ECONOMIC TIMES (ETai) AUTONOMOUS GENERATIVE PIPELINE                    │
├──────────────────────────────────────────────────────────────────────────────────────────────┤
│  [1. SCRIPT / BEATS]  ──►  [2. IMAGE GEN]    ──►  [3. SPEECH / TTS]   ──►  [4. VIDEO DIFF]   │
│   Gemini 2.5 Flash          Gemini Batch API       Whisper Aligned          ComfyUI A100     │
│   56-Beat Story Arc         Consistent Actors      Neural Voiceprint        Runway Gen-3/Veo │
│                                                                                              │
│  ──►  [5. LIP-SYNC]   ──►  [6. AUDIO MIX]    ──►  [7. QC EVAL GATE]   ──►  [4K PRODUCTION]   │
│       Sync Dub Model        SFX / Beats / Duck      808 Automated Tests       Hinglish 9:16  │
│       Face Motion 60fps     EBU-R128 Loudness       79% Story Fidelity        45s-120s Reels │
└──────────────────────────────────────────────────────────────────────────────────────────────┘
```

#### 📌 6 Core Production Applications in Production:
1. **MicroDramas**: Hinglish 9:16 vertical narrative series (~45 min cut into 45–120s episodes) with consistent character embeddings and multi-beat story arcs.
2. **ETHealthVideos**: 60-second running & fitness vertical reels featuring an AI-synthesized coach for marathon preparation.
3. **Masterclass (Clipper Engine)**: Multi-speaker long-form video intelligence that automatically identifies 30s hooks and extracts 1–2 minute high-engagement educational clips.
4. **ETAIWork**: 10-minute long-form explainer engine with automated A/B evaluation harnesses.
5. **MetaCreatives**: Ad creative & prompt generation kits for Times Internet marathon campaigns.
6. **MarketingVideos**: 45s product promo reels with animated kinetic typography and brand-compliant safe zones.

#### 📊 Production Engineering Benchmarks:
| Metric | Before Optimization | After Optimization | Engineering Lever |
|:---|:---:|:---:|:---|
| **Cost per Episode** | **₹9,756** | **₹5,960 (-58%)** | Gemini Batch API + Speculative Cloud/Local routing |
| **360-Job Render Time** | **72 hours** | **18 hours (4.0x)** | Parallelized async queues + A100 batch inference |
| **GPU Cluster Cost** | ₹ Cloud Hourly | **₹0 (Self-Hosted)** | Dedicated ComfyUI cluster on A100-40GB PCIe |
| **Quality Gate** | Manual QA | **808 Automated Tests** | Unattended `pytest` test suite with audio/video asserts |
| **Model Abstraction** | Hardcoded APIs | **43 Configs / 13 Providers** | 5 typed interfaces with zero vendor lock-in |

---

### 🚀 Featured Systems & Open-Source Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/CodeoGraph">📊 CodeoGraph</a></h4>
      <p><b>Enterprise Codebase Intelligence & PR Review Agent</b></p>
      <ul>
        <li>Incremental Tree-sitter AST parsing across polyglot repositories.</li>
        <li>Hybrid BM25 + dense vector retrieval (Pinecone) for semantic dependency discovery.</li>
        <li>Automated PR impact analysis & regression detection.</li>
      </ul>
      <p><code>Python</code> · <code>Tree-sitter</code> · <code>FastAPI</code> · <code>Pinecone</code> · <code>LangChain</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/Agent-Image-Editing">🍌 Agent Banana (Agentic Image Editing)</a></h4>
      <p><b>Visual Editing via Layer Decomposition</b></p>
      <ul>
        <li>Florence-2 open-vocabulary grounding for pixel-precise bounding boxes.</li>
        <li>Autonomous ReAct loop with Gemini VLM critic for visual verification.</li>
        <li>Laplacian pyramid blending for seamless multi-layer artifact removal.</li>
      </ul>
      <p><code>PyTorch</code> · <code>Florence-2</code> · <code>Gemini VLM</code> · <code>OpenCV</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/GPT-2">🧠 GPT-2 from Scratch</a></h4>
      <p><b>Foundational Causal Transformer Reproduction</b></p>
      <ul>
        <li>Built from scratch in pure PyTorch: multi-head causal self-attention and weight tying.</li>
        <li>Pretrained 124M base model and fine-tuned 355M checkpoint.</li>
        <li>Evaluated via Llama-3-as-Judge automated rubric.</li>
      </ul>
      <p><code>PyTorch</code> · <code>CUDA</code> · <code>Transformers</code> · <code>Deep Learning</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://fakepickle.tech">🛡️ PickleTech Advisory</a></h4>
      <p><b>High-Performance Systems & Enterprise AI Consulting</b></p>
      <ul>
        <li>Co-founded with Harsh Mistry (IIIT-Delhi).</li>
        <li>Flagship product <a href="https://driftnet.fakepickle.tech">Driftnet</a>: sovereign network anomaly detection daemon.</li>
        <li>Enterprise generative AI deployment, model routing, and cost reduction sprints.</li>
      </ul>
      <p><code>Go</code> · <code>Python</code> · <code>eBPF</code> · <code>React</code> · <code>Cloud Infra</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/SyncPixel">🎵 SyncPixel</a></h4>
      <p><b>Multimodal Emotion-to-Audio Recommendation</b></p>
      <ul>
        <li>Facial affect extraction using DeepFace + scene captioning via BLIP.</li>
        <li>Emotion vector mapping to Spotify Audio Features API via Gemini.</li>
      </ul>
      <p><code>PyTorch</code> · <code>BLIP</code> · <code>DeepFace</code> · <code>Spotify API</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/Aevom">✉️ Aevom</a></h4>
      <p><b>Autonomous Cold-Outreach Generation Engine</b></p>
      <ul>
        <li>Automated LinkedIn profile scraping and disk caching.</li>
        <li>Strict structured JSON extraction with automated schema fallback healing.</li>
        <li>Gmail OAuth2 integration with state-machine follow-up tracking.</li>
      </ul>
      <p><code>Streamlit</code> · <code>HuggingFace</code> · <code>Gmail OAuth2</code></p>
    </td>
  </tr>
</table>

---

### 🛠️ Production Technology Stack

<div align="center">

| Domain | Technologies & Frameworks |
|:---|:---|
| **Core Languages** | `Python (Advanced)` · `SQL / PostgreSQL` · `C++` · `JavaScript / TypeScript` · `Bash` |
| **Deep Learning & Inference** | `PyTorch` · `TensorFlow` · `CUDA / TensorRT` · `Hugging Face Transformers` · `vLLM` · `Ollama` · `ComfyUI` |
| **LLMs & Agent Frameworks** | `OpenAI API` · `Google Gemini 2.5` · `Anthropic Claude` · `LangChain` · `LlamaIndex` · `DSPy` |
| **Computer Vision & Multimodal** | `OpenCV` · `Florence-2` · `BLIP-2` · `Stable Diffusion / SDXL` · `Runway Gen-3` · `Veo` · `DeepFace` |
| **Audio & Speech Systems** | `OpenAI Whisper` · `ElevenLabs` · `FFmpeg (libav)` · `EBU-R128 Loudness Normalization` |
| **Vector DBs & Retrieval** | `Pinecone` · `ChromaDB` · `FAISS` · `BM25 (Rank-BM25)` · `Tree-sitter AST` |
| **Cloud & Infrastructure** | `NVIDIA A100 / H100 GPUs` · `AWS (S3, EC2, Lambda)` · `Docker` · `Redis` · `FastAPI` · `Git / GitHub Actions` |

</div>

---

### 🔬 Peer-Reviewed Research Publication

<p align="center">
  <b>📄 "Breaking Neural Barriers with Transformers Replacing RNN and CNN"</b><br/>
  <i>AIJR Proceedings</i>, Vol. 7, No. 6, 2025 · ISSN: 2582-3922<br/>
  <a href="https://doi.org/10.21467/proceedings.7.6.51"><b>🔗 Read Paper (DOI: 10.21467/proceedings.7.6.51)</b></a>
</p>

---

### 📊 GitHub Activity & Streak

<div align="center">

<a href="https://git.io/streak-stats">
  <img src="https://github-readme-streak-stats-green-five.vercel.app?user=dhruvg0ya1&theme=tokyonight&date_format=j%20M%5B%20Y%5D&card_width=750&card_height=180&hide_border=true" alt="Dhruv's GitHub Streak" />
</a>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=dhruvg0ya1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhruvg0ya1&layout=compact&theme=tokyonight&hide_border=true" width="48%" />

<br/><br/>

<img src="https://raw.githubusercontent.com/dhruvg0ya1/dhruvg0ya1/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" />

</div>

---

<div align="center">

**Open to Strategic AI Architecture Advisory · Enterprise GenAI Sprints · Principal Engineering Roles**  
📫 Let's connect: **dhruvg096@gmail.com** · [LinkedIn](https://linkedin.com/in/dhruvg0yal) · [fakepickle.tech](https://fakepickle.tech)

</div>
