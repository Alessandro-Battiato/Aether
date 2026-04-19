# Aether

A full-stack AI chat application powered by [OpenRouter](https://openrouter.ai). Supports real-time streaming responses, multiple AI models, and persistent conversation history.

This repository contains two independent projects managed as Git submodules:

| Folder | Description |
|---|---|
| [`Client/`](./Client) | React + Vite front-end — chat UI, sidebar, streaming |
| [`Server/`](./Server) | Node.js + Express + Prisma back-end — REST API, auth, AI integration |

## Getting started

Clone with submodules:

```bash
git clone --recurse-submodules <repo-url>
```

Then follow the setup instructions in each sub-project's README:

- **[Client README](./Client/README.md)** — environment variables, dev server, production build
- **[Server README](./Server/README.md)** — database setup, environment variables, API reference
