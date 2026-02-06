# bugreaper-X
BugReaperX – Authorized Security Assurance & Remediation

BugReaperX is a modular security assurance engine designed for authorized asset discovery, vulnerability identification, safe proof‑of‑concept testing, and automated remediation. Unlike exploit kits or “penetration frameworks,” BugReaperX focuses on prevention and fix generation—it produces evidence, prioritizes by risk, and generates patch recommendations to close the loop.

Features

Asset Inventory – Discovers domains, IPs and URLs, resolving DNS records and building an attack surface map.

Network Scanning – Performs safe TCP reachability checks on configurable ports and flags exposed services such as SSH.

Web Analysis – Probes HTTP/HTTPS endpoints for missing security headers, insecure cookie flags, and TLS issues.

Secrets Detection – Scans local codebases for leaked credentials (AWS keys, JWTs, etc.) using regex patterns.

Dependency Audit – Optionally runs pip-audit to detect vulnerable Python dependencies.

Risk Scoring & Prioritization – Assigns P0/P1/P2 categories based on severity, confidence, and exposure.

Reporting – Generates JSON, Markdown and HTML reports with remediation guidance and tags.

Extensible Architecture – Easy to add new scanners or reporting formats.
