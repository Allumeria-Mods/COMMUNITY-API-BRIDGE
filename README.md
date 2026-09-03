# Allumeria Community API Bridge

Public runtime compatibility content and release distribution for the Allumeria Community API Bridge.

## Current release

- Bridge release: `0.15.5`
- Supported game build: `0.15.5`
- Distribution artifact: `Allumeria-Community-Bridge-0.15.5.zip`

## Browse the public runtime content

The release-synchronized, human-reviewable compatibility snapshot is available under:

```text
content/0.15.5/compatibility/
├── manifest.json
├── manifest.schema.json
├── semantic-targets.json
├── translation-review.json
└── localization-schema-corrections.json
```

Each published file is byte-for-byte synchronized with the corresponding file shipped in the `0.15.5` release archive.

## Installation

Download `Allumeria-Community-Bridge-0.15.5.zip` from the `0.15.5` GitHub Release and extract it into the Allumeria installation root while preserving archive paths.

The release archive contains the complete runtime payload, including Bridge DLLs and the larger generated compatibility datasets that are not mirrored into the Git branch.

## Repository scope

This public repository exposes reviewable runtime compatibility content and release metadata, but not the private engineering project. C# source, tests, build tooling, SPEC documents, acceptance evidence, compatibility recovery tooling, and other engineering material remain in the private Engineering repository.

`distribution.json` is the machine-readable release index and records the exact release artifact and public content identities.
