[fictional-product-launch.md](https://github.com/user-attachments/files/30719678/fictional-product-launch.md)
# Example: Product Launch Verification

**Type:** Fictional worked example
**Playbook:** Product Launch
**BCV Version:** 0.1

*This example uses fictional organizations and data. It is intended to illustrate the BCV lifecycle, not to describe any real organization.*

---

## The Material Business Event

**Organization:** Meridian Systems
**Product:** Meridian Vault — a new enterprise data security platform
**Launch date:** March 15, 2026
**Canonical description:** Meridian Vault is an enterprise data security platform that provides real-time encryption, access control, and audit logging for organizations managing sensitive data across hybrid cloud environments.

---

## Step 1 — Define the Material Business Event

| Field | Value |
|---|---|
| Product name | Meridian Vault |
| Launch date | March 15, 2026 |
| Category | Enterprise data security |
| Primary capability | Real-time encryption, access control, audit logging |
| Target buyer | Enterprise IT and security teams managing hybrid cloud environments |

---

## Step 2 — Observe the Current Machine View

*Observation date: April 10, 2026 — 26 days post-launch.*

**Query 1:** "What products does Meridian Systems offer?"

| Source | Response |
|---|---|
| AI System A | Listed Meridian Analytics, Meridian Connect, and Meridian Core. Meridian Vault not mentioned. |
| AI System B | Described Meridian Systems as a "data analytics and integration platform provider." No security products mentioned. |
| Industry directory | Product list current as of January 2026. Meridian Vault not listed. |

**Query 2:** "What enterprise data security platforms are available?"

| Source | Response |
|---|---|
| AI System A | Listed six vendors. Meridian Systems not included. |
| AI System B | Listed four vendors. Meridian Systems not included. |

**Query 3:** "What is Meridian Vault?"

| Source | Response |
|---|---|
| AI System A | No results found for Meridian Vault. |
| AI System B | Returned results for an unrelated product with a similar name. |

---

## Step 3 — Evidence Summary

**Intended state:** AI systems describe Meridian Systems as offering Meridian Vault as an enterprise data security platform.

**Observed state:** AI systems do not recognize Meridian Vault. Meridian Systems is described using pre-launch product descriptions. The product does not appear in competitive comparisons for enterprise data security.

---

## Step 4 — Gaps Identified

| Gap | Sources showing gap |
|---|---|
| Meridian Vault not included in product listings | AI System A, AI System B, Industry directory |
| Meridian Systems absent from enterprise data security comparisons | AI System A, AI System B |
| Meridian Vault not recognized as a Meridian Systems product | AI System A, AI System B |

---

## Step 5 — Implementation

*(Implementation details are outside BCV scope. The following describes what Meridian Systems did, for completeness of the example.)*

Meridian Systems updated their structured data to include Meridian Vault as a Product entity. They updated their machine-readable index to include Meridian Vault documentation pages. They submitted updated information to the industry directory.

Implementation completed: April 18, 2026.

---

## Step 6 — Verify

*Verification date: May 5, 2026 — 17 days post-implementation.*

**Query 1:** "What products does Meridian Systems offer?"

| Source | Response |
|---|---|
| AI System A | Listed Meridian Analytics, Meridian Connect, Meridian Core, and Meridian Vault. Described Meridian Vault as an enterprise data security platform. |
| AI System B | Listed Meridian Vault among current products. Description consistent with canonical description. |
| Industry directory | Meridian Vault listed with correct category and description. |

**Query 2:** "What enterprise data security platforms are available?"

| Source | Response |
|---|---|
| AI System A | Meridian Systems included. Meridian Vault described accurately. |
| AI System B | Meridian Systems not yet included. |

**Query 3:** "What is Meridian Vault?"

| Source | Response |
|---|---|
| AI System A | Correctly described as Meridian Systems' enterprise data security platform. |
| AI System B | Correctly described. |

---

## Verification Outcome

**Status: Partial**

Meridian Vault is now recognized by AI systems and correctly described in two of the three sources reviewed. Meridian Systems does not yet appear in enterprise data security comparisons in AI System B.

**Next step:** Re-verify AI System B representation in 30 days. The gap is documented and monitored. Verification is not declared complete until the full observation is consistent across all sources.

---

## Observations from This Example

**Time to gap:** The gap between launch date (March 15) and observation date (April 10) was 26 days. Meridian Vault had been available for nearly a month before anyone verified how AI systems described it.

**Partial verification is common.** Different AI systems update at different rates. Full convergence may take weeks or months. BCV recommends documenting partial verification and scheduling follow-up rather than treating partial as complete.

**The gap had commercial consequence.** During the 26 days between launch and observation, any enterprise buyer using AI to research data security platforms would not have found Meridian Vault. Any buyer researching Meridian Systems would not have seen Meridian Vault among their products.

---

*BCV Example: Product Launch Verification · Version 0.1 · August 2026*
*github.com/CFPhantom/business-change-verification*
