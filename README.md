<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2800&pause=900&color=00F0FF&center=true&vCenter=true&width=720&lines=Hey%2C+I'm+Dhruv+Goyal+%F0%9F%91%8B;AI+Engineer+%40+The+Economic+Times;I+build+AI+that+makes+and+understands+video;Generative+Video+%C2%B7+Computer+Vision+%C2%B7+Agents" alt="Dhruv Goyal" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhruvg0yal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruvg0yal)
[![X](https://img.shields.io/badge/X-@dhruvg0yal-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/dhruvg0yal)
[![Kaggle](https://img.shields.io/badge/Kaggle-dhruvg0yal-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/dhruvg0yal)
[![Paper](https://img.shields.io/badge/Paper-AIJR_2025-8A2BE2?style=for-the-badge&logo=googlescholar&logoColor=white)](https://doi.org/10.21467/proceedings.7.6.51)

</div>

---

### 👋 About me

- 🎬 **AI Engineer at The Economic Times (Times Internet).** I build and run the company's in-house generative-AI video platform on my own, end to end, like a one-person startup inside a large company.
- 🧪 **Video AI all year.** Before ET, at **Moleculyst**, I built a pipeline that turns one image and a prompt into a **physics-accurate video**, and an agent that edits images on its own.
- 🧠 **What I enjoy most:** computer vision on video, AI agents, fast and cheap inference, and evaluation that catches what models get wrong.
- 📄 **Published** a paper on Transformers replacing RNNs and CNNs (*AIJR Proceedings*, 2025).
- 🎓 **B.Tech, Artificial Intelligence & Machine Learning**, GGSIPU (2026).

---

### 🎥 What I build: generative video, end to end

> A brief goes in; a finished, checked video comes out. One shared engine serves many different kinds of video - vertical shorts, long explainers, ads in every aspect ratio, clips cut from recordings, and Hindi-English stories.

```
  BRIEF ──► SCRIPT & SHOT PLAN ──► IMAGES ──► VIDEO DIFFUSION ──► VOICE & MUSIC ──► AUTOMATED EDIT ──► QUALITY CHECKS ──► DELIVERY
            LLMs                   image      self-hosted on      speech synthesis  an editor AI        lip-sync, identity,
                                   models     a cloud GPU fleet   + music models    agents can drive    motion, VLM judge
```

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🧩 LLMOps &amp; agents</h4>
      <ul>
        <li>One gateway over many LLM, image, video and voice models, with fallback, caching, cost tracking and spend limits</li>
        <li>An automated video editor exposed as an <b>MCP server</b>, so AI agents can plan, cut and review a video</li>
        <li>Multi-agent research pipelines with automatic source checking</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>👁️ Computer vision &amp; evaluation</h4>
      <ul>
        <li>Phone-screen tracking in OpenCV (RANSAC, Lucas-Kanade, homography) and camera-motion estimation</li>
        <li>Automatic checks on every generated take: lip-sync, face identity, frozen frames, and a vision-language judge</li>
        <li>Frame-by-frame analysis of reference videos to learn how great videos are cut</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ Inference</h4>
      <ul>
        <li>Video diffusion self-hosted on a cloud GPU fleet that scales up and down with the work</li>
        <li>Quantized builds benchmarked across GPU generations; <b>24% less compute per video</b></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🔊 Speech &amp; audio</h4>
      <ul>
        <li>Forced alignment for word-timed captions in Hindi and English</li>
        <li>Speech-quality scoring that picks the best clean-up for every clip, and music cut on its beats</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🌊 Before that: physics-accurate video (Moleculyst)

- **Single image + text → physics-accurate video:** Grounding DINO, SAM2 and PartSAM find the objects and their parts, material recognition works out what each part is made of, and an **MPM** physics simulation decides how it moves before diffusion renders the video.
- **Material recognition** reproduced from an ICCV 2025 paper (ResNet50 + graph attention over a material taxonomy).
- **Agent Banana**, an image-editing agent (below), shipped on Hugging Face Spaces.

---

### 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/Agent-Image-Editing">🍌 Agent Banana - agentic image editing</a></h4>
      <ul>
        <li>ReAct agent: Gemini picks the next tool each step (find, crop, edit, blend, check) and retries until a VLM critic passes the edit</li>
        <li>Ground-first editing: Florence-2 finds the target, only that crop is regenerated, Laplacian-pyramid blending keeps the rest untouched</li>
        <li>Live step-by-step streaming, Docker, unit tests</li>
      </ul>
      <p><code>Python</code> · <code>Florence-2</code> · <code>Gemini</code> · <code>OpenCV</code> · <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/CodeoGraph">📊 CodeoGraph - RAG over codebases</a></h4>
      <ul>
        <li>Tree-sitter AST chunking, Gemini embeddings in Pinecone and hybrid dense + BM25 retrieval, so answers cite the repo's own code</li>
        <li>A symbol-dependency graph traces what a change touches, and an LLM PR reviewer grades the risk of every affected file</li>
      </ul>
      <p><code>Python</code> · <code>FastAPI</code> · <code>Tree-sitter</code> · <code>Pinecone</code> · <code>NetworkX</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/GPT-2">🧠 GPT-2 from scratch</a></h4>
      <ul>
        <li>GPT-2 rebuilt from first principles in PyTorch: causal self-attention, learned positions, weight tying</li>
        <li>Pretrained the 124M model, fine-tuned the 355M model on instructions, evaluated with an LLM judge</li>
      </ul>
      <p><code>PyTorch</code> · <code>Transformers</code> · <code>Ollama</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/dhruvg0ya1/SyncPixel">🎵 SyncPixel - photo to playlist</a></h4>
      <ul>
        <li>DeepFace emotion recognition plus BLIP captioning and visual Q&amp;A read the mood of a photo</li>
        <li>The mood becomes Spotify audio targets (valence, energy, danceability) for a matching playlist</li>
      </ul>
      <p><code>Python</code> · <code>DeepFace</code> · <code>BLIP</code> · <code>Spotify API</code></p>
    </td>
  </tr>
</table>

<p align="center">More: <a href="https://github.com/dhruvg0ya1/IBM-Employee-Salary-Pred">salary prediction</a> · <a href="https://github.com/dhruvg0ya1/VOIS_AICTE_Oct2025_DhruvGoyal">NYC Airbnb analysis</a> · <a href="https://github.com/dhruvg0ya1/VOIS_AICTE_Oct2025_MajorProject_DhruvGoyal">Netflix content analysis</a> · <a href="https://github.com/dhruvg0ya1/AI-Guest-Experience-Infosys">AI guest experience</a></p>

---

### 🛠️ Tech I work with

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,opencv,fastapi,docker,linux,bash,git,js,mysql,mongodb,sqlite&perline=12" alt="Tech stack" />

</div>

| Area | Tools |
|:---|:---|
| **Generative AI & agents** | LLMs (Gemini, Claude, open models), RAG, ReAct agents, MCP, multi-agent pipelines, LLM / VLM-as-judge |
| **Vision & video** | OpenCV, Grounding DINO, SAM2, Florence-2, InsightFace, SyncNet, video diffusion, ComfyUI |
| **ML & deep learning** | PyTorch, Hugging Face, scikit-learn, XGBoost, quantization, model benchmarking |
| **Speech & audio** | Whisper, forced alignment, speech synthesis, speech-quality scoring, FFmpeg |
| **Data & infra** | Python, SQL, Pandas, Pinecone, FastAPI, Docker, Linux, cloud GPUs, pytest, Git |

---

### 📄 Publication

<p align="center">
  <b>"Breaking Neural Barriers with Transformers Replacing RNN and CNN"</b><br/>
  <i>AIJR Proceedings</i>, Vol. 7, No. 6, 2025<br/>
  <a href="https://doi.org/10.21467/proceedings.7.6.51">Read the paper (DOI: 10.21467/proceedings.7.6.51)</a>
</p>

---

### 📊 GitHub activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=dhruvg0ya1&theme=tokyonight&hide_border=true" alt="GitHub streak" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=dhruvg0ya1&theme=tokyonight" alt="Profile details" width="96%" />

<br/>

<img src="https://raw.githubusercontent.com/dhruvg0ya1/dhruvg0ya1/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" />

</div>

---

<div align="center">

**I build AI that sees, edits and makes video.** Always happy to talk about generative video, computer vision and agents.<br/>
👉 [Connect on LinkedIn](https://linkedin.com/in/dhruvg0yal)

</div>
