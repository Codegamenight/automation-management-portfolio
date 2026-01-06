# Failure Scenarios – Smart Factory Digital Twin

## Purpose
Identify realistic failure modes in an automated warehouse and define their operational impact.

## Scenario 1: Conveyor Line Failure
- Description: Motor or drive failure on a main conveyor
- Impact: Upstream backlog, downstream starvation
- Detection: EquipmentStateChanged event + alarms
- Immediate Action: Isolate section, reroute if possible

## Scenario 2: Sorter Jam
- Description: Mechanical jam on high-speed sorter
- Impact: Order fulfillment delays
- Detection: AlarmRaised + throughput drop
- Immediate Action: Stop induction, clear jam, restart sequence

## Scenario 3: WCS Communication Loss
- Description: Loss of communication between WCS and PLC
- Impact: Automation halts or runs in degraded mode
- Detection: Heartbeat timeout
- Immediate Action: Fail-safe stop or local control mode

## Scenario 4: SCADA Server Failure
- Description: Loss of supervisory visualization
- Impact: Reduced visibility, manual intervention risk
- Detection: System health monitoring
- Immediate Action: Switch to redundant SCADA instance

## Scenario 5: Power Outage
- Description: Facility power loss
- Impact: Full automation stop
- Detection: Power monitoring events
- Immediate Action: Controlled shutdown and recovery sequence
