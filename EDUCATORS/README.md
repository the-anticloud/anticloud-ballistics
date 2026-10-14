# Educators — BALLISTICS

**Project:** BALLISTICS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e6df72b489d49de3e7bf0697da1dadaaa4b946a6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2812eac6b5dfdb3e682ccb6b133e1f0dc6dbefbd94e2635af6fbf2e7e95cccc`  
**Date:** October 2026

## Teaching with BALLISTICS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f2812eac6b5dfdb3e682ccb6b133e1f0dc6dbefbd94e2635af6fbf2e7e95cccc` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
