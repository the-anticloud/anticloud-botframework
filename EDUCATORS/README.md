# Educators — BOTFRAMEWORK

**Project:** BOTFRAMEWORK  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `ed8adc25069b8f94c18ff34cf834741f993dc360`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `da623a0b61e31a071d3ac9ddda14285d4a217d52ea61ba91909ad5007a689f8b`  
**Date:** October 2026

## Teaching with BOTFRAMEWORK

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `da623a0b61e31a071d3ac9ddda14285d4a217d52ea61ba91909ad5007a689f8b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
