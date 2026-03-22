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
A plain-language brief with sections: **What's Covered**, **What's Excluded**, **Limits & Deductibles**, and **Examples**, written at a level appropriate for a policyholder conversation.
