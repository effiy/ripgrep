---
title: "globset — cross-platform glob matching for Rust"
tags: [rust, glob, pattern-matching, regex]
category: "projects/ripgrep/crates/globset"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# globset

💡 概述

Cross platform single glob and glob set matching. Glob set matching is the process of matching one or more glob patterns against a single candidate path simultaneously, and returning all of the globs that matched.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/globset.svg)](https://crates.io/crates/globset)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- Single glob matching
- Glob set matching (multiple patterns simultaneously)
- Configurable match semantics via `GlobBuilder`
- Case insensitive and require-literal-separator options
- Non-UTF-8 path support
- Alternate "or" globs (`*.{foo,bar}`)

---

📊 指标

Performance benchmarks:

```
test ext_glob             ... bench:         425 ns/iter (+/- 21)
test ext_regex            ... bench:         175 ns/iter (+/- 10)
test long_glob            ... bench:         182 ns/iter (+/- 11)
test long_regex           ... bench:         173 ns/iter (+/- 10)
test short_glob           ... bench:          69 ns/iter (+/- 4)
test short_regex          ... bench:          83 ns/iter (+/- 2)
test many_short_glob      ... bench:       1,063 ns/iter (+/- 47)
test many_short_regex_set ... bench:         186 ns/iter (+/- 11)
```

---

🏛️ 设计

Implements globs by converting them to regular expressions, executed with the `regex` crate. Primary advantage over the `glob` crate is simultaneous multi-glob matching.

---

📁 目录

「待补充」

---

🔗 资源

- Documentation: https://docs.rs/globset
- Cargo: `globset = "0.4"`
- Feature: `serde1` enables Serde traits on `Glob`