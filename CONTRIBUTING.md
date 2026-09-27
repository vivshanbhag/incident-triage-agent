# Contributing

Thanks for helping improve Incident Triage Agent. The project is early-stage; small, documented changes are easiest to review.

## Before opening a change

- Describe the operational problem and the behavior you want to change.
- Keep sample events, logs, and screenshots synthetic or sanitized. Never include employer-internal details, credentials, customer data, or production logs.
- Explain new AWS permissions and data flows in the README and security notes.
- Keep default tools read-only. Any proposal to add a mutating action must include explicit human approval, bounded parameters, and a clear opt-in design.
- Prefer deterministic policy checks over model-only safeguards.

## Pull requests

Open a focused pull request with a concise description, deployment impact, security implications, and how you evaluated the change. Do not claim production readiness or improved incident outcomes without reproducible evidence.
