# MDE Advanced Hunting KQL Repository

A mini-project repository of Microsoft Defender for Endpoint Advanced Hunting queries.

## Contents

* `queries/Execution`
* `queries/Persistence`
* `queries/Privilege\_Escalation`
* `queries/Defense\_Evasion`
* `queries/Credential\_Access`
* `queries/Discovery`
* `queries/Lateral\_Movement`
* `queries/Command\_and\_Control`
* `queries/Collection`
* `queries/Exfiltration`
* `queries/Initial\_Access`
* `queries/Impact`
* `queries/Utilities`
* `queries/Playbooks`
* `queries/Sigma\_Equivalents`

## Usage

Open Microsoft Defender XDR > Hunting > Advanced Hunting and paste a query from the `queries` folder.

Before using these for detections:

1. Tune time ranges and thresholds.
2. Add environment-specific allowlists.
3. Validate against known-good administrative behavior.
4. Convert stable hunts into custom detection rules.

## Query Metadata

Each `.kql` file includes:

* Title
* Platform
* Tactic
* Technique
* Severity
* Description
* Notes

## Disclaimer

These are starter hunting queries, not production-ready detections. Expect false positives until tuned.

