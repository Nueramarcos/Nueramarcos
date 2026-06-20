# Nueramarcos

Local-first agent operator. I build tools that fix GitHub repos on your machine — no cloud LLM required.

## Flagship

**[issue-agent](https://github.com/Nueramarcos/issue-agent)** — self-hosted GitHub issue resolver

```bash
curl -fsSL https://raw.githubusercontent.com/Nueramarcos/issue-agent/main/scripts/install.sh | bash
issue-agent status
```

Triage → fix → test → PR, powered by Ollama + Aider. [Airport in 5 minutes →](https://github.com/Nueramarcos/issue-agent/blob/main/docs/QUICKSTART.md)

## Local agent stack

| Repo | Role |
|------|------|
| [issue-agent](https://github.com/Nueramarcos/issue-agent) | Fleet runner — triage, fix, merge PRs |
| [linux-cockpit](https://github.com/Nueramarcos/linux-cockpit) | Terminal desires + modular zsh |
| [orion-ai-agent](https://github.com/Nueramarcos/orion-ai-agent) | AST bug tracing |
| [build-composer](https://github.com/Nueramarcos/build-composer) | LangGraph architect/coder/reviewer |

## Upstream

Open PRs on [tinygrad](https://github.com/tinygrad/tinygrad/pull/16683), [torchvision](https://github.com/pytorch/vision/pulls?q=author%3ANueramarcos), and others. Playbook: [CONTRIBUTING-UPSTREAM.md](https://github.com/Nueramarcos/issue-agent/blob/main/docs/CONTRIBUTING-UPSTREAM.md).

## Machine

Ubuntu workstation · i5-9600K · RX 5700 XT · Ollama local · YOLO agents

---

*The terminal is a workshop. [Write a desire](https://github.com/Nueramarcos/linux-cockpit).*
