# Gavin Jiang

**Software engineering · AI · Embedded systems**

I'm pursuing an **M.S. in Computer Science at the University of Southern California**, with graduation expected in June 2027. I earned my B.S. in Computer Science with a Mathematics minor from Santa Clara University in March 2024, graduating Magna Cum Laude.

I enjoy learning by building: turning game-related ideas into useful tools, connecting AI models to practical workflows, and developing software that works with physical devices. My experience spans legal intake and retrieval, hardware test automation, and embedded sensor networks.

## Experience

- **AI Engineering Intern — Beshton** · July–September 2026

  Built natural-language intake that structures legal case descriptions, identifies missing information and required forms, and incorporates filing limits and procedural constraints. Developed a RAG pipeline to ingest and retrieve information from official, vetted legal sources.

- **Software Engineer Intern — Infinera** · June–August 2025

  Built parsers, visualizations, and reports for high-speed SerDes DFE test logs, comparing bit-error rate (BER) and eye-opening monitor (EOM) measurements across configurations. Implemented an ML-driven automated testing pipeline to optimize SerDes settings and minimize BER.

- **Researcher — EPIC IoT** · January 2023–June 2024

  Developed dissolved-oxygen regression models and sensor-data pipelines. Implemented Wi-Fi communication using ESP8266-01 modules and Arduino-compatible boards, protocol-layer APIs for Hydration Automation, and the AB energy-aware networking protocol.

Research publication: [*DOxy: A Dissolved Oxygen Monitoring System*](https://www.mdpi.com/1424-8220/24/10/3253), **Sensors (2024)**.

## Selected Projects

- **[AI Yu-Gi-Oh! Judge](https://github.com/MistaEO/YGOAIJudge)** · December 2025–Present

  A local rules assistant using **Qwen3 8B through Ollama**, **ChromaDB + BM25** hybrid retrieval, and a **SQLite/FTS5** card cache populated on demand from YGOPRODeck. **FastAPI** returns structured judge-slip JSON, with a citation guard that removes references absent from the retrieved context.

- **[HRL Minecraft Agent](https://github.com/MistaEO/UnifiedMinecraftHRL)** · February–June 2026

  A hierarchical reinforcement learning framework connecting a **Mineflayer** bot to a **Python/PyTorch** training backend. Supports reusable macro-actions, structured game-state observations, tech-tree rewards, **DQN/PPO** training, and reasoning-path evaluation against reference paths.

- **[DuelMath](https://duelmath.vercel.app/)** · December 2025–Present · [Source](https://github.com/MistaEO/DuelMath)

  A **React/TypeScript** app with a deck builder and mathematical tools for Yu-Gi-Oh! players, including multivariate hypergeometric calculations for opening-hand probabilities.

## Current Engineering Work

**In progress since October 2026.** These descriptions outline project scope; benchmark and verification results are not yet published here.

- **CUDA RMSNorm Operator** — A fused C++/CUDA operator with PyTorch integration, FP32/FP16 correctness checks across input shapes, and synchronized latency and memory-bandwidth comparisons against eager and compiled PyTorch.

- **TensorRT Inference Optimization** — A PyTorch-to-ONNX-to-TensorRT classifier workflow comparing FP32, FP16, and calibrated INT8 accuracy and performance, with a C++ runner for latency, throughput, and GPU-memory measurements.

- **RTL Verification Environment** — A parameterized FIFO and SystemVerilog/UVM environment with constrained-random sequences, a scoreboard, assertions, and functional coverage for reset, full/empty boundaries, simultaneous reads/writes, and pointer wraparound.

## Tools and Interests

- **Software:** Python, C/C++, TypeScript/JavaScript, SQL, Rust, React, Django, and FastAPI.

- **AI/ML:** PyTorch, TensorFlow, scikit-learn, RAG, reinforcement learning, and model evaluation.

- **Systems:** Linux/Bash, Docker, Verilog, ARM Assembly, ESP8266, Arduino-compatible boards, and network protocol stacks.

I'm interested in reliable AI tools, agent planning and evaluation, GPU programming, and the connections between software and hardware.

## Connect

[Portfolio](https://mistaeo.github.io/) · [LinkedIn](https://www.linkedin.com/in/gavin-jiang-010b4b25a/) · [Email](mailto:gavinyjcs@gmail.com)
