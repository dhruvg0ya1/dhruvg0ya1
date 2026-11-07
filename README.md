<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2800&pause=900&color=00F0FF&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Dhruv+Goyal+%E2%9A%A1;AI+Product+Engineer+%40+Times+Internet;Generative+AI+%40+The+Economic+Times;LLMs+%C2%B7+Multi-Agent+Systems+%C2%B7+Vision" alt="Dhruv Goyal Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhruvg0yal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruvg0yal)
[![X / Twitter](https://img.shields.io/badge/X-@dhruvg0yal-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/dhruvg0yal)
[![Email](https://img.shields.io/badge/Email-dhruvg096@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhruvg096@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-dhruvg0yal-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/dhruvg0yal)

</div>

---

### ⚡ Executive Snapshot

- 🏢 **AI Engineer @ Times Internet (The Economic Times)**: running ET's in-house generative-AI video platform as a **one-person startup** - eight video products on one engine, built to make **~300 AI shorts a day** at **under Rs 55 a finished minute**.
- 🎥 **Video AI all year**: before ET, at **Moleculyst**, a pipeline that turns one image + a prompt into a **physics-accurate video** (Grounding DINO, SAM2, PartSAM, material recognition, MPM), and a ReAct image-editing agent.
- 🔬 **Published Researcher**: *"Breaking Neural Barriers with Transformers Replacing RNN and CNN"*, *AIJR Proceedings*, 2025 ([DOI: 10.21467/proceedings.7.6.51](https://doi.org/10.21467/proceedings.7.6.51)).
- 🛠️ **What I like building**: computer vision on video, agents (ReAct, MCP), GPU and CPU inference, and evaluation that catches what models get wrong.
- 🎓 **Education**: B.Tech in Artificial Intelligence & Machine Learning @ **GGSIPU**, Delhi NCR.

---

### 🎬 ETai - The Economic Times' in-house video-AI platform

> *A brief goes in, a finished and checked video comes out - for many different kinds of video, on one shared engine.*

```
 BRIEF -> SCRIPT & SHOTS -> AI PICTURES -> VIDEO DIFFUSION -> VOICE & MUSIC -> AUTOMATED EDIT -> QC -> DELIVERY
          Gemini            Gemini batch   MiniMax H3 on a    ElevenLabs,      planner + MCP    SyncNet, faces,
                                           self-hosted fleet  ACE-Step         server (20 tools) camera motion, VLM judge
```

**Eight products on one engine** - ET TV shorts and long-form explainers, YouTube long-form, marketing ads in every shape (9:16, 1:1, 4:5, 16:9), clips cut from ET Masterclass recordings, Hinglish micro-drama stories, ET Health and marathon reels, and **ETai Video Studio**, the portal where any team at ET asks for a video.

- **Scale**: built for ~300 AI shorts a day, at under Rs 55 a finished minute.
- **Inference**: video diffusion self-hosted on a cloud GPU fleet; quantized builds and GPU generations benchmarked, cutting compute per video by 24%.
- **Computer vision and evaluation**: phone-screen tracking, camera-motion estimation, lip-sync and face-identity checks and a vision-language judge on every take.
- **Agents and LLMOps**: the automated editor is an MCP server AI agents can drive; one gateway runs 16 LLM, image, video and voice models with fallback, caching and spend limits.

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
        <li>ReAct loop: Gemini 2.5 Flash picks from 9 tools, up to 3 self-correcting attempts.</li>
        <li>Florence-2 grounding re-ranked by an LLM spatial advisor; only the crop is edited.</li>
        <li>Laplacian pyramid blending, a VLM critic and a seam detector check every edit.</li>
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
      <h4><a href="https://github.com/dhruvg0ya1/FIT-HAPPENS-NEW">💪 Fit Happens</a></h4>
      <p><b>Full-Stack AI Health & Adaptive Coach</b></p>
      <ul>
        <li>Interactive workout recommendations and cognitive brain gym routines.</li>
        <li>Gemini 2.5 Flash conversational assistant with adaptive workout tracking.</li>
        <li>Production React frontend with Firebase authentication and real-time database.</li>
      </ul>
      <p><code>React</code> · <code>TypeScript</code> · <code>Gemini</code> · <code>Firebase</code></p>
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
| **Core Languages** | `Python` · `SQL` · `Bash` · `JavaScript` |
| **Deep Learning & Inference** | `PyTorch` · `TensorFlow` · `Hugging Face Transformers` · `ONNX Runtime` · `ComfyUI` · `Ollama` · `CUDA` |
| **LLMs & Agents** | `Google Gemini` · `OpenAI API` · `Anthropic Claude` · `LangChain` · `MCP` · `ReAct agents` |
| **Computer Vision & Multimodal** | `OpenCV` · `Grounding DINO` · `SAM2` · `Florence-2` · `InsightFace` · `SyncNet` · `BLIP` · `DeepFace` · `MiniMax H3 video diffusion` |
| **Audio & Speech** | `OpenAI Whisper` · `MMS forced aligner` · `ElevenLabs` · `ACE-Step` · `FFmpeg` · `EBU-R128 loudness` |
| **Vector DBs & Retrieval** | `Pinecone` · `BM25` · `Tree-sitter AST` |
| **Infrastructure** | `Colab GPU fleets (A100, RTX PRO 6000)` · `Linux servers` · `Docker` · `FastAPI` · `AWS` · `Git` |

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
📫 Let's connect: **dhruvg096@gmail.com** · [LinkedIn](https://linkedin.com/in/dhruvg0yal)

</div>
