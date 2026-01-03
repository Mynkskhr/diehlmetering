Country-Specific NIS2 Without Fragmentation
===========================================

How Diehl Metering can meet national NIS2 requirements across Europe without
duplicating effort, fragmenting execution, or slowing delivery.

**Local compliance execution built on a single, shared European framework.**

.. mermaid::

   flowchart TD
       A[EU NIS2 Directive] --> B[Unified NIS2 Control Framework]

       B --> C[Germany NIS2UmsuCG]
       B --> D[France Transposition]
       B --> E[Netherlands Transposition]
       B --> F[Other EU States]

       C --> G[Country Specific Evidence]
       D --> G
       E --> G
       F --> G

       G --> H[Single Evidence Library]
       H --> I[Audits]
       H --> J[Tenders]
       H --> K[Customers]
       H --> L[Executive Oversight]


“We start with one unified NIS2 control framework, overlay each country’s legal transposition, generate country-specific evidence automatically, and reuse that evidence across audits, tenders, customers, and executive reporting.”

The Core Challenge
------------------

NIS2 is an EU directive, but **it is enforced through national law**.

For Diehl Metering, this creates a structural challenge:

- Multiple EU countries
- Different NIS2 transpositions
- Different supervisory authorities
- Different reporting expectations
- Different enforcement maturity

Yet the business must remain:

- Consistent
- Predictable
- Scalable
- Defensible

Treating each country independently leads to duplication, cost, and internal
misalignment. Treating NIS2 as a single checkbox leads to hidden compliance gaps.

Neither approach is acceptable at scale.

How Thinkwerke Solves This
--------------------------

Thinkwerke separates **what must be common** from **what must be local**.

This allows Diehl Metering to operate one execution model, while still complying
with national requirements.

REGULATION --> CONTROLS --> ENGINEERING --> EVIDENCE

**Flow explanation**

- Regulations: NIS2, CRA, ISO 27001
- Controls: Risk management and security controls
- Engineering: CI/CD, Cloud, Product architecture
- Evidence: Audits, sales, tenders, executive reporting


What Is Common Across All Countries
----------------------------------

The following elements are implemented **once** and reused everywhere:

- Secure Software Lifecycle (SSLM)
- Vulnerability management and remediation workflows
- SBOM generation and OSS license governance
- Cloud and platform security controls
- Evidence generation and retention
- Executive and audit reporting structures

These components are documented in detail at:
- `Secure Software Lifecycle <https://docs.thinkwerke.com/en/latest/solutions/secure-software-lifecycle/>`_
- `Vulnerability Lifecycle <https://docs.thinkwerke.com/en/latest/solutions/vulnerability-lifecycle/>`_
- `Evidence Library <https://docs.thinkwerke.com/en/latest/evidence-library/>`_

What Varies by Country
----------------------

On top of the shared framework, Thinkwerke configures **country-specific layers**
for:

- Registration obligations
- Supervisory authority interfaces
- Incident reporting timelines and formats
- Sector-specific interpretations
- Enforcement thresholds and penalties

These differences are handled through configuration and documentation — not
through re-engineering.

This ensures:

- No duplication of pipelines or controls
- No divergent tooling
- No conflicting narratives between countries

Germany as the Reference Model
------------------------------

.. mermaid::

   flowchart TD
       A[NIS2 EU]
       B[Germany Law]
       C[BSI Oversight]
       D[Registration Portal]
       E[Evidence System]

       A --> B
       B --> C
       C --> D
       D --> E


Germany’s NIS2 implementation (NIS2UmsuCG) is used as the **reference baseline**,
because it is:

- Fully enacted
- Strictly enforced
- Explicit about management accountability
- Backed by a mature supervisory authority (BSI)

Once proven in Germany, the same execution model can be:

- Extended to other EU countries
- Adapted to local legal nuances
- Reused without architectural change

Germany therefore becomes the **anchor**, not a one-off exception.

Operational Impact for Diehl Metering
-------------------------------------

This model allows Diehl Metering to:

- Respond confidently to regulators in different countries
- Maintain a single internal execution narrative
- Avoid country-specific compliance silos
- Scale assurance without increasing headcount
- Provide executives with consistent visibility across regions

From an executive perspective, this means:

- One strategy
- One execution framework
- Country-level assurance without fragmentation

Key Takeaway
------------

NIS2 does not require Diehl Metering to fragment its organisation.

With the Thinkwerke Framework:

- Compliance is implemented once
- Country differences are absorbed cleanly
- Evidence remains consistent and reusable
- Growth, delivery, and sales remain unblocked

This is how multi-country NIS2 compliance becomes **manageable, predictable,
and defensible**.
