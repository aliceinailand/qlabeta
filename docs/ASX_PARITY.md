# ASX Parity Manifest (OL-027)

**Canonical implementation:** [aliceinailand/alisonscorpion](https://github.com/aliceinailand/alisonscorpion)

## Mirrored contracts

| qlabeta path | alisonscorpion source |
|--------------|----------------------|
| `docs/qla-genesis-v1.json` | `data/qla/qla-genesis-v1.json` |
| `docs/qla-genesis-v1.schema.json` | `data/qla/qla-genesis-v1.schema.json` |

## Archive ID lock

Both repos must agree on `archive_id: qla-genesis-v1` and `schema_version: 1.0.0`.

## Verification

Run in alisonscorpion:

```bash
python tools/qlabeta_parity_check.py
```

Synced: 2026-07-04 by MGROK delegation Cycle 8.
