# Intake Agent V1 Execution Flow

1. Capture user input
2. Generate timestamp (ISO8601)
3. Generate UUID (external shortcut)
4. Generate MD5 hash of raw payload
5. Construct intake_event_v1.json structure
6. Write to /raw/{uuid}.json
7. Do not mutate data

Design Principle:
Intake is immutable. It captures truth.
Normalization handles interpretation.
