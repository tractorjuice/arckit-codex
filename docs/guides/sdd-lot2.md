# G-Cloud Lot 2 Service Definition Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:sdd-lot2` generates the Service Definition Document for a G-Cloud Lot 2 cloud software
service. Lot 2 covers SaaS and cloud-hosted software products delivered to public-sector buyers.

---

## Command

```bash
/arckit:sdd-lot2 <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-SDD-v1.0.md
```

---

## When to Use

- The service is a SaaS application, workflow platform, data product, portal, or cloud-hosted
  software tool.
- You need a structured SDD for Digital Marketplace fields and internal submission review.
- You want software features, onboarding, support, data protection, and security evidence in one
  traceable document.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Supplier profile | Shared company, compliance, and certification evidence |
| Service design (`SVCD`) | Product scope, target buyers, features, benefits, and support model |
| Product architecture | Hosting model, integrations, APIs, data flows, and user roles |
| Pricing assumptions | Tiers, licences, free trials, and optional extras |

---

## Output Sections

| Section | Purpose |
|---------|---------|
| Service summary | Marketplace-ready description and buyer use cases |
| Software capabilities | Features, benefits, roadmap, integrations, and accessibility |
| Data and security | Data residency, access control, encryption, audit, and backups |
| Implementation | Onboarding, configuration, training, and exit |
| Support | Service levels, support channels, incident handling, and account management |

---

## Related Commands

- `/arckit:service-design` - Create the service design input.
- `/arckit:pricing` - Generate pricing aligned to software tiers.
- `/arckit:security` - Generate security assertions and evidence.
- `/arckit:gcloud-competitors` - Benchmark the software service against marketplace rivals.
