---
name: coverage-explainer
description: Explain a policy's coverage in plain language including what's covered, what's excluded, limits, deductibles, and examples.
triggers: ["explain this coverage", "what does this policy cover", "coverage explainer"]
---

# Coverage Explainer

## What this skill does
Translates dense policy language into plain English for agents, brokers, or insureds. It summarizes what is covered and what is excluded, highlights key limits and deductibles, and provides real-world examples to make the coverage tangible and easy to understand.

## How to invoke
/coverage-explainer [paste policy language or describe the coverage section]

## Workflow steps

### Step 1 — Parse the coverage grant
Identify the insuring agreement: what event or peril triggers coverage, who is covered, and what property or liability is protected.

### Step 2 — Summarize exclusions and conditions
List the major exclusions clearly, note any conditions the insured must satisfy (e.g., prompt notice, cooperation), and flag endorsements that modify the base coverage.

### Step 3 — Illustrate with examples
Provide two or three concrete examples showing when a claim would be covered, when it would be excluded, and how the deductible and limits would apply in each scenario.

## Example outputs

```
COVERAGE EXPLAINER — Homeowners Policy HO-3 (Special Form)
────────────────────────────────────────────────────────────

WHAT'S COVERED
Your home (dwelling) and attached structures are insured against all direct
physical losses EXCEPT those specifically excluded. Personal property inside
your home is covered against 16 named perils including fire, theft, and
water damage from burst pipes. Liability coverage protects you if someone
is injured on your property and sues you.

WHAT'S EXCLUDED
• Flood — rising water from outside your home is never covered here; you
  need a separate NFIP or private flood policy.
• Earthquake — excluded; separate earthquake endorsement available.
• Normal wear and tear / maintenance issues (e.g., a slow roof leak over
  years of neglect).
• Mold resulting from an unaddressed maintenance problem.
• Business property and liability if you run a business from home (ask
  about a home-business endorsement).

LIMITS & DEDUCTIBLES
  Dwelling (Coverage A):           $420,000
  Other Structures (Coverage B):    $42,000  (10% of A)
  Personal Property (Coverage C):  $210,000  (50% of A)
  Loss of Use (Coverage D):         $84,000  (20% of A)
  Personal Liability (Coverage E): $300,000
  Medical Payments (Coverage F):     $5,000 per person
  All-perils deductible:             $1,000
  Hurricane/Wind deductible:         $4,200  (1% of Coverage A)

EXAMPLES
1. Kitchen fire damages cabinets and appliances. ✅ Covered under Coverage A
   and C. You pay $1,000 deductible; insurer pays up to the applicable limit.

2. Hurricane blows off half your roof. ✅ Covered, but the 1% wind deductible
   ($4,200) applies — not the standard $1,000 deductible.

3. Basement floods after heavy rain overflows the street. ❌ Not covered —
   this is flood damage. Your NFIP policy would respond here.

4. Pipe bursts and water damages hardwood floors. ✅ Covered (sudden/accidental
   discharge); however, if the pipe was corroded and you ignored it for months,
   the insurer may deny on a maintenance-neglect basis.
```
