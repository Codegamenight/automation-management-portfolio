# Layered Architecture – Smart Factory / Warehouse Digital Twin

## Overview
The digital twin represents a layered automation architecture from shop-floor control to enterprise systems, enabling visibility, control, and optimization.

## Architecture Layers

### Level 0/1 – Physical & Control (OT)
- Sensors, actuators, drives, motors
- PLCs controlling conveyors, sorters, AS/RS, robots
- Real-time deterministic control

### Level 2 – Supervisory Control
- SCADA / HMI
- Alarm handling and visualization
- Manual overrides and local diagnostics

### Level 3 – Warehouse Control / Execution
- WCS (Warehouse Control System)
- Orchestration of material flow
- Routing, sequencing, exception handling
- Interface between OT and WMS

### Level 4 – Manufacturing / Warehouse Execution
- WMS / MES
- Inventory management
- Order release and wave planning
- Performance reporting

### Level 5 – Enterprise
- ERP
- Order management
- Planning, finance, and reporting

## Digital Twin Representation
- Mirrors each layer’s state and events
- Aggregates KPIs and telemetry
- Enables scenario analysis and resilience planning
