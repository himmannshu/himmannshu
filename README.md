# Hi, I'm Himanshu Sharma

Software Engineer focused on production systems: full-stack applications, distributed systems, and applied AI. 

[Portfolio](https://www.paperandlatency.com/) • [LinkedIn](https://linkedin.com/in/himanshu00) • vghimanshu2@gmail.com

## Background

At Dematic, I built and deployed Warehouse Control System software (Angular, NestJS, .NET, SQL Server, IBM MQ) for high-throughput distribution centers, covering requirements gathering, commissioning, UAT, and go-live support on live operations.

I'm now spending most of my time on applied AI systems: agent architectures, retrieval-augmented generation, and the evaluation and guardrail work that makes them reliable enough to trust with a real answer.

## Featured Projects

### [Boston Query Compiler](https://github.com/himmannshu/Boston-Query-Compiler)
A query-planning system over 1M+ rows of Boston open city data (311 requests, crash records, building permits). Instead of answering from retrieved text, an LLM planner classifies each question and routes it to SQL, retrieval, or a cross-dataset join, so counts and aggregates come from a deterministic query engine rather than a language model doing arithmetic in its head.

Benchmarked against two RAG baselines on the same 37 questions: 86.7% answer accuracy versus 20% for both baselines, with a numeric-fidelity guard that catches any figure not present in the underlying evidence.

`Python` `DuckDB` `LLM planning` `hybrid retrieval`

### [Financial Research Agent](https://github.com/himmannshu/stock-market-agents)
A multi-agent system that generates equity research reports. A planner agent scopes the analysis, a data agent pulls structured financials, a search agent gathers market context, and a writer agent synthesizes everything into a report that a verifier agent checks for inconsistencies before it reaches the user.

`Python` `Streamlit` `multi-agent orchestration`

## Tech Stack

**Languages:** TypeScript, JavaScript, Python, C#, SQL
**Frontend / Backend:** React, Angular, NestJS, Node.js, .NET, FastAPI
**Data:** PostgreSQL, SQL Server, DuckDB, pandas, NumPy, Power BI
**AI / ML:** PyTorch, LLM agents, RAG, LangGraph, vector search
**Infra:** Docker, REST, gRPC, WebSockets, IBM MQ

---

Open to Software Engineer, Full-Stack, and Applied AI roles. Feel free to reach out.
