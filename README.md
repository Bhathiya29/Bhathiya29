<h1 align="center">Hi, I'm Bhathiya</h1>

<p align="center">
  I am Software Engineer who builds AI systems end to end: the data, the models, the evaluation and the deployment.<br/>
  Three years of production engineering, a Master of Data Science and AI from RMIT, and a published paper in Deep Learning and NLP at IEEE.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bhathiya-dissanayake">LinkedIn</a> ·
  <a href="mailto:bhathiyabandara87@gmail.com">Email</a> ·
  <a href="https://grammar-ai-sandy.vercel.app/">GrammarAI live demo</a>
</p>

---

## Featured: GrammarAI - An open-source alternative to Grammarly

<p align="center">
  <a href="https://grammar-ai-sandy.vercel.app/">
    <img
      width="1000"
      height="756"
      alt="demo_gif"
      src="https://github.com/user-attachments/assets/085fcf90-b4c2-47c2-94c6-95f6ed0eafc4"
    />
  </a>
</p>

- **Hybrid engine:** SymSpell for spelling, spaCy with a pronunciation dictionary for a/an rules, and a T5 grammar model, with priority-based overlap resolution between them.
- **Benchmark:** evaluated with ERRANT on JFLEG. The model lifts F0.5 from 0.39 to 0.54 over the rule-based checkers, and the README is upfront about where it falls short.
- **The hard parts:** a diff pipeline that turns rewritten sentences into character-accurate edits, UTF-16 offset conversion so underlines stay aligned with emoji, stale-request handling, and touch support.
- **Shipped:** Dockerised FastAPI backend (CPU-only PyTorch, model baked into the image) and a React + TypeScript frontend on Vercel, with rate limiting and logs that never contain your text.

[Live demo](https://grammar-ai-sandy.vercel.app/) · [Source code](https://github.com/bhathiya29/grammarai) · [System design](https://github.com/bhathiya29/grammarai)

## What I care about

- **Measuring what I ship.** Benchmarks, ablations and honest limitations, not just another PR
- **Finishing.** Taking a project from ambiguity to a production grade application
- **The unglamorous parts.** Latency, cold starts, privacy and failure modes.

## Also built

- **[InsightPulse](https://github.com/bhathiya29/insightpulse):** a real-time Kafka pipeline over 100K+ reviews with pgvector and Claude-powered RAG. Three-layer Redis caching cut LLM calls by 98%, and four services run on AWS with circuit breakers and Prometheus/Grafana monitoring.
- **[CogniAssess](https://github.com/bhathiya29/cogniassess):** Aspect Based MOOC Review Analysis using Deep Learning and NLP. Capable of Analyzing 100K reviews on one go. (Python, React, REST API).

## Background

- Master of Data Science, RMIT University
- BEng (Hons) Software Engineering, First Class, University of Westminster
- About three years at IFS building production software for international clients (Aston Martin, Emirates and many more)
- IEEE publication in Deep Learning and NLP: [read at IEEE Xplore](https://ieeexplore.ieee.org/document/10963217)

## Tech

**Languages:** Python, Java, TypeScript, JavaScript, Go, C/C++, SQL<br/>
**Backend and data:** FastAPI, Spring Boot, Kafka, Redis, PostgreSQL<br/>
**Cloud and infrastructure:** AWS, Azure, Docker, Kubernetes <br/>
**AI:** PyTorch, Hugging Face, spaCy, RAG, agentic AI, MCP

Open to AI Engineer, Forward Deployed Engineer and Software engineering roles. LinkedIn or email is the best way to reach me.
