<div align="center">

# Hey, I'm Bakr 👋

### I build ML/DL from scratch before I trust a framework with it.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=CS+%40+UESTC%2C+Chengdu;Research-first%2C+not+library-first;Exploring+NLP+%26+LLM+architectures)](https://git.io/typing-svg)

[![GitHub](https://img.shields.io/badge/GitHub-HmedNejjar-181717?style=for-the-badge&logo=github)](https://github.com/HmedNejjar)
[![Org](https://img.shields.io/badge/Org-Irix-8A2BE2?style=for-the-badge&logo=github)](https://github.com/Irix-MAS)
[![Org](https://img.shields.io/badge/Org-Flixentus-FF6B00?style=for-the-badge&logo=github)](https://github.com/Flixentus)
[![Email](https://img.shields.io/badge/Email-bakr.m210906%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bakr.m210906@gmail.com)

</div>

---

## 🧭 The premise

I don't reach for `import transformers` until I've built the thing it's hiding. Second-year CS undergrad at **UESTC**, English-taught track, GPA-flexing quietly. Multilingual (🇲🇦 Arabic · 🇫🇷 French · 🇬🇧 English · 🇨🇳 Mandarin), which mostly just means I read papers and error messages in four languages instead of one.

```mermaid
flowchart LR
    A[Study theory\nGoodfellow DL book] --> B[Implement raw\nNumPy]
    B --> C[Replicate in PyTorch]
    C --> D[Ship it as a project]
    D -.feeds back.-> A

    style A fill:#1a1a2e,stroke:#00D9FF,color:#fff
    style B fill:#16213e,stroke:#00D9FF,color:#fff
    style C fill:#0f3460,stroke:#00D9FF,color:#fff
    style D fill:#533483,stroke:#00D9FF,color:#fff
```

That loop is the whole methodology. MLE/MAP → backprop → MLP in NumPy → MLP in PyTorch. Same pattern, every layer up.

---

## 🧬 How the understanding stacks

Not a project timeline — a depth chart. Each layer only gets built once the one below it actually holds.

```mermaid
flowchart BT
    F["📐 Math foundations\nlinear algebra · probability · optimization theory"]
    N["🔢 From-scratch implementations\nbackprop, MLPs, SGD/BFGS in raw NumPy"]
    T["🧠 Architectures\ndecoder-only transformers, RoPE, SwiGLU, MoE routing"]
    R["🔍 Systems\nretrieval, indexing, eval pipelines"]
    X["🚀 Open research questions\nsparse vs. dense, domain-routed experts"]

    F --> N --> T --> R --> X

    style F fill:#1a1a2e,stroke:#00D9FF,color:#fff
    style N fill:#16213e,stroke:#00D9FF,color:#fff
    style T fill:#0f3460,stroke:#00D9FF,color:#fff
    style R fill:#533483,stroke:#00D9FF,color:#fff
    style X fill:#e94560,stroke:#ffd700,color:#fff
```

---

## 🧠 What's in the stack

<div align="center">

| Layer | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white) |
| **ML Core** | ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)|
| **Retrieval** | ![HNSW](https://img.shields.io/badge/-HNSW-4B0082?style=flat-square)|

</div>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#0f3460','primaryBorderColor':'#00D9FF','primaryTextColor':'#ffffff','lineColor':'#00D9FF','secondaryColor':'#16213e','secondaryBorderColor':'#00D9FF','tertiaryColor':'#1a1a2e','tertiaryBorderColor':'#00D9FF'}}}%%
mindmap
  root((Bakr))
    Architectures
      Decoder-only Transformers
      RoPE / SwiGLU
      Mixture of Experts
      KV-caching
    Optimization
      SGD from scratch
      BFGS / L-BFGS
      Adam / AdamW
    Retrieval
      Chunking strategy
      HNSW indexing
      RAG pipelines
```

---

## 🎯 Where this is going

- 🧠 Push sparse, domain-routed architectures (MoE) past the "nice idea" stage into results that hold up under real benchmarks
- 🔬 Build a research career at the intersection of neural architecture design and efficient training on constrained compute
- 📖 Get into a top-tier ML/DL graduate program and keep working the theory-to-implementation loop at research scale
- 🚀 Long-term: contribute architectures and training techniques that push what's possible in language and reasoning models — not just use them

---
