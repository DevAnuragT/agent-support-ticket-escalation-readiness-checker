# Support Ticket Escalation Readiness Checker

Check escalated support cases for impact, reproduction evidence, and owning team.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-support-ticket-escalation-readiness-checker.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
