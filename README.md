This repository contains the open technical standards that support Business Change Verification.

```
BCV (the discipline)
       ↓
Open Standards (this repository)
       ↓
Implementation Examples
```

The discipline defines what should be verified. BCV is not a brand measurement discipline, it verifies organizational facts declared by the company, and whether those facts are accurately reflected in how AI understands the company. The standards define how to implement the AI Layer that makes verification possible. The examples show what implementation looks like in practice. The repository supports the discipline. It does not define it.

---

# Business Change Verification (BCV)

*Organizations continuously create enterprise value through material business change. BCV defines how those changes can be verified in a AI-mediated world.*

Every organization now has two audiences: humans and machines.

For twenty years, organizations built their websites, communications, and brand materials for the first audience. Machine systems, including AI assistants, search engines, and automated research tools, read those same materials anyway, and reconstruct an understanding of the organization from signals never designed for them.

Business Change Verification (BCV) is the operational discipline that verifies major organizational changes are accurately reflected in how AI understands the company.

BCV applies to **Material Business Events**, changes that materially alter how an organization should be understood: acquisitions, leadership transitions, product launches, strategic partnerships, regulatory approvals, rebranding, and divestitures. It does not apply to ordinary business activity.

The **AI Layer** is the structured, first-party, machine-readable representation through which an organization intentionally communicates authoritative facts to AI systems. It does not replace the other signals machines ingest. It gives the organization an authoritative voice among them where before it had none.

BCV is not the AI Layer. The layer is the input. BCV is the discipline that keeps it true.

Organizations continuously create material business change through:

- Acquisitions
- Product launches
- Leadership transitions
- Strategic partnerships
- Certifications
- Market expansion

Each change creates a Verification Gap: the period between when a change occurs and when AI systems accurately reflect it. BCV defines the process for closing that gap and verifying that it closed.

---

## The Five Questions BCV Always Asks

Regardless of industry or sector, every BCV Assessment asks the same five questions about each Material Business Event:

1. **What changed?** What was the Material Business Event and when did it occur?
2. **What was intended?** What did leadership declare as the intended market understanding?
3. **What does AI understand?** Is that understanding reflected in how AI currently describes the company?
4. **Who owns verifying it?** Is there a named individual responsible for closing the gap?
5. **Is there a process?** Is there an operational workflow that runs after every future Material Business Event?

**Verification Confidence** is achieved when the organization's declared business changes are consistently reflected in AI-assisted research across the standard verification questions.

---

## Who Should Care?

Business Change Verification is intended for organizations that regularly create enterprise value through change, including:

- Enterprise Architecture
- Product Management
- Corporate Development (M&A)
- Investor Relations
- Corporate Communications
- Marketing
- Data & AI Governance

---

## Why BCV Exists

Organizations routinely verify legal, financial, cybersecurity, and regulatory changes.

Very few verify how those same changes are represented across AI systems and machine-consumed information systems.

BCV exists to define that verification process.

---

## BCV Lifecycle

Every Material Business Event follows the same lifecycle.

```
Material Business Event
       ↓
Current Machine View
       ↓
Evidence
       ↓
Gap Identification
       ↓
Implementation
       ↓
Verification Complete
```

1. A material business change occurs.
2. The current machine view is observed.
3. Evidence is collected.
4. Differences between intended and observed representation are identified.
5. Corrective actions are implemented.
6. Verification confirms the change has propagated.

The methodology is intentionally independent of any specific AI model or search engine.

BCV defines **what** should be verified. It intentionally does not prescribe **how** organizations implement that verification.

---

## Example

**Material Business Event:**
Acme Corp acquires ExampleCo.

**Question:**
Do leading AI systems consistently recognize ExampleCo as part of Acme Corp?

**Evidence:**
Collected across multiple AI systems and machine-consumed information sources.

**Outcome:**
Verified / Not Verified

---

## What is a Material Business Event?

A Material Business Event is any organizational event that should alter how external AI systems and machine-consumed information sources understand an enterprise.

Examples include:

- Product launch
- Acquisition
- CEO transition
- Strategic partnership
- Certification
- Market expansion
- Rebrand

---

## Guiding Principles

### Publish observations before opinions.

Evidence should always be distinguishable from interpretation.

---

### Separate verification from optimization.

Verification asks:

> *What currently exists?*

Optimization asks:

> *How could it improve?*

Verification comes first.

---

### Business changes are recurring.

Organizations never stop changing.

Business Change Verification is designed as an operational process, not a one-time audit.

---

## Public Scope

This repository documents the public methodology.

It intentionally does **not** include:

- customer data
- operational history
- proprietary datasets
- detection systems
- recommendation engines
- verification workflows

Those belong to operational platforms built on top of the methodology.

---

## Repository Structure

```
business-change-verification/
  README.md        , This document
  FOUNDATION.md    , Why, principles, scope, and non-goals
  CONTRIBUTING.md  , How to contribute
  LICENSE          , MIT
  playbooks/       , Verification playbooks by material business event type
  research/        , Empirical findings and benchmark data
  examples/        , Worked examples
```

---

## Contributing

Business Change Verification is intended to evolve through practical implementation and observed enterprise behavior.

Issues, discussion, and improvements to the public methodology are welcome.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
