### Mahyar Jaberi

I build AI agents that run in production: tool-calling agents, MCP servers, voice agents, and the evals that keep them honest.

<samp><a href="https://mahyar-portfolio.dev">portfolio</a> · <a href="https://linkedin.com/in/mahyar-jaberi">linkedin</a> · <a href="https://bowlwise.app">bowlwise</a> · <a href="mailto:jaberi.mahyar@gmail.com">email</a></samp>

```console
$ agent run whoami
▸ work()      AI Solutions Engineer @ FGF Brands · agent LLM cost -81% (benchmarked)
▸ ship()      BowlWise · live in 2 Pet Valu stores · MCP server in Claude's connector directory
▸ compete()   Landline · 3rd of 30+ teams · Boson AI Higgs Audio Hackathon
▸ research()  graph retrieval for clinical LLM agents · York Data Mining Lab
✓ 4 tool calls · 0 hallucinations
```

#### Selected work

**[BowlWise](https://bowlwise.app)** · founder  
Dog food matching, live on customer tablets in 2 Pet Valu stores and inside Claude as a connector.
- Claude agent with 15 tools over a deterministic scoring engine: scores and prices come from the engine, never the model
- 7-tool read-only MCP server, listed in Claude's connector directory
- Passed 111/111 eval conversations at $0.009 each

<sub>Python · FastAPI · Claude API · MCP · MongoDB Atlas · React</sub>

**[Landline](https://landline-mu.vercel.app)** · [repo](https://github.com/2arian3/BosonAI-Hackathon) · with [@2arian3](https://github.com/2arian3) and [@Danial-Kord](https://github.com/Danial-Kord)  
Voice agents in real estate work for the brokerage. Landline works for the renter: it phones listing agents in parallel and books viewings in your times.  
3rd of 30+ teams at the Boson AI Higgs Audio Hackathon · Georgian Build North finalist
- Rebuilt the live-map web app and its real-time API
- Fixed the agent's tool use in evals: sessions that skipped tools 7/21 → 0/21, clean multilingual call endings 10/15 → 15/15

<sub>Python · FastAPI · Boson AI Higgs Realtime · Twilio · Next.js · MapLibre</sub>

**Graph retrieval for clinical LLM agents** · York Data Mining Lab, with Prof. Manos Papagelis  
A tool that lets LLM agents follow references across FHIR health records, tested on the public FHIR-AgentBench benchmark.
- Pre-registered eval over 1,489 agent episodes, with paired sign-flip tests
- The tool alone gave no significant gain. Tracing the failures to a schema gap did: one prompt line lifted correctness 25/84 → 56/84 (exploratory)

<sub>Python · FHIR (BLAZE) · MIMIC-IV · OpenAI Responses API</sub>

#### Now

- **AI Solutions Engineer co-op at FGF Brands:** agentic AI for a large bakery manufacturer. Cut an app-builder agent's LLM cost 81% and build time 56% on benchmarks, and hardened its tool calls against excessive agency.
- **[Palimpsest](https://github.com/mahyar-jbr/Palimpsest):** a temporal knowledge-graph memory engine for Claude over MCP, benchmarked on LongMemEval.

#### Previously

- **[Maridian](https://github.com/mahyar-jbr/maridian-sentinel):** six-agent Claude system that turns a flagged factory defect into a recovery plan with a dollar estimate · TMLS 2026 Agentic AI Hackathon
- **Nova Ventures** (2025): sports analytics backend and data pipeline
- **Sepantech** (2024): course platform for 500+ medical professionals

#### Stack

<samp>Python · TypeScript · FastAPI · React · Next.js · Claude API · OpenAI · Azure OpenAI · MCP · LangGraph · PostgreSQL · MongoDB Atlas · Docker · Azure · GCP</samp>
