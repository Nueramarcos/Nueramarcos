# Nueramarcos

Local-first agent operator. I build tools that fix GitHub repos on your machine — no cloud LLM required.

[![X](https://img.shields.io/badge/X-@Nueramarcos-000000?style=flat&logo=x)](https://x.com/Nueramarcos)
[![issue-agent](https://img.shields.io/badge/issue--agent-Airport-blue)](https://github.com/Nueramarcos/issue-agent)

**Find me:** [GitHub](https://github.com/Nueramarcos) · [X @Nueramarcos](https://x.com/Nueramarcos)

## Flagship

**[issue-agent](https://github.com/Nueramarcos/issue-agent)** — self-hosted GitHub issue resolver

```bash
curl -fsSL https://raw.githubusercontent.com/Nueramarcos/issue-agent/main/scripts/install.sh | bash
issue-agent status
```

Habitat → fix → Tower → merge. Powered by Ollama + Aider. [Airport in 5 minutes →](https://github.com/Nueramarcos/issue-agent/blob/main/docs/QUICKSTART.md)

## Local agent stack

| Repo | Role |
|------|------|
| [issue-agent](https://github.com/Nueramarcos/issue-agent) | Fleet runner — Airport, Habitat, Tower, Flight Recorder |
| [linux-cockpit](https://github.com/Nueramarcos/linux-cockpit) | Terminal desires + modular zsh |
| [orion-ai-agent](https://github.com/Nueramarcos/orion-ai-agent) | AST ground truth in Tower |
| [build-composer](https://github.com/Nueramarcos/build-composer) | LangGraph architect/coder/reviewer |

## Upstream

Open PRs on [tinygrad](https://github.com/tinygrad/tinygrad/pull/16683), [torchvision](https://github.com/pytorch/vision/pulls?q=author%3ANueramarcos), and others. Playbook: [CONTRIBUTING-UPSTREAM.md](https://github.com/Nueramarcos/issue-agent/blob/main/docs/CONTRIBUTING-UPSTREAM.md).

## Machine

Ubuntu workstation · i5-9600K · RX 5700 XT · Ollama local · YOLO agents

---

*The terminal is a workshop. [Write a desire](https://github.com/Nueramarcos/linux-cockpit).*