# Playbook: Product Launch

**Business Change Type:** Product Launch
**BCV Version:** 0.1
**Status:** Draft

---

## When This Playbook Applies

Use this playbook when an organization has launched a new product, platform, capability, or service and needs to verify that the launch is accurately reflected in AI systems and machine-consumed information sources.

---

## The Core Question

Do AI systems consistently recognize the new product as part of the organization's current offering?

---

## BCV Lifecycle: Product Launch

### Step 1 — Define the Business Change

Document the specific change before beginning verification.

- Product name (exact, canonical)
- Launch date
- Primary category or capability
- Key differentiators
- Target buyer or user

**Why this matters:** Verification requires a known intended state. Without a clear definition of what was launched, there is no basis for identifying gaps.

---

### Step 2 — Observe the Current Machine View

Query AI systems and review machine-consumed sources to understand how the organization is currently described.

**Suggested queries:**
- "What products does [Organization] offer?"
- "What is [Organization]'s newest product?"
- "Compare [Organization] to [Competitor] in [Category]"
- "Which companies offer [Capability]?"

**Sources to review:**
- Major AI chat systems (at minimum two)
- Industry directories and databases
- Third-party review platforms
- Structured data on the organization's own domain

**Document what is returned, verbatim where possible.**

---

### Step 3 — Collect Evidence

Gather structured evidence of the gap between intended state and observed state.

For each source reviewed, record:

| Field | Value |
|---|---|
| Source | Name of AI system or directory |
| Query used | Exact query |
| Response summary | What the source returned |
| Product mentioned? | Yes / No / Partially |
| Description accurate? | Yes / No / Partially |
| Date observed | |

---

### Step 4 — Identify Gaps

Compare the observed state to the intended state.

Common gaps for product launches:

- Product not mentioned when querying the organization's offerings
- Product described with incorrect name or category
- Product absent from competitive comparisons
- Launch not reflected in third-party sources
- Structured data on the organization's domain does not include the product

Document each gap specifically. Vague gap descriptions produce vague remediation.

---

### Step 5 — Implement

Address the identified gaps. Implementation is outside BCV's scope — BCV does not prescribe how gaps are closed. However, verification requires that implementation is complete before proceeding.

Common implementation actions for product launches:
- Update structured data to include the new product
- Ensure product pages are accessible to machine consumers
- Update machine-readable indexes (such as llms.txt if used)
- Ensure third-party directories reflect the launch

---

### Step 6 — Verify

Repeat the observation process from Step 2 after implementation is complete.

Verification is confirmed when:
- AI systems consistently describe the product accurately
- The product appears in relevant competitive comparisons
- Third-party sources reflect the launch

**Verification is not confirmed by internal review. It is confirmed by external observation.**

---

## Evidence Template

```
Organization:
Product name:
Launch date:
Verification date:

Pre-implementation observation:
  [Source 1]: [Summary]
  [Source 2]: [Summary]

Gaps identified:
  1. [Gap description]
  2. [Gap description]

Post-implementation observation:
  [Source 1]: [Summary]
  [Source 2]: [Summary]

Verification status: Verified / Not Verified / Partial
Notes:
```

---

## Recurring Verification

Product launches are not one-time events. AI systems update continuously. A product that is verified today may require re-verification if:

- AI model updates change how the organization is described
- Competitors launch similar products that affect comparative descriptions
- The product is renamed, repositioned, or expanded

BCV recommends scheduling verification at reasonable intervals following the initial verification.

---

*BCV Playbook: Product Launch · Version 0.1 · August 2026*
*github.com/CFPhantom/business-change-verification*
