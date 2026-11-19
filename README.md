# Hi, I'm Daniel Vaziri

**AI Engineer and founder of [ShareHub](https://sharehub.dk), Copenhagen.**

I build AI-first products, from voice agents to multi-agent development systems, and I care about the boring parts that make AI safe to ship: validation, tests, audit trails and failover.

25+ years in IT · Python, Node.js, PostgreSQL · Claude Code and Codex every day

> Most of my code lives in private repositories because these are live products. I'm happy to walk through the code, architecture and tests in an interview.

---

## What I've built

### [Dani Agent](https://buildhub.dk/dani-agent/) – multi-agent software development system
Describe a product and approve once. Claude plans the work and reviews every step, Codex writes the code in a sandbox, automated tests run, and only reviewed, passing steps are committed to Git.
- Git approval gates, workflow recovery and a full audit trail of every finding and decision
- 353 regression tests
- Validated with a planted bug that normal tests missed: the independent reviewer caught it

`Claude Code` `Codex` `Python` `Git` `sandboxed execution`

### [RingAI](https://ringai.dk) – AI voice receptionist
Answers business phone calls in real time, books and cancels appointments and transfers calls. In commercial pilot with businesses.
- Tool calls into Google Calendar and SMS, with server-side validation and multi-tenant data isolation
- Synthetic test calls in five languages, including prompt-injection attempts
- Failover with owner alerts if the AI provider goes down

`Node.js` `OpenAI Realtime API` `Twilio Media Streams` `WebSockets` `SQLite` `Docker` `Fly.io`

### [Vakosta](https://vakosta.dk) – property valuation platform
Joins Danish public registers (addresses, buildings, registered sales, price index) with local sales data to value homes.
- A deterministic comparable-sales engine is primary; AI is only a fallback
- Results are never blended, and every decision is audited with its model version

`FastAPI` `PostgreSQL/PostGIS` `Alembic` `Next.js` `Docker`

### Other ShareHub products
- **[ParkingHub](https://parkinghub.dk)** – peer-to-peer parking marketplace (web, Android, iOS) with Stripe payments
- **[DriverHub](https://driverhub.dk)** – private-driver service with MitID and driving-licence verification
- **[FounderHub](https://founderhub.dk)** – in pilot
- **Multi-LLM decision engine** – benchmarks models on quality, consistency, latency and cost, with structured JSON outputs

### Earlier
- **TachoLive** (JaxiCloud) – led a real-time EU tachograph compliance platform; finalist, IoT Project of the Year 2024 (GITEX Dubai)
- Prediction models on large-scale GPS and tachograph data; Python/Flask services and Power BI dashboards

---

## Tech I use

- **AI:** LLM apps, agents and tool calling, structured outputs, voice AI, prompt-injection testing, LLM evaluation
- **Backend:** Python (FastAPI, Flask, Django), Node.js (Express), REST APIs, WebSockets
- **Data:** PostgreSQL/PostGIS, SQLite, MySQL, SQL Server, Pandas, scikit-learn, Power BI
- **Ops:** Docker, Git/GitHub, CI/CD, Fly.io, AWS, Azure, Linux

---

## Contact

[LinkedIn](https://linkedin.com/in/dvaziri) · [sharehub.dk](https://sharehub.dk) · jvaziri@gmail.com · Copenhagen, Denmark
