![OctoPilot — build, push, and ship](./Banner.png)

---

## What is OctoPilot?

> [!NOTE]
> **OctoPilot** is a carefully designed set of solutions to accelerate your application development. We remove the burden of configuring and managing build, test, and release pipelines so you can focus on shipping.

---

## Get started

| What you need | Where to go |
|---------------|-------------|
| **Pipeline CLI** — build, push, local registry, watch deployments | [**octopilot-pipeline-tools**](https://github.com/octopilot/octopilot-pipeline-tools) → `op build-push`, `op start-registry`, `op run`, and more |
| **Local HTTPS registry** — push/pull at `localhost:5001` with TLS | [**registry-tls**](https://github.com/octopilot/registry-tls) → use with `op start-registry` or run the image |
| **Reference apps** — one repo per frontend+backend pairing | [**SAMPLES.md**](./SAMPLES.md) → all `sample-*` repos, API contract, build/run/deploy |

> [!TIP]
> New here? Install the **op** CLI from [octopilot-pipeline-tools](https://github.com/octopilot/octopilot-pipeline-tools), run **`op start-registry`** for a local registry, then **`op build-push`** from any sample repo.

---

## Reference samples

We provide **one repository per frontend–backend pairing** (e.g. React+Go, Vue+Go, SolidJS+Go). Each sample has its own Skaffold setup and a simple greet API so you can adopt OctoPilot with minimal friction.

**→ Full list, setup, and contract:** [SAMPLES.md](./SAMPLES.md)
