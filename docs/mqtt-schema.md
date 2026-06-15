# MQTT Topic Structure

## Telemetry

Topic:
vehicle/{vehicle_id}/telemetry

Example:
vehicle/TATA_TIAGO_001/telemetry

Payload:

{
  "vehicle_id":"TATA_TIAGO_001",
  "timestamp":"2026-06-14T10:30:05Z",
  "rpm":2500,
  "coolant_temp":95,
  "speed":72
}

## Alerts

Topic:
vehicle/{vehicle_id}/alerts

Payload:

{
  "alert_level":"critical",
  "fault_class":"bearing_wear",
  "message":"Bearing wear detected"
}
