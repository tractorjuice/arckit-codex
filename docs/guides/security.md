# G-Cloud Security Assertions Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:security` generates NCSC Cloud Security Principles assertions and evidence for a G-Cloud
service. It links the service design, SDD, and supplier profile to security controls, evidence,
residual risks, and buyer-facing security statements.

---

## Command

```bash
/arckit:security <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-SECA-v1.0.md
```

---

## When to Use

- After the service design and SDD are drafted.
- Before pricing and review, so security claims are evidence-backed.
- When a buyer will ask for data protection, access control, encryption, monitoring, incident,
  resilience, or supply-chain evidence.
- When ISO, Cyber Essentials, penetration test, or hosting-location evidence must be tied to the
  service.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Supplier profile (`SUPP`) | Shared certifications, data centres, insurance, and contacts |
| Service design (`SVCD`) | Service scope and architecture assumptions |
| Service Definition Document (`SDD`) | Buyer-facing claims to validate |
| Security evidence | Certificates, policies, pen-test summaries, diagrams, and control records |

---

## Review Checklist

- Assertions are mapped to the NCSC Cloud Security Principles.
- Each material security claim has a source or an explicit evidence gap.
- Data location, access control, encryption, backup, incident, and monitoring statements align with
  the SDD.
- Residual risks are visible and can be fed into `/arckit:risk`.
- Sensitive evidence is referenced appropriately rather than pasted into public documents.

---

## Related Commands

- `/arckit:secure` - General secure-by-design assessment.
- `/arckit:dfd` - Data flow and trust-boundary analysis.
- `/arckit:review` - Final G-Cloud readiness check.
