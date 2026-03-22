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
A structured report with sections: **Loss Description**, **Coverage Analysis**, **Reserve Recommendation**, and **Next Steps**, each with clear bullet points suitable for a claim file note.
