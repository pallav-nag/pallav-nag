## Hi, I'm Pallav

Backend & AI engineer at **Amadeus IT Group**, Bengaluru, building distributed systems
for airline operations. Outside work I build quant research tooling and multi-agent
LLM systems.

[palnag.in](https://palnag.in) · [LinkedIn](https://linkedin.com/in/pallavnag)

### What I work on

- **Distributed, event-driven backends** at airline scale: Java, C++, Kafka, MongoDB
- **Change-data-capture pipelines** with Kafka Connect + Debezium, replacing polling with live streams
- **Reliability engineering** on SLA-critical services
- **LLM tooling** that pulls code context from AST graphs instead of loading whole files

### Side projects

**Systematic equity research engine** · *private*  
A nightly pipeline and point-in-time backtest harness for NSE equities. The engineering is in
the validation: a survivorship-free universe rebuilt from historical turnover, split/bonus
adjustment on every price read, and every candidate signal A/B'd against a random control
before it ships. Most ideas fail that test, and a research log makes sure none gets tested twice.  
`Python` `pandas` `SQLite` `Gemini API` `launchd`

**[PR review agent pipeline](https://github.com/pallav-nag/Optimal-code-review-agents)** · *in progress*  
GitHub webhook → Redis fan-out → specialised review agents → aggregator → critic. Agents query a
code graph through Graphify MCP for callers and dependencies instead of loading whole files.  
`Python` `FastAPI` `Redis` `Claude API` `Docker`

**[Real-time IoT attack detector](https://github.com/pallav-nag/Real-time-network-attack-detector-IoT-)**  
A single ANN detecting DDoS, port scanning, MITM and phishing on IoT traffic (Edge-IIoTset),
benchmarked across ML models, with SMS/email alerting and a research paper.  
`TensorFlow` `Python`

**[Toxic comment classifier](https://github.com/pallav-nag/multilingual-toxic-comment-classifier)**  
Six-label toxicity classification on the Jigsaw dataset. BERT, LSTM-CNN, GRU and QRNN compared,
plus an ensemble. Team project.  
`BERT` `NLP` `Python`

### Stack

**Languages** Java · C++ · Python · SQL · JavaScript  
**Backend** Spring Boot · JAX-RS · REST · Kafka / Kafka Connect · Debezium · MongoDB · Redis  
**Infra** AWS · Docker · Podman · CI/CD  
**AI** Multi-agent pipelines · Graphify MCP · Claude & Gemini APIs · TensorFlow
