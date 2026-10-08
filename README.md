# VHC Pharmacy POS

Release-only repository for the approved Varnika Health Care (VHC) Pharmacy POS Windows builds.

## Latest Stable Release

**VHC Pharmacy POS v3.19.0**

- Platform: Windows
- Installer: `VHC_Pharmacy_POS_Setup_3.19.0.exe`
- SHA256: `0924C175116CF36DF54E3FB18FE45B8B4560266D1DB2DFDAF3986B3D824903B8`
- Installer size: 109,960,017 bytes

## v3.19.0 Highlights

- No default or sticky payment mode on new bills/tabs
- Cash Received / Change shown only for Cash, inside the payment card below Discount and above Net Total
- Per-tab Custom Charge draft isolation
- Inline Split Payment with Cash + UPI exact-total validation
- Unified Bill Details across All Bills, Patient Name and Payments
- Historical/cloud bill Return / Exchange support
- Exact-original-batch stock restoration
- Fail-closed handling for missing, ambiguous or unsafe historical return mappings
- Local/offline returns preserved
- Production cloud-return RPC migration completed with no existing-data drift

## Download & Verify

Download the approved installer from this repository's **Releases** page.

On Windows PowerShell:

```powershell
Get-FileHash .\VHC_Pharmacy_POS_Setup_3.19.0.exe -Algorithm SHA256
```

Expected SHA256:

```text
0924C175116CF36DF54E3FB18FE45B8B4560266D1DB2DFDAF3986B3D824903B8
```

If the hash does not match exactly, do not install the file.

## Previous Stable Release

**v3.18.3**
- Installer: `VHC_Pharmacy_POS_Setup_3.18.3.exe`
- SHA256: `A9E2E61707274BBF5B69647F11690B9A4912023A06B0EA048F5835E886DA4860`

## Documentation

- `docs/RELEASE_NOTES_v3.19.0.md`
- `docs/RELEASE_NOTES_v3.18.3.md`
- `docs/VERIFY_DOWNLOAD.md`

## Repository Purpose

This repository is for approved release artifacts and release documentation only.

Development source code, TEST artifacts, backups, QA profiles, superseded builds and experimental work must not be published here.
