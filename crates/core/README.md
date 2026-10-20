---
title: "ripgrep core — main crate with CLI definition and glue code"
tags: [rust, ripgrep, cli, grep]
category: "projects/ripgrep/crates/core"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# ripgrep core

💡 概述

This is the core ripgrep crate. `main.rs` is where the `main` function lives.

Most of ripgrep core consists of two things:

- The definition of the CLI interface, including docs for every flag.
- Glue code that brings the `grep-matcher`, `grep-regex`, `grep-searcher` and `grep-printer` crates together to actually execute the search.

Currently, there are no plans to make ripgrep core available as an independent library. However, much of the heavy lifting of ripgrep is done via its constituent crates, which can be reused independent of ripgrep.

---

⚡ 功能

- CLI interface definition with full flag documentation
- Orchestration of grep-* subcrates for search execution

---

📊 指标

「待补充」

---

🏛️ 设计

「待补充」

---

📁 目录

「待补充」

---

🔗 资源

「待补充」