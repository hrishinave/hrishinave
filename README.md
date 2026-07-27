# Hrishikesh Naveenam

CS student at UT Dallas (B.S. expected May 2028, math minor). I spend most of my time on the seam between machine learning and the web — training a model is only half of it, the other half is building something people can actually click on.

Open to software engineering and ML internships. Resume and links are at the bottom.

## What I've been built

**[AutoPM](https://github.com/hrishinave)** — An AI copilot for product managers that runs a seven-step workflow (research, user stories, RICE prioritization, wireframes, Jira tickets) across eight LangGraph agents. The interesting part was making agents talk to each other reliably: every handoff is a Zod-validated structured output, which turned a pile of brittle prompt chaining into something type-safe. Placed 2nd out of 350+ projects at HackUTD.
`Next.js` `TypeScript` `LangGraph` `Gemini` `Auth0`

**[NetgainNBA](https://net-gain-nba.vercel.app)** — A playoff prediction platform running a 7-model ensemble (XGBoost, TabNet, Random Forest, Logistic Regression) over 89 features, at 88% accuracy on 2020–2024 seasons. Pipeline goes from NBA Stats API ingestion through K-Means player clustering into inference, and the front end is a GM toolkit: bracket simulation, salary cap tracking, trade engine.
`React` `Flask` `Python` `XGBoost` `scikit-learn`

**TuneTrend** — Genre-aware music popularity predictor, built with a 4–5 person team at the UT Dallas AI Club where I handled architecture and the ML pipeline. Extracts 140+ audio features (MFCCs, chroma, spectral contrast) with artist-level GroupShuffleSplit so the model can't cheat by memorizing artists. Six genre models, real-time hook detection, Three.js visualizations.
`Next.js` `Flask` `XGBoost` `librosa` `Three.js`

## Open source

Contributor to [OpenWorker](https://github.com/andrewyng/openworker) ([PR #185](https://github.com/andrewyng/openworker/pull/185)) — added four NVIDIA NIM catalog models behind an OpenAI-compatible interface. Getting there meant first fixing an auth gap that let invalid API keys pass validation; the fix uses an inference-based verification probe with unit test coverage.

## Research

- **UT Dallas, Machine Learning** (Feb–May 2025) — Astronomical anomaly detection on Galaxy10. Trained a DCGAN in PyTorch to generate synthetic training images and fine-tuned StyleGAN weights for rare celestial events, pushing rare-event detection 15% over baseline (0.85 ROC-AUC, 0.72 recall).
- **University of Missouri, Distributed Systems** (Sept 2023–Jan 2024) — Workflow placement across volunteer edge nodes using K-Means over CPU, RAM, and storage telemetry, at 84% placement accuracy. Built a Docker-based EC2 testbed with multiple Linux VMs to make the experiments repeatable.

## Tools I reach for

**Languages** — Python, Java, C++, TypeScript/JavaScript, SQL, Swift
**ML & data** — PyTorch, scikit-learn, XGBoost, pandas, NumPy, LangChain, LangGraph, librosa
**Web & backend** — React, Next.js, Node.js, Flask, Spring Boot, Fastify, REST, PostgreSQL, MongoDB
**Infra** — AWS (EC2, S3), GCS, Docker, Kubernetes, OpenFaaS, Git, CI/CD

## Reach me

[LinkedIn](https://linkedin.com/in/hrishikeshnaveenam) · hrishinave@gmail.com
