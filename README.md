### Hi there 👋

I'm a cloud performance optimizer. I make systems fast, quiet, and cheap to run—targeting database bottlenecks, async pipeline latency, and bloated cloud bills. Like my work? [Consider working with me](https://peterrauscher.com) or [get in touch](mailto:peter@peterrauscher.com).

Currently a Senior Software Engineer at [Vividly](https://www.govividly.com) on the core backend team, building Rust services and tuning Postgres query engines to cut forecast latency from minutes to seconds. Previously, I was at [Perpay](https://perpay.com) on the commerce and backend infrastructure team, rebuilding core checkout services and slashing async pipeline runtimes by 80% to lower AWS compute costs.

You can read my technical writing over at [peterrauscher.com/blog](https://peterrauscher.com/blog) and connect with me on [LinkedIn](https://linkedin.com/in/peter-rauscher). 🌟

I actively monitor pull requests and issues. If you need urgent eyes on a discussion or project, feel free to ping `@peterrauscher` in a comment.

---

### Selected Performance & Infrastructure Wins

- **2m+ $\to$ <5s Query Latency:** Replaced destructive table drop-and-reload recalculations with a temporary staging delta-diffing engine in Rust/PostgreSQL, eliminating Postgres WAL saturation, replication lag, and replica crash loops under enterprise volume.
- **-80% Runtime & -$1,100/mo Cloud Compute:** Replaced synchronous catalog ingestion with event-driven webhooks and debounced Celery workers, dropping AWS compute spend.
- **-50% CI Build Times & -39% Docker Footprint:** Overhauled image pipelines through layer caching optimization, build engine swaps, and test-suite sharding.
- **Queue-Lag Over CPU Autoscaling:** Architected KEDA autoscaling pipelines for asynchronous AI worker clusters, scaling pods strictly off queue depth to prevent token-burn runaway.

---

### Selected Writing

- [**How to scale AI agent clusters with KEDA**](https://peterrauscher.com/blog/how-to-scale-ai-agent-clusters-with-keda) — Why CPU is the wrong metric for agent workers and how to scale from queue backlog.
- [**The secret to scraping React apps without a headless browser**](https://peterrauscher.com/blog/scraping-react-apps-without-headless-browser) — Eliminating headless browser compute by extracting embedded hydration JSON.
- [**Work-life balance is an eventual consistency problem**](https://peterrauscher.com/blog/balance-in-life-is-eventual-consistency) — Applying distributed systems convergence models to everyday work.
