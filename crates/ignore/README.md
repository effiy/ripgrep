---
title: "ignore — fast recursive directory iterator with gitignore support"
tags: [rust, gitignore, walk, file-system, ripgrep]
category: "projects/ripgrep/crates/ignore"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# ignore

💡 概述

The ignore crate provides a fast recursive directory iterator that respects various filters such as globs, file types and `.gitignore` files. Also provides lower level direct access to gitignore and file type matchers.

[![Build status](https://github.com/BurntSushi/ripgrep/workflows/ci/badge.svg)](https://github.com/BurntSushi/ripgrep/actions)
[![](https://img.shields.io/crates/v/ignore.svg)](https://crates.io/crates/ignore)

Dual-licensed under MIT or the [UNLICENSE](https://unlicense.org/).

---

⚡ 功能

- Recursive directory walking with filters
- `.gitignore` / `.ignore` file support
- File type matching
- Hidden file filtering (configurable)

---

📊 指標

「待补充」

---

🏛️ 设计

WalkBuilder provides configurable iterator construction:

```rust
use ignore::WalkBuilder;

for result in WalkBuilder::new("./").hidden(false).build() {
    println!("{:?}", result);
}
```

---

📁 目录

「待补充」

---

🔗 资源

- Documentation: https://docs.rs/ignore
- Cargo: `ignore = "0.4"`