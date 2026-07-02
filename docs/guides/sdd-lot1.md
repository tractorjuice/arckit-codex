# G-Cloud Lot 1 Service Definition Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:sdd-lot1` generates the Service Definition Document for a G-Cloud Lot 1 cloud hosting
service. Lot 1 covers IaaS and PaaS capabilities such as compute, storage, networking,
containers, platform services, and hosting environments.

---

## Command

```bash
/arckit:sdd-lot1 <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-SDD-v1.0.md
```

---

## When to Use

- The service is primarily cloud hosting, infrastructure, platform, container, or managed hosting.
- You have already created a service design with `/arckit:service-design`.
- You need a buyer-facing SDD that can be copied into Digital Marketplace fields.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Supplier profile | Company, certifications, contacts, and shared security posture |
| Service design (`SVCD`) | Service scope, target buyers, features, benefits, and lot selection |
| Hosting architecture | Regions, data centres, tenancy, scaling, backup, and resilience |
| Security evidence | Certifications, controls, access model, and audit evidence |

---

## Output Sections

| Section | Purpose |
|---------|---------|
| Service overview | Buyer-facing description and use cases |
| Lot 1 capability | Hosting model, infrastructure, regions, tenancy, and service levels |
| Onboarding and offboarding | Migration, exit, data return, and deletion process |
| Security and compliance | Certifications, data protection, access, monitoring, and audit |
| Support | Support hours, channels, escalation, and service management |

---

## Related Commands

- `/arckit:service-design` - Create the service design input.
- `/arckit:pricing` - Align pricing with hosting tiers.
- `/arckit:security` - Generate NCSC Cloud Security Principles evidence.
- `/arckit:review` - Check the submission pack before CCS upload.
