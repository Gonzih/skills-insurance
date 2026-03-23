---
name: renewal-letter
description: Write a policy renewal letter covering coverage summary, any changes, premium explanation, and renewal instructions.
triggers: ["write a renewal letter", "draft renewal notice", "renewal letter"]
---

# Renewal Letter

## What this skill does
Drafts a professional, client-ready policy renewal letter. It summarizes the renewing coverage, clearly explains any changes from the prior term, breaks down the premium, and provides the insured with simple renewal instructions and key contact information.

## How to invoke
/renewal-letter [provide policy details, any changes, and premium information]

## Workflow steps

### Step 1 — Summarize renewing coverage
Open with a warm introduction and provide a concise summary of the coverage being renewed: policy type, coverage lines, effective dates, and key limits.

### Step 2 — Highlight changes and premium
Clearly call out any changes from the prior term (coverage modifications, new endorsements, exclusions, limit adjustments), then explain the renewal premium and any factors driving an increase or decrease.

### Step 3 — Provide renewal instructions and next steps
Give the insured clear instructions for confirming the renewal, payment options and due dates, who to contact with questions, and any action items required before the renewal binds (e.g., signed applications, updated schedules).

## Example outputs

```
Hartwell Insurance Group
400 Commerce Blvd, Suite 12 | Columbus, OH 43215
(614) 555-0182 | renewals@hartwellins.com

March 20, 2024

Patricia L. Okonkwo
Okonkwo Consulting LLC
7 Birchwood Lane
Dublin, OH 43017

Re: Policy Renewal — Business Owners Policy #BOP-2201-09
Renewal Effective: April 1, 2024 – April 1, 2025

Dear Ms. Okonkwo,

Thank you for your continued trust in Hartwell Insurance Group. We are
pleased to present your renewal for the upcoming policy term.

─── COVERAGE SUMMARY ───────────────────────────────────────────────
  Business Personal Property:       $85,000
  Business Liability:               $1,000,000 per occurrence
                                    $2,000,000 aggregate
  Products & Completed Operations:  $2,000,000 aggregate
  Medical Payments:                 $5,000 per person
  Business Income (loss of income): 12 months
  All-perils deductible:            $1,000

─── CHANGES THIS TERM ───────────────────────────────────────────────
• Business Personal Property limit increased from $72,000 to $85,000
  to reflect equipment purchases you reported in December.
• Cyber Liability endorsement added ($250K limit) — included at no
  additional premium as part of our BOP enhancement program.
• No coverage reductions from the prior term.

─── YOUR RENEWAL PREMIUM ────────────────────────────────────────────
  Prior-term annual premium:        $2,104
  Adjustment (property limit +18%): +  $98
  Statewide rate revision (+3.1%):  +  $65
  Cyber endorsement:                $   0
  ──────────────────────────────────────
  2024–2025 annual premium:         $2,267  ($189/month if paid monthly)

─── NEXT STEPS ──────────────────────────────────────────────────────
1. Review and confirm: reply to this letter or call us by March 28 to
   confirm renewal. Coverage will lapse if we do not hear from you.
2. Payment: invoice enclosed; payment due April 1. Pay online at
   hartwellins.com/pay or by check payable to Hartwell Insurance Group.
3. Questions? Contact your agent, Maria Chen, at (614) 555-0182 ext. 4
   or mchen@hartwellins.com.

We value your business and look forward to another year of protecting
Okonkwo Consulting LLC. Please don't hesitate to reach out with any
questions.

Sincerely,

Maria Chen, CPCU
Account Manager, Hartwell Insurance Group
```

## Live Data Sources

- **NAIC Model Laws Database** — naic.org/documents — model regulations and laws governing policy language, renewal notice requirements, and cancellation rules
- **State DOI Rate Filings** — individual state DOI rate filing portals — approved rates and forms for benchmarking renewal premium changes against filed rates
- **ISO Policy Form Library Patterns** — verisk.com/insurance/brands/iso — standard policy form editions, endorsements, and advisory loss costs used as industry benchmarks
- **ACORD Standards** — acord.org — data standards and form specifications for policy and renewal documentation workflows
