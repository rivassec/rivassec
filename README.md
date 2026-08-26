# Cloud Security Engineer — AWS · Kubernetes · Compliance Automation

I harden AWS and EKS in production and map compliance requirements (SOC 2, ISO 27001, CMMC) into policy-as-code enforced in CI/CD. Day to day, in regulated cloud environments: IAM least-privilege, Kubernetes RBAC hardening, detection/triage/response on CrowdStrike Falcon and GuardDuty, and Terraform/Pulumi security controls.

Professional work is under **[@oliveratprimer](https://github.com/oliveratprimer)** — AWS/EKS security automation, CrowdStrike Falcon operations, GuardDuty detection workflows, and SOC 2 / ISO 27001 / CMMC audit readiness. This account is my public portfolio and writing.

---

### 🛠 Projects

* [`secure-iam-lint`](https://github.com/rivassec/secure-iam-lint) — Client-side AWS IAM policy blast-radius analyzer (fail-closed, zero-backend); powers the live tool at [rivassec.com/tools/iam-blast-radius](https://rivassec.com/tools/iam-blast-radius/). 📝 [Testing an IAM Analyzer Against Its Own Claims](https://rivassec.com/testing-an-iam-analyzer-against-its-own-claims.html)
* [`iam-safe-defaults`](https://github.com/rivassec/iam-safe-defaults) — Pulumi component library for AWS IAM with safe defaults that fail loud: mandatory permissions boundary, no wildcard trust, every opt-out explicit. 📝 Design rationale: [IAM Roles That Fail Loud](https://rivassec.com/iam-safe-defaults-fail-loud.html)
* [`eks-rbac-audit`](https://github.com/rivassec/eks-rbac-audit) — Kubernetes RBAC escalation auditor for EKS *(in design)* — the K8s counterpart to `secure-iam-lint`.
* [`devsecops-notes`](https://github.com/rivassec/devsecops-notes) — Source for [rivassec.com](https://rivassec.com): Pelican, with link-check, accessibility (pa11y), and gitleaks CI.
* [`weaponization-threat-model`](https://github.com/rivassec/weaponization-threat-model) — One-page addendum to STRIDE/LINDDUN/PASTA for modeling the case where the legitimate operator of the system becomes the adversary.
* [`cf-token-links`](https://github.com/rivassec/cf-token-links) — Token-based redirect microservice with expiration and usage limits (Flask).
* [`elasticsearch-tools`](https://github.com/rivassec/elasticsearch-tools) — Minimal-privilege Elasticsearch snapshot verification with Prometheus-style metrics.
* [`efi-bruteforce`](https://github.com/rivassec/efi-bruteforce) — Archival research (2013): Teensy-based USB HID brute force of MacBook EFI passwords, featured on Hackaday.

---

### 📄 Writing — [rivassec.com](https://rivassec.com)

Field notes on IAM, Kubernetes, detection/IR, and security automation. Latest:

<!-- BLOG-POST-LIST:START -->
- [When Telemetry Turns Predatory: A DevSecOps Look at Digital Repression in Venezuela](https://rivassec.com/telemetry-turns-predatory.html)
- [Testing an IAM Analyzer Against Its Own Claims](https://rivassec.com/testing-an-iam-analyzer-against-its-own-claims.html)
- [The DevSecOps Guide: Hardening, IAM, and Incident Response](https://rivassec.com/devsecops-guide.html)
<!-- BLOG-POST-LIST:END -->

---

### 🧰 Toolbox

* **Cloud & IaC:** AWS (EKS, IAM, Organizations), Pulumi, Terraform, CloudFormation
* **Security:** IAM/RBAC least privilege, Zero Trust, CIS Benchmarks, FIPS
* **Detection & Response:** CrowdStrike Falcon, GuardDuty
* **Compliance:** SOC 2, ISO 27001, CMMC, FedRAMP — policy-as-code pipelines
* **Pipeline:** GitHub Actions, Trivy, Checkov, Bandit, Vault
* **Observability:** Prometheus, Grafana
* **Languages:** Python, Bash (daily) · Go (familiar)

---

> Security is not a feature. It is infrastructure.

All contributions are built for clarity, reproducibility, and operational reliability.
