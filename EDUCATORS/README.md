# Educators — MONAI

**Project:** MONAI  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/Project-MONAI/MONAI  
**Pinned commit:** `4e8918470f78d89bf1ee3e2bbaceec173c0ff800`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a5f00a9a12262d01315be34dca067b839c7fc2c3deec908a281118445c0a5957`  
**Date:** October 2026

## Teaching with MONAI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a5f00a9a12262d01315be34dca067b839c7fc2c3deec908a281118445c0a5957` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
