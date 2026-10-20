---
title: "windows — Windows manifest for ripgrep binary"
tags: [ripgrep, windows, manifest, long-path]
category: "projects/ripgrep/pkg/windows"
created: "2026-10-20"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# Windows manifest

💡 概述

This directory contains a Windows manifest for various Windows-specific settings.

The main thing enabled here is `longPathAware`, which permits paths of the form `C:\` to be longer than 260 characters.

The approach taken here was modeled off of a [similar change for `rustc`](https://github.com/rust-lang/rust/pull/96737). In particular, this manifest gets linked into the final binary. Those linker arguments are applied in `build.rs`.

---

⚡ 功能

- `longPathAware` manifest setting
- MSVC build support (GNU patches welcome)

---

📊 指标

「待補充」

---

🏛️ 设计

This currently only applies to MSVC builds. If there's an easy way to make this apply to GNU builds as well, then patches are welcome.

---

📁 目录

「待補充」

---

🔗 资源

- [longPathAware documentation](https://learn.microsoft.com/en-us/windows/win32/sbscs/application-manifests#longpathaware)
- [rustc PR reference](https://github.com/rust-lang/rust/pull/96737)