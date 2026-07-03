# G-Cloud Competitor Benchmark Guide

> **Guide Origin**: Community | **ArcKit Version**: [VERSION]

`/arckit:gcloud-competitors` benchmarks a supplier-side G-Cloud service against comparable Digital
Marketplace rivals. It uses the service design, SDD, pricing, and optional market intelligence to
produce positioning, differentiation, and improvement evidence.

---

## Command

```bash
/arckit:gcloud-competitors <service project or service name>
```

Output:

```text
projects/<NNN>-<service-name>/ARC-<NNN>-GCMP-v1.0.md
```

---

## When to Use

- After service design, SDD, and pricing are drafted.
- Before final review, to test whether features, benefits, and price positioning are credible.
- When a supplier wants to understand marketplace rivals for the same lot or capability.
- When existing `/arckit:tenders` or `/arckit:competitors` artefacts can enrich the analysis.

---

## Inputs

| Input | Purpose |
|-------|---------|
| Service design (`SVCD`) | Proposition, target buyers, features, benefits, and lot |
| SDD (`SDD`) | Marketplace-facing claims and support model |
| Pricing (`PRIC`) | Price tiers, assumptions, discounts, and options |
| Tender or competitor artefacts | Optional award and supplier evidence |

---

## Output Sections

| Section | Purpose |
|---------|---------|
| Rival set | Comparable services and suppliers |
| Feature comparison | Strengths, gaps, and differentiators |
| Price positioning | Where the service sits against public comparators |
| Submission improvements | Specific updates to service design, SDD, pricing, or security |
| Caveats | Limits of public marketplace evidence |

---

## Related Commands

- `/arckit:tenders` - Procurement market intelligence.
- `/arckit:competitors` - Supplier landscape intelligence.
- `/arckit:review` - Check readiness after benchmark-driven updates.
