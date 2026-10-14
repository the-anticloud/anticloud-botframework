# Students — BOTFRAMEWORK

**Project:** BOTFRAMEWORK  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `ed8adc25069b8f94c18ff34cf834741f993dc360`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `da623a0b61e31a071d3ac9ddda14285d4a217d52ea61ba91909ad5007a689f8b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ed8adc25069b8f94c18ff34cf834741f993dc360`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `da623a0b61e31a071d3ac9ddda14285d4a217d52ea61ba91909ad5007a689f8b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
