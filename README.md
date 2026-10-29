<!-- header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0a0a0c,55:005757,100:00bfbf&text=Sahil%20Kumar&fontColor=e2e8f0&fontSize=58&fontAlignY=36&desc=AI%2FML%20engineer%20%C2%B7%20builds%20it%20from%20scratch%20once&descSize=18&descAlignY=58" alt="Sahil Kumar" width="100%"/>
</p>

<p align="center">
  <a href="https://www.sahilkumar.tech">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=900&color=00BFBF&center=true&vCenter=true&width=640&height=48&lines=%24+whoami+%E2%86%92+AI%2FML+engineer+in+India;I+build+ML+systems+that+hold+up+outside+the+notebook;model+%E2%86%92+pipeline+%E2%86%92+API+%E2%86%92+deploy+%E2%86%92+tests;Write+it+from+scratch+once.+See+what+the+library+hid.;It+works+on+my+4+GB+GPU.+Ship+it." alt="typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://www.sahilkumar.tech"><img src="https://img.shields.io/badge/sahilkumar.tech-0a0a0c?style=for-the-badge&logo=archlinux&logoColor=00bfbf" alt="website"/></a>
  <a href="https://www.linkedin.com/in/sahil-kumar-a1b148247"><img src="https://img.shields.io/badge/LinkedIn-0a0a0c?style=for-the-badge&logo=linkedin&logoColor=0A84FF" alt="LinkedIn"/></a>
  <a href="mailto:sahil115jangid@gmail.com"><img src="https://img.shields.io/badge/Email-0a0a0c?style=for-the-badge&logo=gmail&logoColor=BF5AF2" alt="email"/></a>
  <img src="https://img.shields.io/badge/status-open%20to%20ML%20%2F%20AI%20backend%20roles-30D158?style=for-the-badge&labelColor=0a0a0c" alt="open to work"/>
</p>

```text
sahil@archlinux ~ $ neofetch
                   -`                     sahil@archlinux
                  .o+`                    ---------------
                 `ooo/                    OS        Arch Linux x86_64 (yes, btw)
                `+oooo:                   Host      DCRUST, B.Tech ECE (AI/ML), final year
               `+oooooo:                  Role      AI/ML engineer
               -+oooooo+:                 Shell     zsh
             `/:-:++oooo+:                Editor    neovim + tmux
            `/++++/+++++++:               GPU       RTX 2050, 4 GB (everything has to fit)
           `/++++++++++++++:              Langs     Python, Go, C/C++, CUDA
          `/+++ooooooooooooo/`            Focus     speech, retrieval, on-device ML
         ./ooosssso++osssssso+`           Robotics  2x e-Yantra (IIT Bombay), Lead @ THINKBOTS
        .oossssso-````/ossssss+`          Building  an LLM serving engine from scratch
       -osssssso.      :ssssssso.         Uptime    final year, shipping
      :osssssss/        osssso+++.
     /ossssssss/        +ssssooo/-        ███ ███ ███ ███ ███ ███ ███
   `/ossssso+/:-        -:/+osssso+-
  `+sso+:-`                 `.-/+oso:
 `++:.                           `-/+/
 .`                                 `/
```

## `$ cat pipeline.md`

Every project goes the full distance. A notebook result is a hypothesis, not a product.

```mermaid
flowchart LR
    M["🧠 Model<br/>PyTorch · ONNX"] --> P["🔁 Pipeline<br/>FAISS · Kafka · DuckDB"]
    P --> A["⚡ API<br/>FastAPI · Pydantic"]
    A --> D["🚀 Deploy<br/>Docker · AWS"]
    D --> T["✅ Tests<br/>pytest · CI"]
    T -. "honest eval, not a demo" .-> M
    classDef box fill:#0a0a0c,stroke:#00bfbf,stroke-width:2px,color:#e2e8f0
    class M,P,A,D,T box
```

## `$ ls ~/featured`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/Sahiljangra115/Holmes">Holmes</a></h3>
      AI-content provenance detector. Fuses 4 independent signals (DeBERTa-v3, C2PA/EXIF, SynthID, image forensics) into a calibrated confidence with an uncertainty band, not a yes/no verdict.
      <br/><br/>
      <code>ONNX Runtime</code> <code>FastAPI</code> <code>AWS Lambda</code>
    </td>
    <td width="50%" valign="top">
      <h3>🖼️ <a href="https://github.com/Sahiljangra115/image-N">image-N</a></h3>
      Multimodal RAG with no framework glue. CLIP + FAISS two-stage retrieval, local Ollama LLMs, every stage readable top to bottom. Runs on a 4 GB GPU.
      <br/><br/>
      <code>CLIP</code> <code>FAISS</code> <code>Ollama</code> <code>FastAPI</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🥗 <a href="https://github.com/Sahiljangra115/HealthByte">HealthByte</a></h3>
      EfficientNet-B0 food classifier with uncertainty-banded calorie estimates and statistically honest correlations (Spearman + Benjamini-Hochberg FDR). Picks honest over impressive.
      <br/><br/>
      <code>EfficientNet</code> <code>SQLite</code> <code>FastAPI</code>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/Sahiljangra115/Noir">NOIR</a></h3>
      Autonomous robot assistant. Three concurrent real-time loops (YOLOv8 vision, STT/TTS voice, local LLM), an ESP32 hardware bridge, a Flutter control app, and ~2,500 lines of tests.
      <br/><br/>
      <code>YOLOv8</code> <code>Gemma</code> <code>ESP32</code> <code>Flutter</code>
    </td>
  </tr>
