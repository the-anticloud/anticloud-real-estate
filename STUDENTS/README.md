# Students — REAL_ESTATE

**Project:** REAL_ESTATE  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `e4c3bd81aca873673fbf24352ed0ede6bc363443`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ca9620375be8ecc56092051a364bc7e767f3e1a7074bd84551b3689e73907e5b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e4c3bd81aca873673fbf24352ed0ede6bc363443`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `ca9620375be8ecc56092051a364bc7e767f3e1a7074bd84551b3689e73907e5b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
