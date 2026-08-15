# Nishant Gadde

Systems, ML, and applied research. Most of what I build falls into four buckets: low-latency trading infrastructure, applied machine learning on health and market data, local-first AI tooling, and embedded systems.

---

### Low-latency systems

| Project | What it is |
|---|---|
| [lowlat-trading-lib](https://github.com/Nishant27-2006/lowlat-trading-lib) | Ultra-low-latency trading infrastructure library. Lock-free SPSC queue, thread-local memory pools, CPU pinning, `rdtsc` timing. C++17, POSIX. |
| [itch-feed-handler](https://github.com/Nishant27-2006/itch-feed-handler) | Zero-allocation NASDAQ ITCH 5.0 UDP-multicast feed handler with real-time limit order book reconstruction. C++20, AVX-512, lock-free. |
| [quant-strategy-v3](https://github.com/Nishant27-2006/quant-strategy-v3) | ML-driven long/short US equity strategy. 500+ ticker universe, walk-forward backtesting, vol-targeted ATR sizing, dollar-neutral book. |
| [kalshi-elections](https://github.com/Nishant27-2006/kalshi-elections) | Kalshi Trade API v2 client with RSA-PSS request signing implemented directly, plus backtest and news-momentum tooling. |

### Local-first AI tooling

| Project | What it is |
|---|---|
| [papercast](https://github.com/Nishant27-2006/papercast) | Drop an arXiv link, get a two-host podcast. Fully local — `gpt-oss:20b` via Ollama for the read and transcript, Kokoro-82M for voices. No API keys. |
| [the-symposium](https://github.com/Nishant27-2006/the-symposium) | Fully-local Socratic research lab for Vision Language Model work, aimed at sports video understanding: athlete tracking, tactical analysis, automated coaching. |
| [shredlab](https://github.com/Nishant27-2006/shredlab) | Local-first biometric performance tracker — macro logging, progress photos, weight curves, and coaching from a locally-run model. |
| [unbiased-news-agent](https://github.com/Nishant27-2006/unbiased-news-agent) | Multi-model news generation pipeline that cross-checks sources to reduce bias and hallucination. LangGraph + Gemini + OpenRouter. |
| [resume-optimizer-ai](https://github.com/Nishant27-2006/resume-optimizer-ai) | LangGraph + Gemini deep-research agent that reads job descriptions and generates tailored resumes. |

### Applied ML research

| Project | What it is |
|---|---|
| [slm-dynamic-inference](https://github.com/Nishant27-2006/slm-dynamic-inference) | Can 1B–7B SLMs on consumer GPUs use dynamic inference to cut latency and compute on standard benchmarks? Experiments, analysis, and paper. |
| [cancer-nonadherence-prediction](https://github.com/Nishant27-2006/cancer-nonadherence-prediction) | 0–100 risk score for treatment non-adherence among cancer survivors, built on MEPS 2016–2023 with survey-weighted logistic regression. |
| [cfml](https://github.com/Nishant27-2006/cfml) | ECG analysis with a hybrid CNN-SVM for non-invasive early heart disease detection. Work from Georgia Tech's Cardiovascular Fluid Mechanics Laboratory. |
| [NeuroAlphaFold3](https://github.com/Nishant27-2006/NeuroAlphaFold3) | AlphaFold 3 pipeline modeling cis- and trans-pQTL-derived proteins implicated in neurological disease. |
| [atrialfilbitration](https://github.com/Nishant27-2006/atrialfilbitration) | Atrial fibrillation detection from ECG — signal preprocessing pipeline feeding a deep learning classifier. |
| [nonlinearoptimization](https://github.com/Nishant27-2006/nonlinearoptimization) | Trust-region optimization with dynamic regularization and sensitivity analysis for high-dimensional nonlinear constrained problems. |
| [MZIMeshOptimization](https://github.com/Nishant27-2006/MZIMeshOptimization) | Q-Learning vs. genetic algorithms vs. gradient descent for tuning Mach-Zehnder Interferometer mesh phases. |
| [QCAttacks](https://github.com/Nishant27-2006/QCAttacks) | Quantum cryptographic methods (QKD, lattice-based) evaluated against quantum attack models. |
| [2018TexasSenate](https://github.com/Nishant27-2006/2018TexasSenate) | Predicting the 2018 Texas Senate race from county-level presidential results, 2008–2016. |

### Products & tools

| Project | What it is |
|---|---|
| [dealflow-ai](https://github.com/Nishant27-2006/dealflow-ai) | AI deal-packet and compliance copilot for franchised car dealerships — tracks deals from sold to funded: stipulations, DMV/title forms, validation, audit readiness. |
| [learnarm](https://github.com/Nishant27-2006/learnarm) | Translates Java, Python, and C++ into ARM Cortex-M assembly with step-by-step explanations, for embedded systems students. |
| [lc3-vis](https://github.com/Nishant27-2006/lc3-vis) | Visualizer for the LC-3 instruction set architecture. |
| [supabase-pgvector-rag](https://github.com/Nishant27-2006/supabase-pgvector-rag) | RAG backend on Supabase pgvector — tiktoken chunking, embedding generation, semantic retrieval. |
| [AceCycleManager](https://github.com/Nishant27-2006/AceCycleManager) | Inventory and CO₂-emissions tracker for tennis stores managing ball lifecycle and reuse. |
| [nfl-vlm-dataset](https://github.com/Nishant27-2006/nfl-vlm-dataset) | Pipeline for building an NFL play-by-play video dataset for vision-language model training. |

---

Reach me at nishantg2706@gmail.com.
