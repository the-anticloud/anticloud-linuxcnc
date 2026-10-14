# How to Update — LINUXCNC

**Project:** `LINUXCNC`
**Category:** FACTORY_MANUFACTURING
**Domain:** factory manufacturing and automation
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
LINUXCNC --version
LINUXCNC check-update
```

### Applying Updates
```bash
pip install --upgrade LINUXCNC
```

### Rolling Back
```bash
pip install LINUXCNC==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
