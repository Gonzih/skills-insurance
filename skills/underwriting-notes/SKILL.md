---
name: underwriting-notes
description: Draft underwriting notes for a risk including risk profile, favorable factors, concerns, proposed terms, and conditions.
triggers: ["draft underwriting notes", "underwriting memo", "write up this risk"]
---

# Underwriting Notes

## What this skill does
Produces professional underwriting notes for a submission or renewal. It synthesizes the risk profile into a structured memo covering favorable characteristics, material concerns, proposed terms, and any conditions or exclusions recommended before binding.

## How to invoke
/underwriting-notes [describe the risk or paste submission details]

## Workflow steps

### Step 1 — Summarize the risk profile
Capture the key risk characteristics: insured name, operation or property type, location, size (revenue, payroll, TIV, etc.), years in business, and prior loss history.

### Step 2 — Identify favorable factors and concerns
List the attributes that support writing the risk (e.g., experienced management, strong loss control, favorable loss history) alongside concerns that require attention or mitigation (e.g., CAT exposure, prior losses, hazardous operations).

### Step 3 — Propose terms and conditions
Recommend coverage terms, pricing direction, sublimits, deductibles, and any conditions, warranties, or exclusions needed to make the risk acceptable. Note any referrals or approvals required.

## Example outputs

```
UNDERWRITING NOTES
────────────────────────────────────────────────────────────
Account:      Maple Street Auto Repair LLC
Line:         Commercial General Liability + Commercial Auto
Submitted:    2024-03-20     Underwriter: J. Torres

RISK PROFILE
• Auto repair shop, 3 locations in suburban Ohio
• Annual revenue: $2.1M | Payroll: $480K | 14 employees
• 22 years in business under current ownership
• Owns building at main location; leases two secondary shops
• Fleet: 4 courtesy vehicles, 1 tow truck

FAVORABLE FACTORS
✓ 22-year account with no prior carrier losses reported (verified via CLUE)
✓ Owner holds ASE Master Technician certification; all techs ASE-certified
✓ Fire suppression and security systems at all locations
✓ Separate secure lot with CCTV for customer vehicle storage
✓ Revenue growth (+12% YoY) suggests stable, well-run operation

CONCERNS
⚠ Garagekeepers exposure: avg. 45 vehicles on premises nightly across 3
  locations — current sublimit ($350K) may be inadequate; recommend $500K.
⚠ One at-fault auto accident (2022, $18K) involving courtesy vehicle;
  driver has since completed defensive driving course.
⚠ Secondary locations are leased — confirm tenant's liability and any
  landlord requirements in lease agreements.
⚠ No pollution/environmental coverage in current program; oil/solvent
  storage creates potential ground contamination exposure.

PROPOSED TERMS & CONDITIONS
  CGL:       $1M/$2M occurrence/aggregate; $500K products-completed ops
  Garage Liability: $1M CSL
  Garagekeepers Legal Liability: $500K (increase from $350K)
  Commercial Auto: $1M CSL; scheduled fleet; MVR required annually
  Pollution:  recommend environmental impairment liability endorsement
  Premium direction: +8% from expiring (loss development + exposure growth)
  Conditions: signed garage operations warranty; annual MVR pulls

RECOMMENDATION
Acceptable risk — write subject to pollution endorsement and garagekeepers
limit increase. Bind at quoted terms pending signed application.
```

## Live Data Sources

- **OSHA Incident Rate Data by SIC Code** — bls.gov/iif — injury and illness rates by industry classification for benchmarking workers' compensation and liability risk
- **ISO Commercial Lines Rating Bureau Patterns** — verisk.com/insurance/brands/iso — advisory loss costs, rating algorithms, and classification systems for commercial lines underwriting
- **SOA Actuarial Tables** — soa.org — Society of Actuaries public mortality, morbidity, and loss tables for pricing and reserve adequacy analysis
