# Ethics — REAL_ESTATE

**Project:** REAL_ESTATE  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `e4c3bd81aca873673fbf24352ed0ede6bc363443`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ca9620375be8ecc56092051a364bc7e767f3e1a7074bd84551b3689e73907e5b`  
**Date:** October 2026

## Position

REAL_ESTATE is packaged for offline deployment with a verifiable audit trail. The
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
