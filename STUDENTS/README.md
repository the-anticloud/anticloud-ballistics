# Students — BALLISTICS

**Project:** BALLISTICS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e6df72b489d49de3e7bf0697da1dadaaa4b946a6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2812eac6b5dfdb3e682ccb6b133e1f0dc6dbefbd94e2635af6fbf2e7e95cccc`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e6df72b489d49de3e7bf0697da1dadaaa4b946a6`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f2812eac6b5dfdb3e682ccb6b133e1f0dc6dbefbd94e2635af6fbf2e7e95cccc`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
