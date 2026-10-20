---
title: "grep-regex — Rust regex Matcher implementation for ripgrep"
tags: [rust, regex, grep, ripgrep]
category: "projects/ripgrep/crates/regex"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# grep-regex

💡 概述

The `grep-regex` crate provides an implementation of the `Matcher` trait from the `grep-matcher` crate. This implementation permits Rust's regex engine to be used in the `grep` crate for fast line oriented searching.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/grep-regex.svg)](https://crates.io/crates/grep-regex)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- `Matcher` trait implementation backed by Rust's `regex` crate
- Default regex engine for ripgrep

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

- Documentation: https://docs.rs/grep-regex
- Cargo: `grep-regex = "0.1"`