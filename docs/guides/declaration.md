# G-Cloud Supplier Declaration Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:declaration` generates the supplier declaration evidence pack for a UK G-Cloud framework
submission. It uses the supplier profile as the baseline for company details, exclusions,
insurance, modern slavery, tax, and related declarations.

---

## Command

```bash
/arckit:declaration <supplier context>
```

Output:

```text
projects/000-global/supplier/ARC-000-DECL-v1.0.md
```

---

## When to Use

- Before submitting or renewing a G-Cloud supplier declaration.
- After creating or updating `/arckit:supplier-profile`.
- When insurance, exclusions, modern slavery, tax, or legal declarations need structured review.
- Before `/arckit:submission-pack`, because the declaration is a required supplier-wide document.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Supplier profile (`SUPP`) | Company identity, contacts, certifications, and insurance |
| Policy evidence | Modern slavery, equality, sustainability, and security policies |
| Legal declarations | Exclusion grounds, tax compliance, insolvency, and conflicts |
| Framework context | G-Cloud framework number and submission deadline |

---

## Review Checklist

- Registered company details match the supplier profile.
- Insurance levels and policy references are current.
- Mandatory and discretionary exclusion answers have owner sign-off.
- Modern slavery, equality, and tax declarations have supporting evidence.
- Unknown framework-specific fields are left pending rather than invented.

---

## Related Commands

- `/arckit:supplier-profile` - Supplier-wide source evidence.
- `/arckit:review` - Validate the complete submission set.
- `/arckit:submission-pack` - Bundle approved files for upload.
