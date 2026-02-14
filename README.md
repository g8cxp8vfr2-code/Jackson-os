# Jackson OS

## Intake Agent V1

Status: FROZEN  
Version: 1.0  

### Purpose
Capture user input and convert it into a structured raw JSON event.

### Guarantees
- UUID assigned
- MD5 hash generated
- Raw event written to `/raw/{uuid}.json`
- No mutation of data at intake layer

### Next Layer
Normalizer (in development)
