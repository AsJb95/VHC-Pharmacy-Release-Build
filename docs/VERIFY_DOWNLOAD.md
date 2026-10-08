# Verify the v3.18.3 Installer

Before installing, verify that the downloaded installer matches the approved checksum.

## Approved File

```text
VHC_Pharmacy_POS_Setup_3.18.3.exe
```

## Approved SHA256

```text
A9E2E61707274BBF5B69647F11690B9A4912023A06B0EA048F5835E886DA4860
```

## PowerShell

```powershell
Get-FileHash .\VHC_Pharmacy_POS_Setup_3.18.3.exe -Algorithm SHA256
```

The resulting hash must exactly match the approved SHA256 above.

If it does not match, do not install that file.
