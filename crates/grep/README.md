---
title: "grep — ripgrep as a library facade"
tags: [rust, grep, library, ripgrep]
category: "projects/ripgrep/crates/grep"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# grep

💡 概述

ripgrep, as a library. This crate provides a facade over the grep-* subcrates.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/grep.svg)](https://crates.io/crates/grep)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- Facade unifying grep-matcher, grep-regex, grep-searcher, grep-printer, grep-cli
- Optional PCRE2 support via `pcre2` feature

---

📊 指标

「待补充」

---

🏛️ 设计

NOTE: This crate isn't ready for wide use yet. Ambitious individuals can probably piece together the parts, but there is no high level documentation describing how all of the pieces fit together.

---

📁 目录

「待补充」

---

🔗 资源

- Documentation: https://docs.rs/grep
- Cargo: `grep = "0.2"`
- Feature: `pcre2` re-exports `grep-pcre2` as alternative `Matcher`