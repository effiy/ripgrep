---
title: "grep-pcre2 — PCRE2 Matcher implementation for ripgrep"
tags: [rust, pcre2, regex, grep, ripgrep]
category: "projects/ripgrep/crates/pcre2"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# grep-pcre2

💡 概述

The `grep-pcre2` crate provides an implementation of the `Matcher` trait from the `grep-matcher` crate. This implementation permits PCRE2 to be used in the `grep` crate for fast line oriented searching.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/grep-pcre2.svg)](https://crates.io/crates/grep-pcre2)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- `Matcher` trait implementation backed by PCRE2
- Enables PCRE2 regex syntax in ripgrep

---

📊 指標

「待補充」

---

🏛️ 設計

**NOTE:** You probably don't want to use this crate directly. Instead, prefer the facade defined in the [`grep`](https://docs.rs/grep) crate.

If you're looking to just use PCRE2 from Rust, then you probably want the [`pcre2`](https://docs.rs/pcre2) crate, which provides high level safe bindings to PCRE2.

---

📁 目录

「待補充」

---

🔗 资源

- Documentation: https://docs.rs/grep-pcre2
- Cargo: `grep-pcre2 = "0.1"`