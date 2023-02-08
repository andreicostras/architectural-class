# ADR [001]: KPIs for Acme Insurance

## Context

We require all applications in Runtime to be monitored.
In addition to this, we require logs from applications to be reachable easier for troubleshooting.

Group:
Wihtout KPIs the project will have no direction or way to measure its success.
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


Group:
KPIs

Key Performance Indicators
1. Availability -> Uptime of APIs, % per month/week/day. (Quality), hours x month an API is up.
2. Resource consumption (vCores consumption) -> $ Budget/Money
3. Physical resources Utilization (CPU, Memory, H Disk, IO Network), -> $/Quality
4. Development Time (Time to Market), Lead Time for Changes
5. Number of Consumers -> Customers/Integrators/3rd Party companies
6. Reusability per Asset/API



[State the decision that was made, including any options that were considered and rejected.]

## Status
Proposed (8 Feb 2023)
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
