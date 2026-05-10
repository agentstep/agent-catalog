# Dependency Auditor — managed-agent template

Scans package manifests for known vulnerabilities, cross-references CVE databases, and prioritizes findings by exploitability and blast radius.

## What it does

1. Parses package manifests (package.json, requirements.txt, go.mod, Cargo.toml, etc.)
2. Resolves the full dependency tree including transitive dependencies
3. Cross-references each package version against CVE/NVD and GitHub Advisory databases
4. Scores findings by CVSS, exploitability, and whether the vulnerable code path is reachable
5. Recommends upgrade paths with breaking change warnings
6. Generates a prioritized remediation report with estimated effort per fix
