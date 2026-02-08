# Cryptographic Keys

This directory contains **public cryptographic keys** used for verification purposes in the Evocracy project.

These keys are provided to enable independent verification of:

- signed Git commits
- signed Genesis artifacts (after Genesis)
- published hash manifests

No private keys are ever stored or referenced here.

---

## Primary Signing Key

The primary public signing key currently published is:

- **Key purpose:** Evocracy canonical artifacts and verification
- **Key type:** Public (verification only)
- **Scope:** Project-level (not part of the Canon)

Example file: `evocracy-signing-key.asc`.

The corresponding private key is held offline and is not accessible via this repository.

---

## Canonical Status

Cryptographic keys are **not part of the Canon**.

Keys may be:
- rotated
- superseded
- revoked

without affecting the canonical Core or its immutability.

Canonical trust derives from:
- anchored hashes
- verified signatures
- published verification instructions

---

## Genesis Usage (planned)

At Genesis, the signing key will be used to sign:

- the canonical Core hash manifest
- Genesis declaration files

Verification instructions will be provided in `CANON.md` and `GENESIS.md`.

---

## Security Note

Trust is placed in **verifiable artifacts**, not identities.

Keys exist to enable verification — not to establish authority.

---
