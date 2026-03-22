---
name: claim-summary
description: Summarize an insurance claim including loss description, applicable coverage, reserve recommendation, and next steps.
triggers: ["summarize this claim", "claim summary", "review this claim"]
---

# Claim Summary

## What this skill does
Produces a structured summary of an insurance claim. It identifies the loss description and circumstances, maps the facts to applicable coverage, recommends a reserve amount, and outlines actionable next steps for the adjuster or examiner.

## How to invoke
/claim-summary [paste or describe the claim details]

## Workflow steps

### Step 1 — Gather claim facts
Extract the key facts: date of loss, claimant, policy number, type of loss, reported circumstances, and any supporting documentation provided.

### Step 2 — Map to coverage
Identify which coverage parts apply (e.g., dwelling, liability, auto physical damage, bodily injury), note any exclusions or conditions that may affect coverage, and flag any coverage questions requiring investigation.

### Step 3 — Reserve and next steps
Recommend an initial reserve based on the exposure described, then list the next steps: contacts to make, documents to obtain, inspections to schedule, and any referrals (SIU, legal, medical management).

## Example outputs

```
CLAIM SUMMARY — CLM-2024-004821
────────────────────────────────────────────────────────
Claim #:      CLM-2024-004821   Date of Loss:  March 18, 2024
Insured:      Riverside Bakery LLC             Policy #: CP-887234-A

LOSS DESCRIPTION
Kitchen exhaust-hood fire caused smoke and heat damage to the commercial
kitchen, walk-in cooler, and ~400 sq ft of retail floor. Fire contained
within two hours; no injuries reported.

COVERAGE ANALYSIS
• Commercial Property – Building ($850K limit / $5K ded.): applies — fire
  is a covered peril; no exclusions triggered.
• Business Income w/ Extra Expense (12-mo. restoration): applies — closure
  expected 4–8 weeks.
• Equipment Breakdown: potential applicability to walk-in cooler compressor;
  investigation pending.
• No arson indicators; SIU referral not required at this time.

RESERVE RECOMMENDATION
  Indemnity (structure + equipment):   $125,000
  Business Income / Extra Expense:      $40,000
  ALAE (adjuster + O&C investigation):   $8,500
  ─────────────────────────────────────────────
  Total Initial Reserve:               $173,500

Reserve subject to revision pending certified rebuild estimate and equipment
breakdown assessment.

NEXT STEPS
1. Assign origin & cause investigator (48-hr deadline).
2. Recorded statement from insured owner (by 3/25/24).
3. Request BI documentation: financials, prior-year tax returns.
4. Issue reservation of rights re: equipment breakdown coverage.
5. Evaluate subrogation potential against exhaust-hood service contractor.
```
