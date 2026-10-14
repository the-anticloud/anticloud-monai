# Students — MONAI

**Project:** MONAI  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/Project-MONAI/MONAI  
**Pinned commit:** `4e8918470f78d89bf1ee3e2bbaceec173c0ff800`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a5f00a9a12262d01315be34dca067b839c7fc2c3deec908a281118445c0a5957`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4e8918470f78d89bf1ee3e2bbaceec173c0ff800`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `a5f00a9a12262d01315be34dca067b839c7fc2c3deec908a281118445c0a5957`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
