---
title: "archlinux-duff benchmark run — ripgrep benchsuite"
tags: [ripgrep, benchmark, performance, grep]
category: "projects/ripgrep/benchsuite/runs"
created: "2022-12-16"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# archlinux-duff benchmark run

💡 概述

Benchmark run captured on 2022-12-16 via `benchsuite/benchsuite` from the ripgrep repository root.

Command:

    $ ./benchsuite \
          --dir /dev/shm/benchsuite \
          --raw runs/2022-12-16-archlinux-duff/raw.csv \
          | tee runs/2022-12-16-archlinux-duff/summary

---

⚡ 功能

Performance comparison across search tools.

---

📊 指标

Tool versions:

    $ rg --version
    ripgrep 13.0.0 (rev 87c4a2b4b1)
    -SIMD -AVX (compiled)
    +SIMD +AVX (runtime)

    $ grep -V
    grep (GNU grep) 3.8

    $ ag -V
    ag version 2.2.0

    Features:
      +jit +lzma +zlib

    $ git --version
    git version 2.39.0

    $ ugrep --version
    ugrep 3.9.2 x86_64-pc-linux-gnu +avx2 +pcre2jit +zlib +bzip2 +lzma +lz4 +zstd
    License BSD-3-Clause: <https://opensource.org/licenses/BSD-3-Clause>
    Written by Robert van Engelen and others: <https://github.com/Genivia/ugrep>

ripgrep compiled from source on commit 7f23cd63:

    $ cargo build --release --features 'pcre2'

Machine: Intel i9-12900K with 128GB of memory.

---

🏛️ 设计

「待补充」

---

📁 目录

「待补充」

---

🔗 资源

- ripgrep repository: https://github.com/BurntSushi/ripgrep