---
title: "grep-matcher — low-level regex matcher interface"
tags: [rust, regex, matcher, trait, ripgrep]
category: "projects/ripgrep/crates/matcher"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# grep-matcher

💡 概述

This crate provides a low level interface for describing regular expression matchers. The `grep` crate uses this interface in order to make the regex engine it uses pluggable.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/grep-matcher.svg)](https://crates.io/crates/grep-matcher)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- `Matcher` trait definition for pluggable regex engines
- Abstraction layer for `grep-regex` and `grep-pcre2`

---

📊 指標

「待补充」

---

🏛️ 设计

**NOTE:** You probably don't want to use this crate directly. Instead, prefer the facade defined in the [`grep`](https://docs.rs/grep) crate.

---

📁 目录

「待补充」

---

🔗 资源

- Documentation: https://docs.rs/grep-matcher
- Cargo: `grep-matcher = "0.1"`