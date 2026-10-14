# How to Update — BOTFRAMEWORK

**Project:** `BOTFRAMEWORK`
**Category:** CHAT_PLATFORMS
**Domain:** chat platforms and messaging
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
BOTFRAMEWORK --version
BOTFRAMEWORK check-update
```

### Applying Updates
```bash
pip install --upgrade BOTFRAMEWORK
```

### Rolling Back
```bash
pip install BOTFRAMEWORK==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
