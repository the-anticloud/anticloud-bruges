# Educators — BRUGES

**Project:** BRUGES  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `905fe4fee2bd03f4852ecaacd9a004d84ed8441f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `278e4c2dd9d69a697b5cc9a4472a3c5f710070fb6776d6dedd911cd4a8ad40bb`  
**Date:** October 2026

## Teaching with BRUGES

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `278e4c2dd9d69a697b5cc9a4472a3c5f710070fb6776d6dedd911cd4a8ad40bb` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
