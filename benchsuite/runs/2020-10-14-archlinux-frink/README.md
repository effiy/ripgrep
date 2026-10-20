---
title: "archlinux-frink benchmark run — ripgrep benchsuite"
tags: [ripgrep, benchmark, performance, grep]
category: "projects/ripgrep/benchsuite/runs"
created: "2020-10-14"
updated: "2026-10-20"
source: "external"
type: "index"
status: "stable"
lifecycle: "active"
---

# archlinux-frink benchmark run

💡 概述

Benchmark run captured on 2020-10-14 via `benchsuite/benchsuite` from the ripgrep repository root.

Command:

    $ ./benchsuite \
          --dir /tmp/benchsuite \
          --raw runs/2020-10-14-archlinux-frink/raw.csv \
          --warmup-iter 1 \
          --bench-iter 5

---

⚡ 功能

Performance comparison across search tools.

---

📊 指标

Tool versions:

    $ rg --version
    ripgrep 12.1.1 (rev def993bad1)
    -SIMD -AVX (compiled)
    +SIMD +AVX (runtime)

    $ grep -V
    grep (GNU grep) 3.4

    $ ag -V
    ag version 2.2.0

    Features:
      +jit +lzma +zlib

    $ git --version
    git version 2.28.0

    $ ugrep --version
    ugrep 3.0.2 x86_64-pc-linux-gnu +avx2 +pcre2_jit +zlib +bzip2 +lzma +lz4
    License BSD-3-Clause: <https://opensource.org/licenses/BSD-3-Clause>
    Written by Robert van Engelen and others: <https://github.com/Genivia/ugrep>

ripgrep compiled from source on commit def993bad1:

    $ cargo build --release --features 'pcre2'

---

🏛️ 设计

「待补充」

---

📁 目录

「待补充」

---

🔗 资源

- ripgrep repository: https://github.com/BurntSushi/ripgrep