# Security policy

This repository is an early-development reference implementation. Do not connect it to production accounts or sensitive logs without a security review.

## Reporting a vulnerability

Please do not publish credentials, customer data, or an exploitable vulnerability in a public issue. Use GitHub's private vulnerability reporting for this repository if enabled. Otherwise, contact the maintainer through the GitHub profile and include a minimal, sanitized description.

## Security boundaries

- The v0.1 diagnostic tools are read-only and fixed in code.
- The log query is limited to one configured CloudWatch log group, a short time window, and a bounded number of records.
- Model output is untrusted and is never executed as shell commands or AWS API calls.
- The redaction patterns are best-effort and cannot guarantee removal of every secret or personal identifier.
- Operators must review the IAM policy, data path, model selection, encryption, retention, and notification subscriptions before deployment.
