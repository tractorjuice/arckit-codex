# G-Cloud Lot 3 Service Definition Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:sdd-lot3` generates the Service Definition Document for a G-Cloud Lot 3 cloud support
service. Lot 3 covers cloud consulting, migration, implementation, optimisation, training, support,
and managed services.

---

## Command

```bash
/arckit:sdd-lot3 <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-SDD-v1.0.md
```

---

## When to Use

- The service is consultancy, migration, integration, managed support, optimisation, or training.
- You need to describe delivery approach, roles, outcomes, dependencies, and buyer
  responsibilities.
- You want support service claims to align with pricing and supplier evidence before review.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Supplier profile | Reusable supplier credentials, certifications, and contact details |
| Service design (`SVCD`) | Service proposition, buyer segments, outcomes, and support model |
| Delivery method | Phases, roles, artefacts, dependencies, and acceptance criteria |
| Case studies or references | Evidence for capability and delivery experience |

---

## Output Sections

| Section | Purpose |
|---------|---------|
| Service overview | Buyer-facing scope and outcomes |
| Delivery approach | Phases, roles, responsibilities, dependencies, and artefacts |
| Skills and assurance | Team capability, quality assurance, governance, and reporting |
| Onboarding and exit | Mobilisation, knowledge transfer, handover, and closure |
| Support | Availability, escalation, SLAs, and account management |

---

## Related Commands

- `/arckit:service-design` - Create the service design input.
- `/arckit:pricing` - Generate day-rate, package, or outcome-based pricing.
- `/arckit:gcloud-competitors` - Compare against similar support services.
- `/arckit:review` - Check readiness before submission.