</table>

<details>
<summary><b>More on the bench</b> (click to expand)</summary>
<br/>

| Repo | One line |
|---|---|
| [NyxCore](https://github.com/Sahiljangra115/NyxCore) | TinyML anomaly detection inside XRCE-DDS streams on an ESP32-S3, with micro-ROS lifecycle management |
| [smogcast](https://github.com/Sahiljangra115/smogcast) | 24h / 48h PM2.5 forecasts for Delhi NCR, drift detection, gated retraining, canary rollback |
| [credit-risk-policy](https://github.com/Sahiljangra115/credit-risk-policy) | Calibrated LightGBM default model turned into a cost-based lending policy with fairness checks |
| [shrota](https://github.com/Sahiljangra115/shrota) | Timestamp-grounded audio intelligence for multi-speaker, code-mixed lectures and podcasts |
| [Path-tracer](https://github.com/Sahiljangra115/Path-tracer) | Monte Carlo path tracer in C++17 with a parallel CUDA port and zero dependencies |

</details>

## `$ cat now.txt`

```diff
+ mini-inference-engine   LLM serving from scratch: paged KV cache, continuous batching,
+                         chunked prefill, Triton kernels. Qwen2.5-0.5B on a 4 GB GPU.
+ straightline            Flow matching from scratch: DiT backbone, reflow, MeanFlow,
+                         an honest quality-vs-NFE table on CIFAR-10.
! both in progress. the READMEs track which phases are done.
```

## `$ which tools`

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,fastapi,docker,kubernetes,aws,githubactions&theme=dark" alt="ML and backend"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=cpp,go,ts,redis,postgres,ros,raspberrypi,arduino&theme=dark" alt="systems and embedded"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=arch,linux,bash,neovim,git&theme=dark" alt="daily driver"/>
</p>

<p align="center"><sub>plus LangGraph · FAISS · Qdrant · ONNX Runtime · faster-whisper · CUDA · ESP-IDF · FreeRTOS · micro-ROS</sub></p>

## `$ git log --graph`

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Sahiljangra115&background=0a0a0c&border=1f2937&stroke=1f2937&ring=00bfbf&fire=BF5AF2&currStreakNum=00bfbf&currStreakLabel=00bfbf&sideNums=e2e8f0&sideLabels=8b949e&dates=6b7280" alt="commit streak" width="95%"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sahiljangra115/Sahiljangra115/output/snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/Sahiljangra115/Sahiljangra115/output/snake.svg" alt="snake eating the contribution grid" width="95%"/>
  </picture>
</p>

<p align="center">
  <img src="./metrics.isocalendar.svg" alt="3D contribution calendar" width="49%"/>
  <img src="./metrics.languages.svg" alt="most used languages" width="49%"/>
</p>

## `$ ls ~/writing ~/learn`

<table>
  <tr>
    <td width="55%" valign="top">
      <b>✍️ Latest posts</b>
      <br/><br/>
      🚨 <a href="https://www.sahilkumar.tech/blog/agents-of-signoz">The Alert That Woke an Agent</a> <sub>Jul 2026</sub><br/>
      🛰️ <a href="https://www.sahilkumar.tech/blog/micro-ros-xrce-dds">Micro-ROS and XRCE-DDS: How ROS2 Fits into Microcontrollers</a> <sub>May 2026</sub><br/>
      🔁 <a href="https://www.sahilkumar.tech/blog/the-constant">The Constant</a> <sub>May 2026</sub><br/>
      🧭 <a href="https://www.sahilkumar.tech/blog">all posts →</a>
    </td>
    <td width="45%" valign="top">
      <b>🎓 Free courses I wrote</b>
      <br/><br/>
      <a href="https://www.sahilkumar.tech/learn/docker"><img src="https://img.shields.io/badge/Docker-0a0a0c?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"/></a>
      <a href="https://www.sahilkumar.tech/learn/kubernetes"><img src="https://img.shields.io/badge/Kubernetes-0a0a0c?style=flat-square&logo=kubernetes&logoColor=326CE5" alt="Kubernetes"/></a>
      <a href="https://www.sahilkumar.tech/learn/linux"><img src="https://img.shields.io/badge/Linux-0a0a0c?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux"/></a>
      <br/>
      <a href="https://www.sahilkumar.tech/learn/sql"><img src="https://img.shields.io/badge/SQL-0a0a0c?style=flat-square&logo=postgresql&logoColor=4169E1" alt="SQL"/></a>
      <a href="https://www.sahilkumar.tech/learn/git"><img src="https://img.shields.io/badge/Git-0a0a0c?style=flat-square&logo=git&logoColor=F05032" alt="Git"/></a>
      <a href="https://www.sahilkumar.tech/learn/langgraph"><img src="https://img.shields.io/badge/LangGraph-0a0a0c?style=flat-square&logo=langchain&logoColor=00bfbf" alt="LangGraph"/></a>
    </td>
  </tr>
</table>

## `$ fortune`

> *"If your eval only reports the wins, it is a demo, not an eval."*

<p align="center">
  <sub>Building the next generation of robots, AI systems, or just want to talk Linux? My inbox is open.</sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:00bfbf,45:005757,100:0a0a0c" alt="" width="100%"/>
