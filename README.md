# VHC Pharmacy POS

Release-only repository for the approved Varnika Health Care (VHC) Pharmacy POS Windows builds.

## Latest Stable Release

**VHC Pharmacy POS v3.19.1**

- Platform: Windows
- Installer: `VHC_Pharmacy_POS_Setup_3.19.1.exe`
- SHA256: `65EB9F35DBDF7C0B7666507AF89691DE01367A44D92C74A4AB8FA241DC7308BE`
- Installer size: 109,960,248 bytes

## v3.19.1 Fix

- Reports Bill Count counts distinct bills rather than payment rows.
- Split payment transaction rows and payment totals remain unchanged.

## Download & Verify

Download the approved installer from this repository's **Releases** page.

On Windows PowerShell:

```powershell
Get-FileHash .\VHC_Pharmacy_POS_Setup_3.19.1.exe -Algorithm SHA256
```

Expected SHA256:

```text
65EB9F35DBDF7C0B7666507AF89691DE01367A44D92C74A4AB8FA241DC7308BE
```

If the hash does not match exactly, do not install the file.

## Previous Stable Release

**v3.19.0**
- Installer: `VHC_Pharmacy_POS_Setup_3.19.0.exe`
- SHA256: `0924C175116CF36DF54E3FB18FE45B8B4560266D1DB2DFDAF3986B3D824903B8`

## Documentation

- `docs/RELEASE_NOTES_v3.19.1.md`
- `docs/RELEASE_NOTES_v3.19.0.md`
- `docs/RELEASE_NOTES_v3.18.3.md`
- `docs/VERIFY_DOWNLOAD.md`

## Repository Purpose

This repository is for approved release artifacts and release documentation only.

Development source code, TEST artifacts, backups, QA profiles, superseded builds and experimental work must not be published here.
