# Security Policy

To report security issues with projects under the Pylons Project, send email to: pylons-project-security@googlegroups.com.
If we determine that your report may be a security issue with the project, we may contact you for further information.
We volunteers ask that you delay public disclosure of your report for at least ninety (90) days from the date you report it to us.
This will allow sufficient time for us to process your report and coordinate disclosure with you.

Once verified and fixed, the following steps will be taken.

-   We will use GitHub's Security Advisory tool to report the issue.
-   GitHub will review our Security Advisory report for compliance with Common Vulnerabilities and Exposures (CVE) rules.
    If it is compliant, they will submit it to the MITRE Corporation to generate a [CVE](https://www.cve.org/).
    This in turn submits the CVE to the [National Vulnerability Database (NVD)](https://nvd.nist.gov/vuln/search).
    GitHub notifies us of their decision.
-   Assuming it is compliant, we then publish our Security Advisory on GitHub, which triggers the next steps.
-   GitHub will publish the CVE to the CVE List.
-   GitHub will broadcast our Security Advisory via the [GitHub Advisory Database](https://github.com/advisories).
-   GitHub will send [security alerts](https://docs.github.com/en/code-security/supply-chain-security/managing-vulnerabilities-in-your-projects-dependencies/about-alerts-for-vulnerable-dependencies) to all repositories that use our package (and have opted into security alerts).
    This includes Dependabot alerts.
-   We will make a bug-fix release.
-   We will send an announcement through our usual channels, including those listed on the Pylons Project website's [Contact](https://pylonsproject.org/about-contact.html) page.
-   We will provide credit to the reporter or researcher in the vulnerability notice.
