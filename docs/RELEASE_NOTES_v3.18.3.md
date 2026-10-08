# VHC Pharmacy POS v3.18.3 — Release Notes

## Status

v3.18.3 is the frozen stable production baseline.

## Included

- Reports local-date fix
- Reports top summary cards
- Settings and UI improvements already approved for the stable build
- Payment/cash fixes
- Telegram security and reliability fixes
- Local/offline return improvements
- Existing inventory, stock transfer and reporting workflows

## Historical / Cloud Returns

Historical/cloud returns are intentionally not enabled in v3.18.3.

If a historical bill is visible from cloud/report history but the local return context is unavailable, the app fails closed rather than guessing stock or batch data.

The redesigned historical return flow is planned for v3.19.0 and is not part of this stable release.

## Verified Installer

Filename:

```text
VHC_Pharmacy_POS_Setup_3.18.3.exe
```

SHA256:

```text
A9E2E61707274BBF5B69647F11690B9A4912023A06B0EA048F5835E886DA4860
```

## Release Safety

- v3.18.3 should not be rebuilt for routine release publication.
- New feature work belongs to v3.19.0.
- Production database changes are not part of this release package.
