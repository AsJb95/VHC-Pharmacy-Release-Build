# VHC Pharmacy POS

Windows desktop pharmacy billing and inventory application for Varnika Health Care (VHC).

## Current Stable Release

**VHC Pharmacy POS v3.18.3**

- Platform: Windows
- Installer: `VHC_Pharmacy_POS_Setup_3.18.3.exe`
- SHA256: `A9E2E61707274BBF5B69647F11690B9A4912023A06B0EA048F5835E886DA4860`

## Highlights

- Pharmacy billing and cart workflow
- Cash, UPI, Card/Credit and Split Payment support
- Payment reporting and filtering
- Inventory and stock movement workflows
- Warehouse ↔ Pharmacy transfer support
- Credit settlement support
- Reports with local-date handling and summary cards
- Telegram bot integration and security improvements
- Local/offline return improvements
- Light/Dark theme support

## Important v3.18.3 Note

Historical/cloud bill returns remain intentionally fail-closed in v3.18.3.  
The production-safe historical return redesign is being developed separately for v3.19.0.

## Installation

1. Download `VHC_Pharmacy_POS_Setup_3.18.3.exe` from the repository Releases page.
2. Verify the SHA256 checksum before installation.
3. Run the installer on the approved Windows PC.
4. Launch **VHC Pharmacy POS** and verify login, billing, reports and configured integrations.

## Verify SHA256 on Windows

Open PowerShell in the installer folder and run:

```powershell
Get-FileHash .\VHC_Pharmacy_POS_Setup_3.18.3.exe -Algorithm SHA256
```

Expected SHA256:

```text
A9E2E61707274BBF5B69647F11690B9A4912023A06B0EA048F5835E886DA4860
```

## Version Policy

- **v3.18.3** is the frozen stable baseline.
- New development continues under **v3.19.0**.
- v3.19.0 changes must not be mixed back into the v3.18.3 release.

## Release Documentation

See:
- `docs/RELEASE_NOTES_v3.18.3.md`
- `docs/VERIFY_DOWNLOAD.md`

## Repository Purpose

This repository is intended to hold stable VHC Pharmacy POS release information and approved release assets. Development work should remain in the main development repository and only verified release artifacts should be published here.
