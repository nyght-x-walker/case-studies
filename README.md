# Case studies

Architecture, security properties, and evidence for four systems I have built. The source for these projects is private; these write-ups are the public record. No tenant data, secrets, or private source are included.

| Project | What it proves | Status |
|---|---|---|
| [Axiom](axiom.md) | Zero-trust exam routing with an audit trail an independent system can verify | Private beta · hardening |
| [Oversight](oversight.md) | A SOC/SIEM that checks Axiom's audit chain instead of trusting it | Private beta · v1.0 |
| [COMPASS-RT](compass-rt.md) | AI red-teaming with replayable evidence, regression suites, and CI gates | Private beta · v0.2 |
| [Auf Deutsch](auf-deutsch.md) | A live AI language product with SRS, payments, analytics, and GDPR tools | Live beta |

## How to read these

Each case study follows the same shape:

1. The problem and the constraint that shaped it.
2. The architecture and the trust boundaries.
3. The security or product properties that matter.
4. The evidence I can show publicly.
5. What is deliberately not public.
6. What I would test or build next.

The source is private for a reason: Axiom handles exam material and signing keys, Oversight handles tenant telemetry, and COMPASS-RT contains attack corpora and target configurations. The public artifact is the architecture and the evidence, not the code.

## Related

- [compass-sarif](https://github.com/nyght-x-walker/compass-sarif) — JSON-to-SARIF exporter for AI red-team findings
- [Portfolio](https://augustine-portfolio-two.vercel.app/2d)
- [GitHub profile](https://github.com/nyght-x-walker)

## Contact

[Portfolio](https://augustine-portfolio-two.vercel.app/2d) · [Email](mailto:s-01141@student.german-uds.de) · [Public code](https://github.com/nyght-x-walker?tab=repositories)
