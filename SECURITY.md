# Security Policy

This policy covers how to report vulnerabilities in Silus products and how Silus discloses vulnerabilities we find in others.

Contact: **security@silus.us**

## Reporting a vulnerability in a Silus product

Email security@silus.us with:

- Affected product and version
- Description of the issue and its impact
- Steps to reproduce or a proof of concept
- Your name or handle and how you would like to be credited

You can also use GitHub's private vulnerability reporting on the affected repository, where enabled.

Please do not open public issues for security reports.

### What to expect

| Stage | Target |
|---|---|
| Acknowledgment | Within 3 business days |
| Initial assessment | Within 10 business days |
| Status updates | At least every 14 days until resolved |
| Fix and advisory | Coordinated with the reporter, normally within 90 days |

When a report is confirmed, Silus will publish an advisory, request a CVE where appropriate, and credit the reporter unless they ask to remain anonymous.

### Scope

In scope: Silus software and services published or operated by Silus LLC, including repositories under [github.com/silus-cyber](https://github.com/silus-cyber) and [silus.us](https://silus.us).

Out of scope:

- Denial of service or volumetric testing
- Social engineering or physical attacks against Silus staff or facilities
- Findings in third-party services we use, which should be reported to that vendor
- Reports from automated scanners without a demonstrated impact

### Safe harbor

Silus will not pursue legal action against researchers who act in good faith under this policy: avoiding privacy violations and service disruption, accessing only the data needed to demonstrate the issue, and giving us reasonable time to remediate before public disclosure.

## How Silus discloses vulnerabilities we find

When Silus researchers discover a vulnerability in third-party software or hardware, we:

1. Report it privately to the vendor or maintainer through their published security contact, or through a CVE Numbering Authority or CERT/CC if no contact exists.
2. Allow 90 days for remediation before public disclosure. We may extend this when the vendor is actively working on a fix, or shorten it if the vulnerability is being actively exploited.
3. Request a CVE ID and ask that the advisory credit Silus LLC and the individual researcher.
4. Publish our own advisory after the fix is available or the disclosure deadline passes.
