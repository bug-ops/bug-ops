# Hi, I'm Andrei

**Rust Performance Engineer | AI Tooling Architect**

I build high-performance systems that solve real problems. My work spans from SIMD-accelerated parsers to AI agent infrastructure—always with a focus on measurable impact.

---

## Open Source Contributions

Core contributor to foundational AI infrastructure:

| Project | Contributions | |
|---------|---------------|:-:|
| [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) | Elicitation support, context-aware completion | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [restatedev/restate](https://github.com/restatedev/restate) | Shell completion for restatectl | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [zed-industries/extensions](https://github.com/zed-industries/extensions) | Deps extension *(in review)* | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |

---

## AI Agent Infrastructure

> [!NOTE]
> Tools that make AI agents cheaper and smarter.

| Project | What it does | Impact | |
|---------|--------------|--------|:-:|
| [mcp-execution](https://github.com/bug-ops/mcp-execution) | MCP servers → standalone TypeScript tools | **98% token savings** | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [claude-plugins](https://github.com/bug-ops/claude-plugins) | 8 specialized Rust agents for Claude Code | Full dev lifecycle coverage | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?logo=gnubash&logoColor=white&style=flat-square) |
| [mcpls](https://github.com/bug-ops/mcpls) | MCP ↔ LSP bridge | Semantic code intelligence for AI | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [pjs](https://github.com/bug-ops/pjs) | Priority JSON Streaming + SIMD | **6x faster** than standard parsers | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [tap-mcp-bridge](https://github.com/bug-ops/tap-mcp-bridge) | Visa TAP + MCP integration | Secure payment auth for AI agents | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |

> [!TIP]
> Start with [mcp-execution](https://github.com/bug-ops/mcp-execution) — it's the foundation for token-efficient AI workflows.

## High-Performance Parsers

> [!NOTE]
> When standard libraries aren't fast enough.

| Project | What it does | Impact | |
|---------|--------------|--------|:-:|
| [fast-yaml](https://github.com/bug-ops/fast-yaml) | YAML 1.2.2, zero unsafe, built-in linter | **14x faster** than PyYAML | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square)![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square)![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white&style=flat-square) |
| [feedparser-rs](https://github.com/bug-ops/feedparser-rs) | RSS/Atom/JSON Feed + all extensions | **213 MB/s** · 94x faster | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square)![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square)![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white&style=flat-square) |

> [!IMPORTANT]
> Both parsers have Python and Node.js bindings — drop-in replacements for existing code.

## Developer Tools

> [!NOTE]
> Tools I wish existed.

| Project | What it does | Impact | |
|---------|--------------|--------|:-:|
| [deps-lsp](https://github.com/bug-ops/deps-lsp) | Universal dependency management LSP | Cargo + npm + PyPI | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [helix-trainer](https://github.com/bug-ops/helix-trainer) | FSRS spaced repetition for Helix | **30% fewer** reviews than Anki | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |

---

## Archive

> [!NOTE]
> Completed projects no longer in active development.

| Project | What it was | |
|---------|-------------|:-:|
| [vkteams-bot](https://github.com/bug-ops/vkteams-bot) | VK Teams Bot ecosystem: CLI + MCP + vector storage | ![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square) |
| [vkteams-bot-clj](https://github.com/bug-ops/vkteams-bot-clj) | VK Teams Bot implementation | ![Clojure](https://img.shields.io/badge/-Clojure-5881D8?logo=clojure&logoColor=white&style=flat-square) |

---

## Principles

```
Performance is a feature     →  Criterion benchmarks in every project
Safety is non-negotiable     →  #![forbid(unsafe_code)] by default
Standards matter             →  YAML 1.2.2, not 1.1. Rust 2024 edition.
Cross-platform by design     →  PyO3 + napi-rs bindings from day one
```

---

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=bug-ops&show_icons=true&theme=transparent&hide_border=true&hide_title=true&include_all_commits=true&rank_icon=github" alt="GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bug-ops&layout=compact&theme=transparent&hide_border=true&langs_count=6" alt="Top Languages" height="165" />
</p>

---

<p align="center">
Building infrastructure for AI agents that doesn't waste context on ceremony.<br><br>
If your MCP server loads 30k tokens and uses 3 tools, <b>we should talk</b>.
</p>

<p align="center">
<a href="https://github.com/bug-ops?tab=repositories">View All Projects →</a>
</p>
