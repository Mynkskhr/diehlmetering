The Thinkwerke Framework
========================

A unified execution model that turns NIS2, CRA, and ISO 27001 into an operational,
repeatable, and business-aligned capability for Diehl Metering.

**One framework. One execution plan. Continuous evidence across products,
platforms, and countries.**

.. mermaid::

   flowchart TB
       REG[NIS2 • CRA • ISO 27001]
       CTRL[Security and Compliance Controls]
       ENG[CI/CD • Cloud • Product Architecture]
       EVID[Continuous Evidence Generation]
       BIZ[Audits • Customers • Tenders • Executives]

       REG --> CTRL
       CTRL --> ENG
       ENG --> EVID
       EVID --> BIZ

What the Framework Solves
-------------------------

Diehl Metering operates across multiple countries, regulatory regimes, and
product portfolios. Traditional compliance approaches break down because they:

- Treat regulations independently instead of as a system
- Rely on static documents instead of operational evidence
- Create dependency on engineering teams for explanations and audits
- Do not scale across countries, products, or future regulations

The Thinkwerke Framework addresses this by **connecting regulation directly to
execution**, and execution directly to **business outcomes**.

.. mermaid::

   flowchart TD
       EXEC[Board • SVP • Directors]
       DASH[Executive Dashboards]
       EVID[Evidence Library]
       PIPE[Engineering Pipelines]

       PIPE --> EVID
       EVID --> DASH
       DASH --> EXEC

Core Pillars of the Framework
-----------------------------

1. Regulation Translated into Controls
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Instead of interpreting NIS2, CRA, and ISO 27001 separately, Thinkwerke maps them
into a **shared control model**.

This ensures:

- Overlapping requirements are implemented once
- Differences are handled through configuration, not rework
- Future regulations can be added without redesign

Detailed mappings and control rationale are documented in:
:doc:`NIS2, CRA, and ISO 27001 mappings <docs.thinkwerke.com/en/latest/compliance/index>`

2. Controls Embedded into Engineering Reality
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Controls are implemented directly into:

- Secure Software Lifecycle (SSLM)
- CI/CD pipelines
- Cloud and platform architecture
- Vulnerability and incident workflows

This removes the gap between *policy* and *practice*.

Technical execution details are described in:
- :doc:`Secure Software Lifecycle <docs.thinkwerke.com/en/latest/solutions/secure-software-lifecycle>`
- :doc:`Vulnerability Lifecycle <docs.thinkwerke.com/en/latest/solutions/vulnerability-lifecycle>`
- :doc:`Cloud Security Foundations <docs.thinkwerke.com/en/latest/solutions/cloud-security-foundations>`

3. Continuous Evidence by Design
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Evidence is generated automatically as a **by-product of normal delivery**, not
as a manual reporting task.

This includes:

- Build-level security results
- Vulnerability tickets with SLAs and closure proof
- SBOMs and license reports
- Architecture and control traceability

Evidence structures and export models are documented in:
- :doc:`Evidence Library <docs.thinkwerke.com/en/latest/evidence-library/index>`
- :doc:`Control-to-Proof Mapping <docs.thinkwerke.com/en/latest/evidence-library/control-to-proof>`
- :doc:`Exportable Artifacts <docs.thinkwerke.com/en/latest/evidence-library/exportable-artifacts>`

4. Executive-Accessible Governance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The framework is designed so that **executives do not need engineering
translation** to understand status or risk.

This is achieved through:

- Clear ownership models
- Human-readable summaries derived from technical evidence
- Consistent narratives for regulators, customers, and auditors

Governance and executive views are explained in:
:doc:`Executive Visibility <docs.thinkwerke.com/en/latest/executive-visibility>`

Country-Specific Without Fragmentation
--------------------------------------

The Thinkwerke Framework separates:

- **What is common across the EU**
- **What is country-specific under NIS2 transposition**

.. mermaid::

   flowchart TB
       CORE[Unified Thinkwerke Framework]
       DE[Germany NIS2UmsuCG]
       FR[France NIS2]
       IT[Italy NIS2]
       ES[Spain NIS2]

       CORE --> DE
       CORE --> FR
       CORE --> IT
       CORE --> ES


This allows Diehl Metering to:

- Maintain one core execution model
- Layer country-specific requirements on top
- Avoid duplication and divergence

The country-specific execution model is detailed in:
:doc:`Country-Specific NIS2 <country-specific-nis2>`

Designed for Growth, Not Constraint
-----------------------------------

A key design principle of the Thinkwerke Framework is **no architectural lock-in**.

Compliance controls:

- Do not mandate specific tools or vendors
- Do not force re-architecture
- Do not slow delivery pipelines

Instead, they adapt to existing and future platforms.

Architecture protection principles are explained in:
:doc:`Architecture & Growth Protection <architecture-growth-protection>`

Why This Matters Strategically
------------------------------

The Thinkwerke Framework allows Diehl Metering to:

- Meet German NIS2 obligations today
- Scale efficiently as other EU countries enforce NIS2
- Prepare proactively for CRA enforcement
- Reuse the same evidence across audits, customers, and tenders
- Provide executives with continuous visibility and control

This transforms compliance from a **cost and risk factor** into a **strategic,
defensible capability**.

Key Takeaway
------------

The Thinkwerke Framework is not a compliance project.

It is a **business operating model** that aligns regulation, engineering,
documentation, and executive oversight into one coherent system — built to
withstand regulatory scrutiny without slowing growth.
