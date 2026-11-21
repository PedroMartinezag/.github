# Security Policy

Security and supply-chain integrity are first-class priorities across all CLIs, container daemons, and GitHub Actions maintained under `@PedroMartinezag`.

## Supported Versions

Security patches are always applied to the latest minor/patch release on the `main` branch of each active repository. Users running production workloads are strongly encouraged to pin release digests or verify SLSA provenance attestations where provided.

## Reporting a Vulnerability

**Please do NOT report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, please report suspected vulnerabilities privately using **GitHub Private Vulnerability Reporting**:
1. Navigate to the **Security** tab of the affected repository.
2. Click **Advisories** and select **Report a vulnerability**.
3. Include minimal reproduction steps, affected version/OS architecture, and potential impact.

### Response Timeline

* **Initial Acknowledgment:** Within **48 hours** of submission.
* **Triage & Remediation Plan:** Within **5 business days**.
* **Coordinated Disclosure:** Once a patched binary/release is published, contributors will be credited in the official GitHub Security Advisory (unless anonymity is requested).
