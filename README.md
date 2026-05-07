# Collin Kabwama

**Backend & platform engineer** — APIs, JVM services, and **distributed control paths** (state, policy, and enforcement at scale).

I design and ship systems where **correctness under failure**, **clear operational boundaries**, and **security-by-default** matter as much as feature velocity.

---

### Focus

- **Distributed systems** — replication-style patterns, shared state with **bounded latency** budgets, **fail-open / fail-closed** tradeoffs where appropriate
- **Platform engineering** — Spring Boot starters, autoconfiguration, extension points, versioned configuration surfaces
- **Cloud & orchestration** — **AWS** for runtime, networking, and IAM-aware services; **Kubernetes** for deployments, services, config, and rollouts
- **Reliability & observability** — structured telemetry, metrics, actuator-style introspection, CI for multi-module Java
- **Security & abuse resistance** — runtime policy, identity-aware signals, rate/throttle/quarantine semantics

---

### Stack

`Java` · `Spring Boot` · `Maven` · `Redis` · `Kafka` (where async boundaries help) · `Docker` · **`AWS`** · **`Kubernetes`** · `GitHub Actions` · `Micrometer` · `JUnit`

*Comfortable with:* IAM/VPC-style boundaries, container images and cluster ops, horizontal scaling, API design, performance-sensitive hot paths.

---

### Flagship: [ai-sentinel](https://github.com/CollinKabwama/ai-sentinel)

**Zero-trust–style API defense for Spring Boot** — in-process behavioral analysis, optional identity trust + anomaly fusion, and enforcement (monitor / throttle / block / quarantine), with **optional Redis** for cluster quarantine, throttling, and distributed behavioral baselines.

- **Why it exists:** Complements auth and edge controls with **per-identity** behavioral signals and a single policy surface; no mandatory hosted scorer — **servlet filter + core pipeline** on the request path.
- **Production thinking:** bounded Redis commands, **fail-open** fallbacks when shared state is slow/unavailable, optional trainer + filesystem model registry for **off-path** model refresh.
- **Depth:** Multi-module layout (core / starter / trainer / demo), documented architecture and configuration, CI on PRs to `main` and `dev`.

---

### Other work

- **[Property-Management-Portal](https://github.com/CollinKabwama/Property-Management-Portal)** — Full-stack domain modeling and API-backed workflows (Java ecosystem).
- Smaller learning and assignment repos — algorithms, games, deployment exercises (intentionally not the focus of this profile).

---

### Now

Building **ai-sentinel** and related patterns: **policy at the edge of the JVM**, safe optional distribution, and measurable runtime behavior.

---

### Contact

**LinkedIn:** [linkedin.com/in/collin-kabwama](https://www.linkedin.com/in/collin-kabwama/)

**Certifications (Credly):** [AWS Solutions Architect – Associate](https://www.credly.com/badges/9f98eca8-e0dc-4e91-b52e-20afbc9902ee/public_url) · [AWS Security – Specialty](https://www.credly.com/badges/4a7d4514-3ed3-4634-ad1e-621f6b46ebc0/public_url) · [CKAD](https://www.credly.com/badges/33b721f2-98a4-48dc-86ea-eb018211582c/public_url)

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=CollinKabwama&show_icons=true&theme=default&hide_rank=false" alt="GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=CollinKabwama&theme=default" alt="GitHub streak" />
</p>

