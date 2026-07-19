## Licensing Model

Open DG AI uses a **split licensing model** to balance regulatory clarity, accountability, and ecosystem interoperability.

### Platform & Runtime Components
The Open DG AI platform, including managed cloud services and prebuilt container images, is provided under a **commercial license**.

This ensures:
- A single authoritative implementation
- Consistent governance behavior
- Clear accountability in regulated environments

Source code for the core platform is not publicly distributed.

### Open Artifacts
The following artifacts are released under the **Apache License 2.0**:
- Data governance schemas
- PDPA and GDPR profile definitions (as data)
- Policy examples
- Deployment manifests
- SDKs and integration libraries
- Documentation

These artifacts are open to promote transparency, interoperability, and integration.

### Important Note
Open DG AI is a technology platform that supports governance and compliance efforts.
It does not provide legal advice, regulatory approval, or compliance certification.

# Transparency & Accountability Statement  
**Open DG AI**

---

## Our Position

Open DG AI is a **governance-support technology platform** designed for use in regulated data environments.

We believe transparency and accountability are essential for trust — especially when AI is involved. At the same time, transparency does not require unrestricted source code distribution, particularly for governance-critical systems.

This statement explains **how transparency and accountability are provided** in Open DG AI.

---

## What Transparency Means in Open DG AI

Transparency in Open DG AI is achieved through **observable behavior, documented structure, and verifiable evidence**, rather than public source code access.

Specifically, transparency is provided through:

- Clearly defined data governance models  
- Documented system behavior and decision flows  
- Human-reviewed governance actions  
- Immutable audit records  
- Exportable evidence for review  

---

## Source Code Disclosure

The core Open DG AI platform is distributed as:
- a managed cloud application, and  
- prebuilt container images.

The core application source code is **not publicly released**.

This design choice ensures:
- A single authoritative implementation  
- Consistent governance behavior  
- Clear accountability in regulated environments  
- Protection against fragmented or misleading derivative implementations  

Transparency is instead provided at the **governance, configuration, and evidence layers**, which are the layers relevant to regulatory review.

---

## Open and Inspectable Artifacts

To promote interoperability and understanding, Open DG AI openly publishes:

- Data governance schemas  
- PDPA and GDPR profile definitions (as data)  
- Policy and configuration examples  
- Deployment manifests  
- SDKs and integration libraries  
- Documentation  

These artifacts are released under the **Apache License 2.0** and may be inspected, reused, and integrated by third parties.

---

## AI Accountability

AI capabilities in Open DG AI are designed to **assist, not decide**.

AI features:
- Provide analysis and recommendations  
- Highlight potential governance gaps  
- Summarize evidence and activity  

AI does not:
- Interpret law  
- Make compliance determinations  
- Approve or deny processing  
- Replace human judgment  

All governance decisions require **human review and accountability**.

---

## Auditability and Evidence

The platform maintains structured, time-stamped records of:

- Data assets and classifications  
- Declared purposes and legal bases  
- Consent states  
- Access and processing events  
- Governance decisions and exceptions  

These records can be viewed and exported to support:
- Internal reviews  
- Auditor assessments  
- Regulatory inquiries  

Open DG AI does not certify compliance; it provides **evidence to support assessment**.

---

## Responsibility and Accountability

Open DG AI is a technology provider.

Responsibility for:
- Legal interpretation  
- Policy definition  
- Governance decisions  
- Compliance outcomes  

remains with the deploying organization and its accountable roles.

Use of the platform does not imply regulatory approval or endorsement.

---

## Our Commitment

We are committed to:
- Clear documentation of system behavior  
- Responsible use of AI in governance contexts  
- Continuous improvement of auditability and explainability  
- Engagement with customers, auditors, and regulators in good faith  

Transparency and accountability are **operational principles**, not marketing claims.

---

## Closing Statement

Open DG AI is built on the belief that:

> **Trust in governance systems comes from clarity, evidence, and accountability — not from unchecked automation or ambiguous claims.**

This statement reflects how we design, operate, and evolve the platform.

---

## What is Open DG AI

A **Data Governance platform with full-PDPA compliance operations and AI Governance built in** — compliance-officer-first, multilingual (English + Thai first). It gives DPOs and governance leads one place to run: asset inventory & classification, retention, policies, RoPA, all PDPA data-subject rights (30-day statutory clock), breach notification (72-hour PDPC clock), DPIA, cross-border transfers, processor/DPA registers, AI system registry with risk tiering — with an append-only audit trail enforced at the database level.

**v0.1 target: 2026-10-14.** Distribution: official container images + managed cloud (commercial license above).

## Open artifacts in this repository

| Path | Contents | Status |
|---|---|---|
| `profiles/pdpa/` | Thailand PDPA statutory workflows as versioned, machine-readable transition tables (rights requests §30–§36, breach §37(4)) — the exact definitions the platform executes | Published |
| `schemas/` | Governance data schemas | Coming with v0.1 |
| `policies/` | Policy examples | Coming with v0.1 |
| `deploy/` | Deployment manifests (compose/Helm) | Coming with v0.1 |

Contributions to these artifacts are welcome under Apache-2.0 with DCO sign-off — especially additional jurisdiction profiles and translations.

**Not legal advice.** Open DG AI supports compliance operations; it does not guarantee compliance with PDPA, GDPR, or any other law (see the commercial license §3).
