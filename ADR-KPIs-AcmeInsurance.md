# ADR [number]: [Title]

## Context

We require all applications in Runtime to be monitored.
In addition to this, we require logs from applications to be reachable easier for troubleshooting.

[Provide context for the decision, including any constraints or requirements that influenced the decision.]

## Decision

KPIs for monitoring:
CPU 
Mem
State(UP/Down)
Sizing
Name of application

KPIs for logs:
At least 3 months retention period
Source
Time
Aggregate logging (posibility to search across logs from multiple applications)

[State the decision that was made, including any options that were considered and rejected.]

## Status

[Indicate the current status of the decision, such as "proposed", "accepted", "rejected", "superseded", or "obsolete".]

## Consequences

[Describe the consequences, both positive and negative, of the decision, including any risks or dependencies.]

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
