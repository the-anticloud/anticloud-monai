# Ethics — MONAI

**Project:** MONAI  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/Project-MONAI/MONAI  
**Pinned commit:** `4e8918470f78d89bf1ee3e2bbaceec173c0ff800`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a5f00a9a12262d01315be34dca067b839c7fc2c3deec908a281118445c0a5957`  
**Date:** October 2026

## Position

MONAI is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
