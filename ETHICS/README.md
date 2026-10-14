# Ethics — BALLISTICS

**Project:** BALLISTICS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e6df72b489d49de3e7bf0697da1dadaaa4b946a6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2812eac6b5dfdb3e682ccb6b133e1f0dc6dbefbd94e2635af6fbf2e7e95cccc`  
**Date:** October 2026

## Position

BALLISTICS is packaged for offline deployment with a verifiable audit trail. The
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
