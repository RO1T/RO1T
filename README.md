### Khusnutdinov Rinat
---
**Go highload & LLM engineering**. I build Go microservices that handle real-time data end to end: concurrent WebSocket ingestion from several sources, gRPC between services, time-series analytics in ClickHouse, and a Telegram bot on top. I build AI tools that bring LLMs into the apps people already use, like GigaChat inside Microsoft Word for expanding, condensing and summarising documents. Every project builds or starts with one command and comes with a README that gets you from clone to running system.

### Focus: Go × LLM
| Project | What it does | Stack |
|---|---|---|
| [Career Proof](https://github.com/RO1T/career-proof) | CLI that checks which skills on a resume are actually backed by evidence. The LLM only extracts facts with verbatim quotes; code verifies every quote, scores each skill against a 7-check rubric and compares the result with real vacancy requirements. Asks targeted questions and builds hh.ru-ready "Experience" and "About" blocks with provenance for every fact, so nothing is invented. One-command install | Go, SQLite, Claude / OpenAI-compatible LLMs, JSON Schema, GoReleaser |
| [GoSpread](https://github.com/RO1T/GoSpreadv3) | Real-time crypto arbitrage monitor. Streams order books from Binance, Bybit and OKX over WebSocket behind a unified exchange interface, computes spot-futures spreads net of fees and funding, serves the top-10 opportunities through a Telegram bot | Go, gRPC, WebSocket, ClickHouse, PostgreSQL, Docker Compose |
| [GigaChatWord](https://github.com/Enfariches/VSTO_AddIn) | Microsoft Word add-in with GigaChat in the context menu: expand a selection, condense it to key points, or generate a conclusion for the whole document. Ships as an .exe installer | C#, .NET, VSTO, GigaChat API |
| [gym-client](https://github.com/RO1T/gym-client) | Desktop client for a workplace-exercise service. Lives in the system tray, pulls the exercise schedule over gRPC, sends reminders, opens video instructions from MinIO, reports completion stats back to the server | Python, PySide6, gRPC, MinIO |
---
### Stack

Go: goroutines · channels · errgroup · context · sync · pprof · benchmarks · gRPC · WebSocket · REST · Swagger LLM: GigaChat · Ollama · RAG · embeddings · pgvector · LLM-as-judge · prompt engineering · structured output Data: PostgreSQL · ClickHouse · Redis · Kafka · Goose migrations Infra: Docker · Kubernetes · GitLab CI · Prometheus · Grafana · Linux

---
### Open to

Go backend · LLM engineer · AI backend.

### Contact

enderrino@gmail.com · @Mi4i0S
