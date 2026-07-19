# PDPA profiles (Thailand)

Versioned, machine-readable definitions of Thailand PDPA statutory processes — the exact transition tables the Open DG AI platform executes. Published under Apache-2.0 so any tool can adopt them.

| Artifact | Covers | Statutory clock |
|---|---|---|
| `rights-request-workflow.v1.json` | Data subject rights (§30–§36) end-to-end handling | 30 days from receipt; pauses only during identity verification (pauses must be recorded) |
| `breach-workflow.v1.json` | Personal data breach handling (§37(4)) | 72 hours from awareness to PDPC notification; awareness timestamp locks after first notification |

**Versioning**: regulatory or guidance changes produce a new `vN` file; existing versions are never edited in place — an audit trail for the definitions themselves.

**Not legal advice.** These artifacts describe statutory processes to support compliance operations; they do not guarantee compliance (see repository README).
