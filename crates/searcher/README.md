---
title: "grep-searcher — fast line-oriented search engine"
tags: [rust, grep, search, ripgrep]
category: "projects/ripgrep/crates/searcher"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# grep-searcher

💡 概述

A high level library for executing fast line oriented searches. This handles things like reporting contextual lines, counting lines, inverting a search, detecting binary data, automatic UTF-16 transcoding and deciding whether or not to use memory maps.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/grep-searcher.svg)](https://crates.io/crates/grep-searcher)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- Context line reporting
- Line counting and invert search
- Binary data detection
- Automatic UTF-16 transcoding
- Memory map decision logic

---

📊 指標

「待補充」

---

🏛️ 设计

**NOTE:** You probably don't want to use this crate directly. Instead, prefer the facade defined in the [`grep`](https://docs.rs/grep) crate.

---

📁 目录

「待補充」

---

🔗 资源

- Documentation: https://docs.rs/grep-searcher
- Cargo: `grep-searcher = "0.1"`