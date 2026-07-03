# G-Cloud Pricing Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:pricing` generates the pricing document for a G-Cloud service. It aligns prices to the
service design, SDD, supplier evidence, and any market intelligence from tender or competitor
artefacts.

---

## Command

```bash
/arckit:pricing <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-PRIC-v1.0.md
```

---

## When to Use

- After `/arckit:service-design` and the relevant SDD command.
- Before submission review, so pricing can be checked against service features and support model.
- When tiers, units, day rates, discounts, trials, or education pricing need to be explicit.
- When tender or competitor evidence should inform the pricing rationale.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Service design (`SVCD`) | Service scope, target buyers, features, and benefits |
| Service Definition Document (`SDD`) | Marketplace-facing service detail |
| Supplier profile (`SUPP`) | Currency, contact, insurance, and shared supplier context |
| Tender or competitor artefacts | Optional benchmark evidence for price positioning |

---

## Output Sections

| Section | Purpose |
|---------|---------|
| Pricing summary | Buyer-facing pricing model and headline tiers |
| Units and assumptions | Licence, user, day-rate, usage, or package basis |
| Included and excluded items | Clear boundary for each tier |
| Discounts and trials | Education pricing, free trials, minimum terms, and extras |
| Benchmark rationale | Evidence from market intelligence where available |

---

## Related Commands

- `/arckit:tenders` - Procurement market benchmarks.
- `/arckit:competitors` - Competitor award and positioning evidence.
- `/arckit:gcloud-competitors` - Marketplace service comparison.
- `/arckit:review` - Submission completeness and consistency check.
