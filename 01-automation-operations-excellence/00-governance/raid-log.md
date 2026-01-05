RAID Log — Automation Operations Excellence Programme

Purpose
To identify, track, and actively manage Risks, Assumptions, Issues, and Dependencies affecting automation operations reliability and delivery.

| ID  | Risk Description                                              | Impact | Likelihood | Mitigation                                                             | Owner                |
| --- | ------------------------------------------------------------- | ------ | ---------- | ---------------------------------------------------------------------- | -------------------- |
| R1  | Unplanned downtime due to insufficient preventive maintenance | High   | Medium     | Implement asset-criticality-based PM strategy with standard checklists | Automation Manager   |
| R2  | Knowledge dependency on key individuals                       | High   | Medium     | Document procedures and enforce shift handovers and runbooks           | Automation Manager   |
| R3  | Delayed incident response outside core hours                  | High   | Medium     | Define on-call rota and escalation matrix                              | Operations Manager   |
| R4  | Inadequate spare parts availability                           | Medium | Medium     | Classify critical spares and set minimum stock levels                  | Maintenance Lead     |
| R5  | Inconsistent incident root cause analysis                     | Medium | Medium     | Standardize postmortem template and review cadence                     | Reliability Engineer |
| R6  | KPI data not available or unreliable                          | Medium | Medium     | Define clear data sources and validation rules                         | Operations Analyst   |
| R7  | Change implementation causing production disruption           | High   | Low        | Enforce change control and maintenance windows                         | Operations Manager   |
| R8  | Safety incidents during maintenance activities                | High   | Low        | Mandatory lockout/tagout and safety checklists                         | HSE Lead             |
| R9  | Vendor response delays during major failures                  | Medium | Medium     | Define vendor escalation SLAs and contact lists                        | Automation Manager   |
| R10 | Continuous improvement backlog not actioned                   | Medium | Medium     | Monthly review cadence with assigned owners                            | Operations Manager   |

| ID | Assumption                                                       |
| -- | ---------------------------------------------------------------- |
| A1 | Automation assets are maintained by trained internal technicians |
| A2 | Basic CMMS or maintenance tracking system exists                 |
| A3 | Production schedules allow planned maintenance windows           |
| A4 | Incident data can be captured manually if needed                 |
| A5 | Management supports standardization initiatives                  |

| ID | Issue Description                           | Status | Owner              |
| -- | ------------------------------------------- | ------ | ------------------ |
| I1 | No standardized incident escalation process | Open   | Operations Manager |
| I2 | PM tasks vary by shift and technician       | Open   | Maintenance Lead   |
| I3 | KPI definitions not aligned across teams    | Open   | Operations Analyst |

| ID | Dependency                                      | Owner              |
| -- | ----------------------------------------------- | ------------------ |
| D1 | Access to historical incident and downtime data | Operations         |
| D2 | Technician availability for PM execution        | Maintenance        |
| D3 | Spare parts supplier lead times                 | Procurement        |
| D4 | Production approval for maintenance windows     | Production Manager |

