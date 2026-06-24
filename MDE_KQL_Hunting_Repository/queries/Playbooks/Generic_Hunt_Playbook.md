# Threat Hunting Playbook Template

## Hunt Name

## Hypothesis

## ATT&CK Mapping

## Data Sources

## Queries Used

## Triage Steps

1. Review process lineage.
2. Validate user and device context.
3. Check prevalence across the environment.
4. Review network destinations.
5. Collect related files, hashes, and command lines.
6. Determine whether behavior is expected, suspicious, or malicious.

## Escalation Criteria

- Credential access evidence
- Persistence established
- C2 communication
- Lateral movement
- Data staging or exfiltration

## Response Actions

- Isolate endpoint
- Collect investigation package
- Block indicators
- Disable compromised accounts
- Create tuned detection logic
