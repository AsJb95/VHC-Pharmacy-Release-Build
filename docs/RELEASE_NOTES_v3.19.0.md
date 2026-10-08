# VHC Pharmacy POS v3.19.0 — Release Notes

## Status

v3.19.0 is the current approved stable production release.

## Billing

- New bills and tabs start with no payment mode selected.
- Payment mode does not leak between bills or tabs.
- Cash Received and Change to Return appear only for Cash, inside the payment card below Discount and above Net Total.
- Custom Charge draft state is isolated per billing tab.
- Split Payment is inline; Cash + UPI must equal the Net Total before completion.

## Reports

- All Bills, Patient Name and Payments open the same Bill Details view.
- Return / Exchange availability and reasons are consistent across those report views.

## Returns

- Historical/cloud bills can be returned when the original stock mapping is safely reconstructable.
- Stock is restored to the exact original batch.
- Partial returns and repeat submissions are protected.
- Unsafe or ambiguous historical cases fail closed without stock or financial mutation.
- Local/offline returns continue to work.

## Production Migration

Migration:

```text
20261008000100_v3190_cloud_sale_return_rpc.sql
```

The production migration completed after fresh backup, restore validation and restored-copy rehearsal.

Production PRE/POST row counts, stock total and stock checksum remained unchanged by the migration.

## Verified Installer

Filename:

```text
VHC_Pharmacy_POS_Setup_3.19.0.exe
```

SHA256:

```text
0924C175116CF36DF54E3FB18FE45B8B4560266D1DB2DFDAF3986B3D824903B8
```

Installer size:

```text
109,960,017 bytes
```

Only this approved installer should be published for v3.19.0. Superseded review builds must not be published.
