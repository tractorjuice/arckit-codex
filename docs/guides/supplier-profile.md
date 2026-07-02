# G-Cloud Supplier Profile Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:supplier-profile` creates or updates the supplier-wide profile used by the UK G-Cloud
supplier overlay. The profile records company details, contacts, certifications, insurance,
security posture, data-centre locations, accreditations, and reusable evidence for each service
submission.

---

## Command

```bash
/arckit:supplier-profile <supplier name or website URL>
```

Output:

```text
projects/000-global/supplier/ARC-000-SUPP-v1.0.md
```

---

## When to Use

- Before creating the first G-Cloud service design.
- When company details, certifications, contacts, insurance, or accreditations change.
- Before submission review, so supplier-wide answers are consistent across all services.
- When a supplier website or Companies House evidence should be captured with citations.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Supplier name | Identifies the organisation and trading name |
| Website URL | Supports web research and citation-backed profile fields |
| Company registration details | Confirms legal identity and supplier status |
| Certifications and insurance | Feeds service design, SDD, security, and declaration documents |

---

## Workflow

1. Run `/arckit:supplier-profile`.
2. Review any existing `ARC-000-SUPP` file before updating it.
3. Provide or confirm company, contact, certification, insurance, and security details.
4. Use the profile as shared input to `/arckit:service-design`, `/arckit:declaration`,
   `/arckit:pricing`, `/arckit:security`, and `/arckit:review`.

---

## Review Checklist

- Registered company name, registration number, address, and contact details are correct.
- Certifications include certificate numbers, expiry dates, and certification bodies.
- Insurance figures match the evidence that will be used for the supplier declaration.
- Data-centre and hosting claims align with the services being submitted.
- Every sourced fact has a citation where web or document evidence was used.

---

## Related Commands

- `/arckit:service-design` - Create a per-service G-Cloud offering.
- `/arckit:declaration` - Generate the supplier declaration.
- `/arckit:submission-pack` - Bundle approved documents for submission.
