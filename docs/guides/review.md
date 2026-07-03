# G-Cloud Submission Review Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:review` checks a G-Cloud service submission for completeness and internal consistency
before CCS submission. It validates the supplier profile, declaration, service design, SDD,
pricing, and security evidence as a joined submission set.

---

## Command

```bash
/arckit:review <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-GCRV-v1.0.md
```

---

## When to Use

- After supplier-wide and service-specific documents are drafted.
- Before `/arckit:submission-pack`.
- When there are multiple revisions and you need a single readiness view.
- Before copying answers into the Digital Marketplace submission form.

---

## Required Artefacts

| Artefact | Command |
|----------|---------|
| `ARC-000-SUPP` | `/arckit:supplier-profile` |
| `ARC-000-DECL` | `/arckit:declaration` |
| `ARC-<NNN>-SVCD` | `/arckit:service-design` |
| `ARC-<NNN>-SDD` | `/arckit:sdd-lot1`, `/arckit:sdd-lot2`, or `/arckit:sdd-lot3` |
| `ARC-<NNN>-PRIC` | `/arckit:pricing` |
| `ARC-<NNN>-SECA` | `/arckit:security` |

---

## Review Areas

- Document existence and version currency.
- Marketplace mandatory fields and limits.
- Cross-document consistency for service name, lot, support, pricing, and security claims.
- Evidence gaps for certifications, hosting, security, data, and support statements.
- Action plan with owners and commands to rerun.

---

## Related Commands

- `/arckit:gcloud-competitors` - Run benchmark analysis before final review.
- `/arckit:submission-pack` - Bundle approved artefacts after review.
- `/arckit:risk` - Track material submission or delivery risks.
