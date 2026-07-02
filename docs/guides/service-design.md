# G-Cloud Service Design Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:service-design` creates a per-service design document for a UK G-Cloud Digital Marketplace
offering. In the G-Cloud supplier overlay, each service is its own ArcKit project under
`projects/<NNN>-<service-name>/`.

---

## Command

```bash
/arckit:service-design <service name, lot, and context>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-SVCD-v1.0.md
```

---

## When to Use

- To create a new cloud hosting, cloud software, or cloud support service listing.
- To capture service name, description, lot, buyer segments, features, benefits, onboarding, and
  support model before drafting the SDD.
- To ground pricing, security assertions, and competitor review in a single service definition.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Service name | Creates or locates the service project |
| G-Cloud lot | Selects Lot 1, Lot 2, or Lot 3 guidance |
| Supplier profile | Reuses company, certification, and contact evidence |
| Service URL or existing listing | Supports citation-backed service facts |

---

## Workflow

1. Run `/arckit:supplier-profile` first when supplier-wide evidence is not yet captured.
2. Run `/arckit:service-design` for the service name and target lot.
3. Review the generated `SVCD` document for marketplace limits and claim accuracy.
4. Generate the relevant SDD with `/arckit:sdd-lot1`, `/arckit:sdd-lot2`, or
   `/arckit:sdd-lot3`.
5. Generate pricing and security evidence, then review the submission.

---

## Review Checklist

- The service name and short description fit Digital Marketplace limits.
- Features and benefits are buyer-focused and evidence-backed.
- The selected lot matches the service model.
- Support, onboarding, offboarding, data, security, and pricing assumptions are explicit.
- The service design is internally consistent with the supplier profile.

---

## Related Commands

- `/arckit:sdd-lot1` - Draft a Lot 1 Service Definition Document.
- `/arckit:sdd-lot2` - Draft a Lot 2 Service Definition Document.
- `/arckit:sdd-lot3` - Draft a Lot 3 Service Definition Document.
- `/arckit:pricing` - Generate the pricing document.
