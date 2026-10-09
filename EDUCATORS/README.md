# Educators — REAL_ESTATE

**Project:** REAL_ESTATE  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `e4c3bd81aca873673fbf24352ed0ede6bc363443`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ca9620375be8ecc56092051a364bc7e767f3e1a7074bd84551b3689e73907e5b`  
**Date:** October 2026

## Teaching with REAL_ESTATE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `ca9620375be8ecc56092051a364bc7e767f3e1a7074bd84551b3689e73907e5b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
