# Awesome-Manufacturing-Quality-Management

## Top Manufacturing Quality Management (QMS) Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Manufacturing Quality Management, QMS, CAPA, SPC, FMEA, Audits & Compliance*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Manufacturing Quality Management Systems (QMS)**. These tools manage quality processes across manufacturing operations, including document control, nonconformance management, CAPA, audits, supplier quality, inspections, SPC, FMEA, risk management, change control, training, complaints, and regulatory compliance.

**Examples** include ETQ Reliance, MasterControl, QT9 QMS, Qualio, Greenlight Guru, AssurX, Sparta TrackWise, Intellect QMS, ComplianceQuest, and Harrington QMS.

**Open-source emphasis**: This section is heavily expanded with projects for self-hosting, manufacturing quality workflows, SPC, FMEA, CAPA, inspection, traceability, manufacturing ERP/QMS integration, and Git-based quality management. A few projects are broader manufacturing/ERP platforms or specialized quality components rather than complete enterprise QMS replacements.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and clearly distinguish fully open-source projects from open-core and proprietary software.

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Core Open-Source QMS Platforms](#core-open-source-qms-platforms)
* [Manufacturing ERP/MES Platforms with Quality Modules](#manufacturing-erpmes-platforms-with-quality-modules)
* [SPC & Statistical Quality Tools](#spc--statistical-quality-tools)
* [FMEA, Risk & Process Quality](#fmea-risk--process-quality)
* [Inspection, NCR & CAPA](#inspection-ncr--capa)
* [Quality Documentation & Compliance](#quality-documentation--compliance)
* [Additional Manufacturing Quality Projects](#additional-manufacturing-quality-projects)
* [Building an Open-Source Manufacturing QMS](#building-an-open-source-manufacturing-qms)
* [Commercial QMS → Open-Source Equivalents](#commercial-qms--open-source-equivalents)
* [Recommended Open-Source Stacks](#recommended-open-source-stacks)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

* **[ETQ Reliance](https://www.etq.com/)**
  Enterprise QMS platform covering CAPA, document control, audits, change management, supplier quality, nonconformance, training, and quality workflows.

* **[MasterControl](https://www.mastercontrol.com/)**
  Enterprise quality and manufacturing platform focused on quality management, document control, training, CAPA, audits, change control, and regulated industries.

* **[QT9 QMS](https://qt9software.com/qms/)**
  Manufacturing-focused QMS integrated with ERP capabilities, covering quality control, inspections, nonconformance, CAPA, supplier quality, and manufacturing workflows.

* **[Qualio](https://www.qualio.com/)**
  Cloud QMS focused on quality documentation, training, CAPA, audits, risk management, and compliance for regulated organizations.

* **[Greenlight Guru](https://www.greenlight.guru/)**
  Quality management and product development platform particularly focused on medical-device organizations, design controls, document management, CAPA, risk, and quality processes.

* **[AssurX](https://www.assurx.com/)**
  Enterprise quality and compliance management platform supporting CAPA, complaints, audits, document control, change management, training, and regulated workflows.

* **[Sparta TrackWise Digital](https://www.spartasystems.com/)**
  Enterprise quality management platform for regulated manufacturing, covering quality events, CAPA, audits, complaints, supplier quality, training, and document management.

* **[Intellect QMS](https://www.intellectqms.com/)**
  Configurable cloud QMS platform supporting quality processes, CAPA, document control, audits, supplier quality, risk, and compliance workflows.

* **[ComplianceQuest](https://www.compliancequest.com/)**
  Cloud-based quality, safety, risk, and compliance platform covering QMS, CAPA, audits, supplier management, document control, training, and quality events.

* **[Harrington QMS](https://www.harrington-group.com/)**
  Quality management software supporting document control, corrective actions, audits, training, risk, supplier management, and compliance.

### Additional Major Manufacturing QMS Platforms

* **[Veeva Vault QMS](https://www.veeva.com/products/vault-quality/)**
  Cloud quality management platform for regulated industries.

* **[Intelex QMS](https://www.intelex.com/)**
  Quality, environmental, health, safety, and compliance management platform.

* **[Plex Smart Manufacturing Platform](https://www.rockwellautomation.com/)**
  Manufacturing platform with quality, production, traceability, and operational management capabilities.

* **[SAP Quality Management](https://www.sap.com/products/scm/quality-management.html)**
  Enterprise quality management functionality integrated with SAP manufacturing and supply-chain workflows.

* **[Oracle Quality Management](https://www.oracle.com/scm/manufacturing/quality-management/)**
  Quality management capabilities integrated with Oracle manufacturing and supply-chain applications.

* **[Siemens Opcenter Quality](https://www.sw.siemens.com/)**
  Manufacturing execution and quality-management capabilities for industrial production.

* **[Tulip](https://tulip.co/)**
  Frontline operations platform with manufacturing quality, inspection, traceability, and workflow capabilities.

* **[SafetyCulture](https://safetyculture.com/)**
  Inspection, audit, corrective-action, checklist, and operational quality platform.

* **[ETQ](https://www.etq.com/)**
  Enterprise quality management platform emphasizing configurable quality workflows and compliance.

---

## Open-Source GitHub Projects

The open-source manufacturing QMS ecosystem is considerably more fragmented than the commercial QMS market.

Instead of one open-source project reproducing every capability of MasterControl, ETQ Reliance, or TrackWise, the ecosystem is composed of:

```text
Core QMS
   +
Manufacturing ERP / MES
   +
SPC
   +
FMEA / Risk
   +
Inspection
   +
NCR / CAPA
   +
Document Management
   +
Workflow / Approvals
   +
Audit Trail
   +
Analytics
```

### Core Open-Source QMS Platforms

* **[OpenQMS — Open-Industry-System](https://github.com/Open-Industry-System/OpenQMS)**
  Full-stack manufacturing QMS covering FMEA, 8D/CAPA, control plans, SPC, MSA, incoming quality control, supplier quality, SCAR, customer complaints, APQP, PPAP, audits, quality objectives, and multi-plant management. It is specifically oriented toward manufacturing and IATF 16949 workflows.

* **[Open QMS — IridiumSoftware](https://github.com/IridiumSoftware/OpenQMS)**
  GitHub-native open-source QMS generator that composes quality-system scaffolding from products, jurisdictions, standards, and regulatory modules. It includes manufacturing as well as medical-device, aerospace, automotive, pharma, food-safety, and other domains.

* **[openQMS — evolunis](https://github.com/evolunis/openQMS)**
  MIT-licensed open-source ISO 13485 quality-management-system documentation/project that can serve as a foundation for regulated quality-system implementation.

* **[QMS MCP Server](https://github.com/zavora-ai/mcp-qms)**
  Open-source QMS MCP server providing tools around suppliers, batches, QC release, inspections, NCR, CAPA, complaints, and HACCP monitoring for manufacturing and food-and-beverage workflows.

### Additional Strong Open-Source Options

* **[Tessera](https://github.com/jackhale98/Tessera)**
  Git-based engineering and manufacturing quality data platform covering requirements, risks, tests, BOMs, tolerances, manufacturing processes, SPC/control data, work instructions, NCRs, and CAPA.

* **[Carbon](https://github.com/crbnos/carbon)**
  Open-core manufacturing platform combining ERP, MES, and QMS capabilities. Useful as a manufacturing foundation, although it should not be treated as a fully open-source QMS equivalent because some functionality is commercially licensed.

* **[ERPNext](https://github.com/frappe/erpnext)**
  Fully open-source ERP platform containing manufacturing and quality-management functionality, including quality inspections and manufacturing workflows.

* **[Frappe Framework](https://github.com/frappe/frappe)**
  Open-source application framework underlying ERPNext and useful for developing custom manufacturing quality applications.

* **[Odoo Community](https://github.com/odoo/odoo)**
  Open-source ERP foundation with manufacturing capabilities; additional quality functionality can depend on the edition and installed modules.

---

## Manufacturing ERP/MES Platforms with Quality Modules

Many manufacturers do not operate QMS as a completely separate application. Quality is frequently connected directly to:

* Manufacturing orders
* Bills of materials
* Work orders
* Inventory
* Production lots
* Serial numbers
* Supplier receipts
* Shop-floor inspections
* Traceability

### ERPNext

* **[ERPNext](https://github.com/frappe/erpnext)**
  Open-source ERP covering manufacturing, inventory, purchasing, accounting, asset management, and quality management.

Quality-related workflows can be connected directly to manufacturing and inventory data.

```text
ERPNext
├── Manufacturing
├── Inventory
├── Quality Management
├── Quality Inspection
├── Purchasing
├── Suppliers
├── Batch / Serial Tracking
└── Accounting
```

### Carbon

* **[Carbon](https://github.com/crbnos/carbon)**
  Manufacturing-oriented ERP/MES/QMS platform designed around complex assembly, contract manufacturing, high-volume manufacturing, and configure-to-order workflows.

> Carbon is best categorized as **open-core**, rather than being treated as a fully open-source equivalent to a QMS.

### S-PMS

* **[S-PMS](https://github.com/s-pms/SPMS-Server)**
  Open-source smart production management system integrating MES, WMS, ERP, QMS, and IoT functionality for manufacturing environments.

---

## SPC & Statistical Quality Tools

Statistical Process Control is a major component of manufacturing quality management.

```text
Production Measurements
          │
          ▼
       SPC Data
          │
          ▼
 ┌─────────────────┐
 │ Control Charts  │
 └────────┬────────┘
          │
     ┌────┴─────┐
     ▼          ▼
  In Control  Out of Control
     │          │
     │          ▼
     │         NCR
     │          │
     │          ▼
     │         CAPA
     │
     ▼
 Process Capability
 Cp / Cpk / Pp / Ppk
```

* **[Cassini](https://github.com/saturnis-io/cassini)**
  Open-source SPC platform for manufacturing quality control with real-time control charts, capability analysis, gage R&R, FAI management, and audit logging. The project is open-core, with an AGPL-3.0 open-source edition and commercial functionality.

* **[OpenQMS](https://github.com/Open-Industry-System/OpenQMS)**
  Includes SPC with X̄-R, I-MR, P/NP/C/U charts, process capability calculations, and rule-based detection.

* **[Tessera](https://github.com/jackhale98/Tessera)**
  Provides manufacturing process/control concepts including SPC-related data structures and quality workflows.

* **[ERPNext](https://github.com/frappe/erpnext)**
  Provides manufacturing quality-inspection functionality that can be extended with statistical quality workflows.

### Additional SPC Building Blocks

* **[Python](https://github.com/python/cpython)** + statistical libraries for custom quality analytics.
* **[Pandas](https://github.com/pandas-dev/pandas)** for manufacturing measurement datasets.
* **[NumPy](https://github.com/numpy/numpy)** for numerical quality calculations.
* **[SciPy](https://github.com/scipy/scipy)** for statistical analysis.
* **[Matplotlib](https://github.com/matplotlib/matplotlib)** for control charts and quality visualization.
* **[Grafana](https://github.com/grafana/grafana)** for manufacturing quality dashboards.

---

## FMEA, Risk & Process Quality

Failure Mode and Effects Analysis is central to automotive and industrial quality management.

* **[OpenQMS](https://github.com/Open-Industry-System/OpenQMS)**
  Supports AIAG-VDA 7-step PFMEA/DFMEA, RPN/AP calculations, approval workflows, control-plan generation, special characteristics, and traceability.

* **[Tessera](https://github.com/jackhale98/Tessera)**
  Git-managed engineering data model covering requirements, risks, tests, manufacturing processes, controls, and quality events.

* **[Open QMS](https://github.com/IridiumSoftware/OpenQMS)**
  Provides standards-driven quality-system scaffolding and traceability between requirements and QMS artifacts.

### FMEA Ecosystem

```text
Requirements
     │
     ▼
Design FMEA
     │
     ▼
Process FMEA
     │
     ▼
Control Plan
     │
     ▼
Inspection
     │
     ▼
SPC
     │
     ▼
NCR
     │
     ▼
CAPA
     │
     ▼
FMEA Update
```

This closed-loop model is particularly useful for automotive and complex manufacturing QMS implementations.

---

## Inspection, NCR & CAPA

Nonconformance and corrective-action management form the operational core of many manufacturing QMS systems.

* **[OpenQMS](https://github.com/Open-Industry-System/OpenQMS)**
  Supports 8D/CAPA, IQC, SCAR, customer complaints, RMA, supplier quality, and linked quality workflows.

* **[QMS MCP Server](https://github.com/zavora-ai/mcp-qms)**
  Provides manufacturing-oriented workflows for inspections, nonconformances, CAPA, complaints, supplier quality, and QC release.

* **[ERPNext](https://github.com/frappe/erpnext)**
  Provides quality-inspection workflows integrated with manufacturing, stock, purchasing, and production processes.

* **[Tessera](https://github.com/jackhale98/Tessera)**
  Includes NCR and CAPA concepts directly in its manufacturing quality data model.

### NCR → CAPA Workflow

```text
Quality Inspection
       │
       ▼
Nonconformance
       │
       ▼
Containment
       │
       ▼
Root Cause Analysis
       │
       ▼
Corrective Action
       │
       ▼
Effectiveness Verification
       │
       ▼
Closure
       │
       ▼
FMEA / Process Update
```

---

## Quality Documentation & Compliance

A manufacturing QMS must also control:

* Quality manuals

* SOPs

* Work instructions

* Controlled forms

* Records

* Training

* Approvals

* Change history

* Audit evidence

* Regulatory requirements

* Standard clauses

* **[Open QMS](https://github.com/IridiumSoftware/OpenQMS)**
  Generates QMS scaffolding with bidirectional clause-to-artifact traceability and regulatory modules.

* **[OpenQMS](https://github.com/Open-Industry-System/OpenQMS)**
  Provides manufacturing quality documentation and management workflows around ISO/IATF-oriented processes.

* **[ERPNext](https://github.com/frappe/erpnext)**
  Provides document and workflow infrastructure that can be extended for quality records.

* **[Frappe Framework](https://github.com/frappe/frappe)**
  Provides permissions, workflows, records, APIs, notifications, and customizable business applications.

### Git-Based Quality Management

Git can provide an interesting alternative for certain classes of controlled documentation:

```text
QMS Requirement
      │
      ▼
Git Repository
      │
      ▼
Pull Request
      │
      ├── Review
      ├── Approval
      └── Automated Checks
      │
      ▼
Versioned Quality Artifact
      │
      ▼
Audit Trail
```

This is the architectural approach taken by the GitHub-native Open QMS project.

---

## Additional Manufacturing Quality Projects

### Open-Source Manufacturing Platforms

* **[ERPNext](https://github.com/frappe/erpnext)**
  ERP + manufacturing + inventory + quality management.

* **[S-PMS](https://github.com/s-pms/SPMS-Server)**
  ERP + MES + WMS + QMS + IoT manufacturing platform.

* **[Carbon](https://github.com/crbnos/carbon)**
  Open-core ERP/MES/QMS manufacturing platform.

* **[Odoo](https://github.com/odoo/odoo)**
  Open-source ERP and manufacturing foundation.

### Engineering / Quality Data

* **[Tessera](https://github.com/jackhale98/Tessera)**
  Git-based requirements, risks, tests, BOMs, tolerances, manufacturing and quality data.

### Manufacturing Analytics

* **[Grafana](https://github.com/grafana/grafana)**
  Open-source dashboards for SPC, OEE, inspection, defects, and quality KPIs.

* **[InfluxDB](https://github.com/influxdata/influxdb)**
  Time-series database suitable for manufacturing measurements and machine-quality signals.

* **[Apache Kafka](https://github.com/apache/kafka)**
  Event-streaming infrastructure for production, inspection, machine, and quality events.

* **[Apache Superset](https://github.com/apache/superset)**
  Open-source BI platform for quality analytics and management dashboards.

### Industrial / IoT Integration

* **[Node-RED](https://github.com/node-red/node-red)**
  Flow-based industrial integration and automation.

* **[ThingsBoard](https://github.com/thingsboard/thingsboard)**
  IoT platform useful for connecting machines, sensors, telemetry, and quality-monitoring workflows.

* **[Eclipse Kura](https://github.com/eclipse-kura/kura)**
  IoT gateway framework for industrial edge applications.

---

## Manufacturing Quality Data Architecture

```text
                   SHOP FLOOR
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
     Machines       Inspectors      Suppliers
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                 Quality Events
                       │
             ┌─────────┼─────────┐
             ▼         ▼         ▼
           IQC       SPC        FAI
             │         │         │
             └─────────┼─────────┘
                       ▼
                     QMS
                       │
       ┌───────────────┼────────────────┐
       ▼               ▼                ▼
      NCR             CAPA             SCAR
       │               │                │
       └───────────────┼────────────────┘
                       ▼
                Root Cause Analysis
                       │
                       ▼
                 Corrective Action
                       │
                       ▼
                Effectiveness Check
                       │
                       ▼
                  FMEA / Control Plan
```

---

## Building an Open-Source Manufacturing QMS

A practical architecture can combine specialized projects instead of attempting to create every QMS feature from scratch.

```text
                 Manufacturing Application
                          │
                          ▼
                    QMS API Layer
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
       ▼                  ▼                  ▼
     NCR/CAPA            SPC              FMEA
       │                  │                  │
       └──────────────────┼──────────────────┘
                          ▼
                    Quality Database
                          │
       ┌──────────────────┼──────────────────┐
       ▼                  ▼                  ▼
   Documents          Suppliers          Inspections
       │                  │                  │
       └──────────────────┼──────────────────┘
                          ▼
                    Manufacturing ERP
                          │
                          ▼
                  Production / MES
```

---

## Recommended Open-Source Architecture

### Option 1 — Dedicated Manufacturing QMS

```text
OpenQMS
+
PostgreSQL
+
Redis
+
React
+
FastAPI
+
Grafana
```

Suitable when the primary requirement is:

* FMEA
* APQP
* PPAP
* SPC
* MSA
* IQC
* Supplier Quality
* SCAR
* CAPA
* Audits

---

### Option 2 — ERP + Quality

```text
ERPNext
+
Frappe Framework
+
PostgreSQL / MariaDB
+
Grafana
```

Suitable when QMS must be tightly connected to:

* Manufacturing
* Inventory
* Purchasing
* Suppliers
* Batch tracking
* Serial numbers
* Production

---

### Option 3 — Git-Native QMS

```text
Open QMS
+
GitHub / GitLab
+
Pull Requests
+
CI/CD
+
Markdown / YAML
+
Traceability Matrix
```

Suitable for organizations that want quality-system artifacts to be versioned and reviewed like software.

---

### Option 4 — SPC-Centric Manufacturing Quality

```text
Cassini
+
InfluxDB
+
Grafana
+
Node-RED
+
PostgreSQL
```

Suitable for:

* Real-time SPC
* Machine measurements
* Process capability
* Control charts
* Gauge studies
* Manufacturing analytics

---

### Option 5 — Composable QMS

```text
OpenQMS
    +
ERPNext
    +
Tessera
    +
Grafana
    +
Node-RED
    +
PostgreSQL
```

```text
                    ┌─────────────┐
                    │   OpenQMS   │
                    │ Core QMS    │
                    └──────┬──────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
       ERPNext          Tessera          Cassini
      Manufacturing    Engineering          SPC
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                        Grafana
                           │
                           ▼
                    Quality Analytics
```

---

## Commercial QMS → Open-Source Equivalents

| Commercial QMS                | Open-Source Equivalent / Building Blocks                    |
| ----------------------------- | ----------------------------------------------------------- |
| **ETQ Reliance**              | OpenQMS + ERPNext + Grafana + Frappe                        |
| **MasterControl**             | Open QMS + OpenQMS + ERPNext + Git-based document control   |
| **QT9 QMS**                   | ERPNext + OpenQMS + manufacturing extensions                |
| **Qualio**                    | Open QMS + Frappe + Git-based document control              |
| **Greenlight Guru**           | Open QMS + Frappe + Tessera + document/traceability tooling |
| **AssurX**                    | Open QMS + ERPNext + workflow engine                        |
| **Sparta TrackWise Digital**  | OpenQMS + ERPNext + Frappe + Grafana                        |
| **Intellect QMS**             | Frappe + OpenQMS + custom workflow modules                  |
| **ComplianceQuest**           | Open QMS + ERPNext + Open QMS regulatory modules            |
| **Harrington QMS**            | ERPNext + OpenQMS + Frappe workflows                        |
| **Veeva Vault QMS**           | Open QMS + Git-based document control + workflow engine     |
| **Intelex QMS**               | OpenQMS + ERPNext + Grafana + custom EHS integrations       |
| **Plex Quality**              | ERPNext + OpenQMS + manufacturing/IoT stack                 |
| **SAP QM**                    | ERPNext + OpenQMS + manufacturing integrations              |
| **Oracle Quality**            | ERPNext + OpenQMS + custom quality workflows                |
| **Manufacturing QMS**         | OpenQMS + ERPNext + SPC + FMEA                              |
| **SPC Platform**              | Cassini + Grafana + InfluxDB                                |
| **CAPA Platform**             | OpenQMS + QMS MCP Server + workflow engine                  |
| **Supplier Quality Platform** | OpenQMS + ERPNext + supplier workflows                      |
| **Git-Native QMS**            | Open QMS + GitHub/GitLab                                    |

---

## Manufacturing QMS Technology Stack

```text
┌──────────────────────────────────────────────┐
│             QUALITY APPLICATION              │
│                                              │
│ CAPA • NCR • FMEA • SPC • Audits • PPAP     │
└──────────────────────┬───────────────────────┘
                       │
┌──────────────────────▼───────────────────────┐
│                WORKFLOW ENGINE               │
│       Approvals • Escalation • Signatures    │
└──────────────────────┬───────────────────────┘
                       │
┌──────────────────────▼───────────────────────┐
│                 DATA LAYER                   │
│ PostgreSQL • Timeseries • Object Storage     │
└──────────────────────┬───────────────────────┘
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
      ERP             MES            IoT
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                  SHOP FLOOR
```

---

## Quality Management Workflow

```text
Production
   │
   ▼
Inspection
   │
   ├──────────────► PASS ──────────────► Release
   │
   ▼
FAIL
   │
   ▼
Nonconformance
   │
   ▼
Containment
   │
   ▼
Root Cause
   │
   ▼
CAPA
   │
   ▼
Effectiveness Verification
   │
   ├────────► FAIL ──────► Reopen CAPA
   │
   ▼
PASS
   │
   ▼
Close
   │
   ▼
Update FMEA / Control Plan
```

---

## Quality Management Architecture

```text
┌────────────────────────────────────────────────────┐
│                  MANUFACTURING QMS                 │
├────────────────────────────────────────────────────┤
│                                                    │
│  Document Control                                  │
│  ├── SOPs                                          │
│  ├── Work Instructions                             │
│  ├── Forms                                         │
│  └── Records                                       │
│                                                    │
│  Quality Events                                    │
│  ├── NCR                                           │
│  ├── Complaints                                    │
│  ├── Deviations                                   │
│  └── Defects                                      │
│                                                    │
│  Corrective Action                                 │
│  ├── CAPA                                          │
│  ├── 8D                                            │
│  ├── Root Cause                                    │
│  └── Effectiveness                                 │
│                                                    │
│  Manufacturing Quality                             │
│  ├── IQC                                           │
│  ├── IPQC                                          │
│  ├── FAI                                           │
│  ├── OQC                                           │
│  ├── SPC                                           │
│  └── MSA                                           │
│                                                    │
│  Product / Process Quality                         │
│  ├── FMEA                                          │
│  ├── Control Plans                                 │
│  ├── APQP                                          │
│  ├── PPAP                                          │
│  └── Change Control                                │
│                                                    │
│  Supplier Quality                                  │
│  ├── Supplier Audits                               │
│  ├── SCAR                                          │
│  ├── Supplier Scorecards                           │
│  └── Incoming Quality                              │
│                                                    │
└────────────────────────────────────────────────────┘
```

---

## Open-Source Manufacturing QMS Landscape

```text
                         Manufacturing QMS
                                │
       ┌────────────────────────┼────────────────────────┐
       │                        │                        │
       ▼                        ▼                        ▼
     Core QMS                 ERP/MES                  Quality Data
       │                        │                        │
       ├── OpenQMS              ├── ERPNext              ├── Cassini
       ├── Open QMS             ├── Carbon               ├── Grafana
       └── openQMS              ├── S-PMS                └── InfluxDB
                                └── Odoo
       │
       ├─────────────────────────────────────────────┐
       │                                             │
       ▼                                             ▼
    Quality Engineering                         Compliance
       │                                             │
       ├── Tessera                                  ├── Open QMS
       ├── FMEA                                     ├── Git
       ├── APQP                                     ├── GitHub
       ├── PPAP                                     └── CI/CD
       └── SPC
       │
       ▼
  NCR → CAPA → Verification → FMEA / Control Plan
```

---

## Open-Source vs Commercial QMS

| Capability                 |   Commercial QMS |       Open-Source Stack |
| -------------------------- | ---------------: | ----------------------: |
| Document Control           |                ✅ |                       ✅ |
| CAPA                       |                ✅ |                       ✅ |
| NCR                        |                ✅ |                       ✅ |
| Audit Management           |                ✅ |                       ✅ |
| Supplier Quality           |                ✅ |                       ✅ |
| SPC                        |                ✅ |                       ✅ |
| FMEA                       |                ✅ |                       ✅ |
| MSA                        |                ✅ |                      ⚠️ |
| APQP                       |                ✅ |                      ⚠️ |
| PPAP                       |                ✅ |                      ⚠️ |
| Change Control             |                ✅ |                       ✅ |
| Training                   |                ✅ |                      ⚠️ |
| Electronic Signatures      |                ✅ |       Build / integrate |
| Audit Trails               |                ✅ |                       ✅ |
| Manufacturing Integration  |                ✅ |                       ✅ |
| ERP Integration            |                ✅ |                       ✅ |
| MES Integration            |                ✅ |       Build / integrate |
| IoT Integration            |                ✅ |                       ✅ |
| Customization              |           Medium |               Very High |
| Source Code                |                ❌ |                       ✅ |
| Self Hosting               |           Varies |                       ✅ |
| Data Ownership             | Vendor-dependent |            Full control |
| Vendor Lock-in             |           Higher |                   Lower |
| Regulatory Validation      | Vendor-supported | Customer responsibility |
| Time to Deploy             |           Faster |          Usually slower |
| Engineering Effort         |            Lower |                  Higher |
| License Cost               |     Subscription |             Often lower |
| Infrastructure Cost        | Vendor-dependent |                Customer |
| Air-Gapped Deployment      |           Varies |                       ✅ |
| Custom Manufacturing Logic |           Varies |                       ✅ |

---

## Recommended Projects by Use Case

| Use Case                        | Recommended Starting Point                 |
| ------------------------------- | ------------------------------------------ |
| Full manufacturing QMS          | **OpenQMS**                                |
| IATF 16949-oriented QMS         | **OpenQMS**                                |
| Git-native QMS                  | **Open QMS**                               |
| General ERP + Quality           | **ERPNext**                                |
| Manufacturing ERP + QMS         | **ERPNext + OpenQMS**                      |
| SPC                             | **Cassini**                                |
| FMEA / APQP / PPAP              | **OpenQMS**                                |
| NCR / CAPA                      | **OpenQMS + QMS MCP Server**               |
| Engineering quality data        | **Tessera**                                |
| Manufacturing + ERP + MES + QMS | **S-PMS / ERPNext / Carbon**               |
| Quality analytics               | **Grafana + InfluxDB**                     |
| Industrial IoT quality          | **Node-RED + ThingsBoard**                 |
| Git-based quality documentation | **Open QMS + GitHub/GitLab**               |
| Supplier quality                | **OpenQMS + ERPNext**                      |
| Manufacturing inspection        | **OpenQMS + ERPNext**                      |
| Process capability              | **Cassini + Python/SciPy**                 |
| Custom QMS platform             | **Frappe + PostgreSQL + OpenQMS concepts** |

---

## Building an ETQ Reliance / MasterControl Alternative

A modular open-source implementation could look like:

```text
                         QMS PORTAL
                             │
          ┌──────────────────┼──────────────────┐
          │                  │                  │
          ▼                  ▼                  ▼
     Documents            Quality Events       Audits
          │                  │                  │
          │            ┌─────┴─────┐            │
          │            ▼           ▼            │
          │           NCR         CAPA          │
          │            │           │            │
          └────────────┼───────────┼────────────┘
                       ▼           ▼
                    Workflow / Approval
                           │
                           ▼
                      PostgreSQL
                           │
            ┌──────────────┼──────────────┐
            ▼              ▼              ▼
          FMEA            SPC           Supplier
            │              │              │
            └──────────────┼──────────────┘
                           ▼
                     Manufacturing
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
            ERP           MES           IoT
```

### Suggested Components

```text
Core QMS        → OpenQMS
QMS Generator   → Open QMS
ERP             → ERPNext
Engineering     → Tessera
SPC             → Cassini
Workflow        → Frappe / custom workflow
Database        → PostgreSQL
Time Series     → InfluxDB
Dashboards      → Grafana
IoT             → Node-RED / ThingsBoard
Authentication  → Keycloak
Object Storage  → MinIO
Messaging       → Kafka / NATS
```

---

## Building a Manufacturing Quality Data Platform

```text
                   MACHINE DATA
                        │
                        ▼
                 Node-RED / IoT
                        │
                        ▼
                  Time-Series DB
                        │
                        ▼
                      SPC
                        │
             ┌──────────┴──────────┐
             ▼                     ▼
        In Control             Out of Control
             │                     │
             ▼                     ▼
       Process Data              NCR
                                   │
                                   ▼
                                  CAPA
                                   │
                                   ▼
                           Root Cause Analysis
                                   │
                                   ▼
                            Corrective Action
                                   │
                                   ▼
                         Effectiveness Check
                                   │
                                   ▼
                             FMEA Update
```

---

## Open-Source QMS Technology Map

```text
QMS APPLICATION
│
├── Document Control
│   ├── Open QMS
│   ├── OpenQMS
│   └── Frappe
│
├── Quality Events
│   ├── OpenQMS
│   ├── ERPNext
│   └── QMS MCP Server
│
├── CAPA / 8D
│   ├── OpenQMS
│   ├── QMS MCP Server
│   └── Tessera
│
├── FMEA
│   ├── OpenQMS
│   └── Tessera
│
├── SPC
│   ├── Cassini
│   ├── OpenQMS
│   └── Python / SciPy
│
├── Manufacturing
│   ├── ERPNext
│   ├── Carbon
│   └── S-PMS
│
├── Analytics
│   ├── Grafana
│   ├── Apache Superset
│   └── InfluxDB
│
└── Infrastructure
    ├── PostgreSQL
    ├── Redis
    ├── Kafka
    ├── MinIO
    └── Kubernetes
```

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow the existing format).
3. Include: name, official/GitHub link, 1–2 sentence description, and whether it is SaaS, open-source, or open-core.
4. Prefer projects with active development and publicly verifiable repositories.
5. Do not classify proprietary products as open source.
6. Clearly identify projects where only a subset of the functionality is open source.
7. Submit a PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated** list — not exhaustive and not an endorsement.
* A manufacturing QMS can be subject to requirements such as **ISO 9001, IATF 16949, AS9100, ISO 13485, 21 CFR Part 11/Part 820, EU MDR**, and other applicable standards or regulations.
* Open-source software does not automatically constitute a validated or compliant QMS.
* Organizations using open-source QMS software in regulated environments are responsible for appropriate validation, electronic records, electronic signatures, access controls, audit trails, change control, cybersecurity, backup, disaster recovery, and regulatory compliance.
* Open-core projects should not be treated as fully open-source unless the relevant functionality is actually available under an open-source license.
* Always verify the current license, project activity, regulatory coverage, and commercial-use terms before deployment.

---

**Made for manufacturers, quality engineers, supplier-quality teams, process engineers, regulatory teams, auditors, and industrial technologists.**
Let's make manufacturing quality management more open, traceable, data-driven, and accessible.

