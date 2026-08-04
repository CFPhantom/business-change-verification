[acquisition.md](https://github.com/user-attachments/files/30719708/acquisition.md)
# Playbook: Acquisition

**Material Business Event Type:** Acquisition
**BCV Version:** 0.1
**Status:** Draft

---

## When This Playbook Applies

Use this playbook when an organization has completed an acquisition and needs to verify that the combined entity is accurately reflected in AI systems and machine-consumed information sources.

This playbook applies to acquisitions that have closed. It is not a pre-close diligence tool.

---

## The Core Question

Do AI systems consistently recognize the acquired organization as part of the acquiring organization?

---

## Why Acquisitions Require Specific Attention

Acquisitions create a persistent gap between organizational reality and machine-consumed representation. The acquired organization often has an established identity in AI systems and directories — an identity that predates the acquisition and does not automatically update when the deal closes.

Research Note 001 (in the `/research` folder) found that acquisition gaps persisted an average of 56 months in the organizations studied. No organization had a defined process for verifying or resolving this gap.

---

## BCV Lifecycle: Acquisition

### Step 1 — Define the Material Business Event

Document the specific change before beginning verification.

- Acquiring organization (canonical name, domain)
- Acquired organization (canonical name, domain, prior identity)
- Close date
- Primary rationale (capability, market, technology, talent)
- Combined entity description (how the acquiring organization describes the relationship)

**Why this matters:** Verification requires clarity about what the intended state is. An acquisition that adds a capability requires different verification than one that adds a geography.

---

### Step 2 — Observe the Current Machine View

Query AI systems and review machine-consumed sources to understand how both organizations are currently described — separately and in relation to each other.

**Suggested queries:**
- "What does [Acquiring Organization] do?"
- "What does [Acquired Organization] do?"
- "Who owns [Acquired Organization]?"
- "Is [Acquired Organization] part of [Acquiring Organization]?"
- "What companies has [Acquiring Organization] acquired?"
- "What capabilities does [Acquiring Organization] have in [Acquired Category]?"

**Sources to review:**
- Major AI chat systems (at minimum two)
- Industry directories and databases
- Structured data on both organizations' domains
- Third-party company profiles (Crunchbase, LinkedIn, similar)

**Document what is returned for each query and each source.**

---

### Step 3 — Collect Evidence

For each source reviewed, record:

| Field | Value |
|---|---|
| Source | Name of AI system or directory |
| Query used | Exact query |
| Response summary | What the source returned |
| Relationship recognized? | Yes / No / Partially |
| Acquired org described independently? | Yes / No |
| Date observed | |

---

### Step 4 — Identify Gaps

Common gaps for acquisitions:

- Acquired organization described as independent with no reference to acquiring organization
- Acquiring organization's capabilities do not reflect the acquisition
- Structured data does not declare the organizational relationship
- Third-party directories show the acquired organization with pre-acquisition ownership
- AI systems describe the acquiring organization without mentioning the acquisition

Document each gap specifically, including which sources show the gap and which do not. Gaps are often inconsistent across sources — some sources may reflect the acquisition while others do not.

---

### Step 5 — Implement

Implementation is outside BCV's scope. Common implementation actions for acquisitions:

- Update structured data on the acquiring organization's domain to declare the acquired organization as a subsidiary or related entity
- Update structured data on the acquired organization's domain to reference the parent
- Update third-party directory profiles for both entities
- Update machine-readable indexes to reflect combined capabilities

---

### Step 6 — Verify

Repeat the observation process from Step 2 after implementation is complete.

Verification is confirmed when:
- AI systems consistently describe the acquired organization as part of the acquiring organization
- The acquiring organization's capabilities reflect the acquisition
- Third-party sources reflect the current ownership relationship

**For acquisitions specifically:** verification across multiple AI systems is important because different systems may update at different rates. Partial verification — where some systems reflect the acquisition and others do not — should be documented and monitored until full convergence is achieved.

---

## Evidence Template

```
Acquiring organization:
Acquired organization:
Close date:
Verification date:

Pre-implementation observation:
  [Source 1]: [Summary — does it recognize the relationship?]
  [Source 2]: [Summary — does it recognize the relationship?]

Gaps identified:
  1. [Gap description and source]
  2. [Gap description and source]

Post-implementation observation:
  [Source 1]: [Summary]
  [Source 2]: [Summary]

Verification status: Verified / Not Verified / Partial
Notes:
```

---

## Recurring Verification

Acquisition gaps tend to close slowly. BCV recommends:

- Initial verification at 30 days post-implementation
- Follow-up verification at 90 days
- Annual review thereafter

AI systems may revert to pre-acquisition descriptions if the organizational relationship is not consistently maintained in machine-consumed sources.

---

*BCV Playbook: Acquisition · Version 0.1 · August 2026*
*github.com/CFPhantom/business-change-verification*
