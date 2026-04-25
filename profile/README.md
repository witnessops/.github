# WitnessOps

Verification infrastructure for governed workflows.

WitnessOps separates authority, execution, evidence, receipt, and verification so consequential workflows can produce portable proof bundles that third parties can inspect.

## Trust boundary

This GitHub organization is a publication and source-control surface. It is not, by itself, proof of operational execution.

A claim is only treated as verified when a receipt, artifact hash, signer or key reference, and verifier result are present.

## Public proof path

1. Protocol and reference verification materials:
   - `witnessops-proof-reference`

2. Sample proof cases:
   - `witnessops-sample-cases`

3. Public trust surface:
   - `witnessops-web`

4. Governed workflow examples:
   - `witnessops-governed-recon`

## Repository classes

- Protocol and verifier reference
- Sample proof cases
- Public trust surface
- Governed workflow examples
- Compliance and control catalogs
- Internal execution, authority, and governance systems

## Verification rule

Do not trust claims from README text alone. Prefer:

- signed receipts
- artifact manifests
- schema validation
- reproducible verifier output
- challenge paths

## Bootstrap receipt note

This profile README is public and can aid reproduction, but it is not an authority by itself.

Challenge path:

```bash
sha256sum profile/README.md
```

If a reproduced hash differs from a published receipt, treat the claim as untrusted until the mismatch is explained.
