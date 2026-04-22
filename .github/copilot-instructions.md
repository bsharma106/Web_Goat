# .github/copilot-instructions.md

When performing a code review, focus on security risks in this pull request.

Ignore style-only suggestions unless they affect security or correctness.

Check for:
- authentication and authorization flaws
- secrets exposure
- input validation gaps
- SQL/command injection
- XSS, CSRF, SSRF, XXE
- path traversal and unsafe file access
- insecure deserialization
- crypto misuse
- insecure defaults
- unsafe shell execution

For each finding, include:
- severity
- exploit scenario
- concrete remediation

Apply the checks in /security/security-checklist.md when present.
