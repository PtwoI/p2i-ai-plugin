# p2i-ai-plugin

Optional adapters for external agents using P2I's structured tools.

## Boundary

Future provider-specific connectors may translate external tool calls to [p2i-sdk](https://github.com/PtwoI/p2i-sdk) actions. Core tracing, skill validation and architecture editing remain deterministic and provider-neutral in [p2i-core](https://github.com/PtwoI/p2i-core). No provider, API key, cloud service or AI model is required by core, GUI or CLI.

## Migration status

**Repository initialized; no AI integration has been implemented.** The working [PtwoI/p2i](https://github.com/PtwoI/p2i) already includes an agent-agnostic tool protocol and skill Harness. This repository reserves an explicit opt-in boundary for future connectors and does not claim a working AI plugin today.

MIT licensed.
