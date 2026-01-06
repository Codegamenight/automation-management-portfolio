# Event Model – Digital Twin

## Purpose
Define the event-driven model that represents system behavior across automation layers.

## Core Event Types
- EquipmentStateChanged (Running, Stopped, Faulted)
- AlarmRaised / AlarmCleared
- ItemInducted
- ItemRouted
- ItemStored
- ItemPicked
- ItemSorted
- ItemShipped
- MaintenanceStarted / MaintenanceCompleted

## Event Attributes
- Timestamp
- Source (PLC, SCADA, WCS, WMS)
- Asset ID / Location
- Severity (if applicable)
- Correlation ID (order, incident)

## Usage
- Real-time monitoring
- Incident detection
- Throughput and bottleneck analysis
- Replay and simulation scenarios
