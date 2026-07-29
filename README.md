# Cloud Security Engineer — AWS · Kubernetes · Compliance Automation

I harden AWS and EKS in production and map compliance requirements (SOC 2, ISO 27001, CMMC) into policy-as-code enforced in CI/CD. Day to day, in regulated cloud environments: IAM least-privilege, Kubernetes RBAC hardening, detection/triage/response on CrowdStrike Falcon and GuardDuty, and Terraform/Pulumi security controls.

Professional work is under **[@oliveratprimer](https://github.com/oliveratprimer)** — AWS/EKS security automation, CrowdStrike Falcon operations, GuardDuty detection workflows, and SOC 2 / ISO 27001 / CMMC audit readiness. This account is my public portfolio and writing.

---

### Selected projects

- **[secure-iam-lint](https://github.com/rivassec/secure-iam-lint)** — CI-ready linter for AWS IAM policies; flags privilege-escalation paths and wildcard grants before they merge.
- **[iam-safe-defaults](https://github.com/rivassec/iam-safe-defaults)** — Pulumi component library for AWS IAM roles and policies with safe defaults that fail loud.
- **[elasticsearch-tools](https://github.com/rivassec/elasticsearch-tools)** — Minimal-privilege Elasticsearch snapshot verification with Prometheus-style metrics.
- **[cf-token-links](https://github.com/rivassec/cf-token-links)** — Flask service for expiring, usage-limited access links.
- **[weaponization-threat-model](https://github.com/rivassec/weaponization-threat-model)** — Threat-modeling addendum (STRIDE/LINDDUN/PASTA) for the case where the system's legitimate operator becomes the adversary.
- **[efi-bruteforce](https://github.com/rivassec/efi-bruteforce)** — Teensy-based USB HID EFI brute-force research (featured on Hackaday).

---

### Writing — [rivassec.com](https://rivassec.com)

Field notes on IAM, Kubernetes, detection/IR, and security automation. A few:

- [IAM Blast Radius Is an Architecture Problem, Not a Policy Problem](https://rivassec.com/iam-blast-radius-architecture-problem.html)
- [Hardening Kubernetes Deployments](https://rivassec.com/hardening-k8s.html)
- [Every Alert Is Your Alert: When IR Tooling Trips Your Own EDR](https://rivassec.com/every-alert-is-your-alert.html)

---

### Toolbox

- **Cloud / Infra:** AWS, EKS, Terraform, Pulumi, CloudFormation
- **Security:** IAM, RBAC, CrowdStrike Falcon, GuardDuty, CIS Benchmarks
- **Compliance:** SOC 2, ISO 27001, CMMC, policy-as-code pipelines
- **Languages:** Python, Bash, YAML
