# Ethics — BOTFRAMEWORK

**Project:** BOTFRAMEWORK  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `ed8adc25069b8f94c18ff34cf834741f993dc360`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `da623a0b61e31a071d3ac9ddda14285d4a217d52ea61ba91909ad5007a689f8b`  
**Date:** October 2026

## Position

BOTFRAMEWORK is packaged for offline deployment with a verifiable audit trail. The
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
