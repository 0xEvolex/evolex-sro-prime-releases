# SRO Prime releases

Signed releases of SRO Prime. This repository holds no source code: only release files and
`latest.json`, which the SRO Prime updater reads.

## Verifying a release

Every release carries `manifest.json` with a detached Ed25519 signature `manifest.json.sig`, and
`installer.json` with `installer.json.sig`. SRO Prime checks both against the release keys built
into it before it installs anything. Current release key ids:

- `65a98ab64177f333` (primary)
- `efc5ba96cbfd00bc` (recovery)

The installer's SHA-256 is listed in each release's notes.

Support: the SRO Prime Discord.
