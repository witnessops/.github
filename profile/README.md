# WitnessOps org profile receipt (bootstrap)

Trust boundary: this file is public; use it as an aid for reproduction, not as an authority.

## Artifact manifest (minimal)
- `profile/README.md` (this file)

## Receipt schema (JSON)
```json
{
  "receipt_version": 1,
  "subject": "witnessops/.github",
  "artifact": "profile/README.md",
  "hash_fn": "sha256",
  "signer": "optional",
  "manifest_hash": "optional"
}
```

## Challenge path
- recompute: `sha256sum profile/README.md`
- compare with your local copy
- if mismatch, describe repro steps (inputs, commands, env)
