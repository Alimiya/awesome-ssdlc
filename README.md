# Awesome SSDLC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub Stars](https://img.shields.io/github/stars/Alimiya/awesome-ssdlc?style=flat-square)](https://github.com/Alimiya/awesome-ssdlc/stargazers) [![GitHub Forks](https://img.shields.io/github/forks/Alimiya/awesome-ssdlc?style=flat-square)](https://github.com/Alimiya/awesome-ssdlc/network/members) [![License: CC0](https://img.shields.io/badge/License-CC0%201.0%20Universal-brightgreen.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)

> A curated list of **Secure Software Development Lifecycle** resources, tools, frameworks, and methodologies for building security into every phase of software development.

---

## Contents

- [Getting Started](#getting-started)
- [Phase 1: Planning & Requirements](#phase-1-planning--requirements)
- [Phase 2: Design & Architecture](#phase-2-design--architecture)
- [Phase 3: Secure Coding & Development](#phase-3-secure-coding--development)
- [Phase 4: Security Testing & Verification](#phase-4-security-testing--verification)
- [Phase 5: Release & Deployment](#phase-5-release--deployment)
- [Phase 6: Operations & Monitoring](#phase-6-operations--monitoring)
- [Phase 7: Continuous Improvement](#phase-7-continuous-improvement)
- [Frameworks & Standards](#frameworks--standards)
- [Tools by Category](#tools-by-category)
- [Language-Specific Resources](#language-specific-resources)
- [Books & Papers](#books--papers)
- [Communities & Events](#communities--events)
- [Contributing](#contributing)

---

## Getting Started

New to SSDLC? Start here:

- [OWASP Top 10 2021](https://owasp.org/www-project-top-ten/) - Web application security risks
- [Microsoft SDL](https://www.microsoft.com/en-us/securityengineering/sdl) - Industry-proven SDL methodology
- [NIST SSDF v1.1](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf) - Federal secure development standard
- [OWASP SAMM 2.0](https://owasp.org/samm/) - Security maturity model
- [Awesome AppSec](https://github.com/paragonie/awesome-appsec) - General application security

---

## Phase 1: Planning & Requirements

### Governance & Strategy

- [OWASP SAMM](https://owasp.org/samm/) - Software Assurance Maturity Model
- [Microsoft SDL](https://www.microsoft.com/en-us/securityengineering/sdl) - Security Development Lifecycle
- [NIST SSDF v1.1](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf) - Secure software development framework
- [CIS Controls v8](https://www.cisecurity.org/controls/) - Prioritized security practices
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework) - Governance framework
- [ISO/IEC 27001:2022](https://www.iso.org/isoiec-27001-information-security-management.html) - Information security management

### Security Requirements

- [OWASP ASVS 4.0](https://owasp.org/www-project-application-security-verification-standard/) - Application security verification standard
- [OWASP API Security Top 10](https://owasp.org/www-project-api-security/) - API security requirements
- [OWASP Proactive Controls 2024](https://owasp.org/www-project-proactive-controls/) - Ranked secure practices
- [NIST SP 800-53 Rev. 5](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf) - Security and privacy controls
- [CWE](https://cwe.mitre.org/) - Common Weakness Enumeration database
- [CAPEC](https://capec.mitre.org/) - Common Attack Pattern Enumeration

### Compliance Frameworks

- [PCI DSS v4.0](https://www.pcisecuritystandards.org/) - Payment card security standard
- [HIPAA Security Rule](https://www.hhs.gov/hipaa/) - Healthcare data protection
- [GDPR](https://gdpr.eu/) - EU data protection regulation
- [CCPA/CPRA](https://oag.ca.gov/privacy) - California privacy law
- [SOC 2 Type II](https://www.aicpa.org/soc2) - Service organization audit
- [FedRAMP](https://www.fedramp.gov/) - Federal compliance program

---

## Phase 2: Design & Architecture

### Threat Modeling

#### Frameworks & Methodologies

- [STRIDE](https://owasp.org/www-project-threat-modeling/) - Threat categorization framework
- [PASTA](https://verymodel.com/pasta-threat-modeling/) - Risk-centric threat analysis
- [CVSS v3.1](https://www.first.org/cvss/) - Vulnerability severity scoring
- [FAIR](https://www.fairinstitute.org/) - Quantitative risk modeling
- [Attack Trees](https://www.schneier.com/academic/archives/1999/12/attack_trees.html) - Hierarchical attack analysis

#### Threat Modeling Tools

- [Microsoft Threat Modeling Tool](https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling) - Free STRIDE tool
- [OWASP Threat Dragon](https://threatdragon.org/) - Open-source web-based modeling
- [IriusRisk](https://www.iriusrisk.com/) - Enterprise threat platform
- [ThreatModeler](https://threatmodeler.com/) - Commercial solution
- [Miro Threat Modeling Template](https://miro.com/templates/threat-modeling/) - Collaborative whiteboard

### Security Architecture Review

- [OWASP Architecture](https://owasp.org/www-community/attacks/) - Architectural security flaws
- [NIST SP 800-64 Rev. 2](https://csrc.nist.gov/publications/detail/sp/800-64/rev-2/final) - System development security
- [AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/userguide/security-pillar.html) - Cloud security design
- [Azure Security Best Practices](https://learn.microsoft.com/en-us/azure/security/) - Microsoft cloud guidance
- [GCP Security Best Practices](https://cloud.google.com/security) - Google Cloud guidance
- [Kubernetes Security Guide](https://kubernetes.io/docs/concepts/security/) - Container security

### Design Checklists & Guides

- [OWASP Cheat Sheets](https://cheatsheetseries.owasp.org/) - Security reference guides
  - [Authentication Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
  - [Authorization Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
  - [Cryptographic Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html)
  - [Secrets Management Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Secrets_Management_Cheat_Sheet.html)
- [NIST SP 800-204](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-204.pdf) - Microservices security
- [12-Factor App](https://12factor.net/) - Cloud-native application design

---

## Phase 3: Secure Coding & Development

### Secure Coding Standards

- [OWASP Top 10 2021](https://owasp.org/www-project-top-ten/) - Web application risks
- [OWASP API Security Top 10](https://owasp.org/www-project-api-security/) - API risks
- [CWE Top 25](https://cwe.mitre.org/top25/) - Most dangerous weaknesses
- [SEI Secure Coding](https://www.securecoding.cert.org/) - Language-specific practices
- [OWASP Proactive Controls](https://owasp.org/www-project-proactive-controls/) - Ranked practices

### Language-Specific Guides

- [Node.js Security Best Practices](https://nodejs.org/en/docs/guides/security/) - Official guide
- [OWASP Node.js Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Nodejs_Security_Cheat_Sheet.html) - Security tips
- [OWASP Python Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Python_Security_Cheat_Sheet.html) - Best practices
- [OWASP Java Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Java_Security_Cheat_Sheet.html) - Framework guidance
- [OWASP Go Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Go_Security_Cheat_Sheet.html) - Language guide
- [OWASP PHP Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/PHP_Security_Cheat_Sheet.html) - PHP practices
- [Spring Security](https://spring.io/projects/spring-security) - Enterprise authentication
- [Laravel Security](https://laravel.com/docs/11.x/security) - Framework features
- [Rust Security](https://doc.rust-lang.org/nightly/nomicon/safety.html) - Memory safety

### Dependency & Supply Chain Security

- [SLSA Framework](https://slsa.dev/) - Supply chain security levels
- [SBOM Minimum Elements](https://ntia.doc.gov/report/2021/minimum-elements-software-bill-materials-sbom) - NIST standards
- [CycloneDX](https://cyclonedx.org/) - Standard SBOM format
- [SPDX](https://spdx.dev/) - Component metadata standard
- [OWASP Dependency-Track](https://dependencytrack.org/) - Component management platform

### Secrets Management

- [OWASP Secrets Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Secrets_Management_Cheat_Sheet.html) - Best practices
- [HashiCorp Vault](https://www.vaultproject.io/) - Open-source secrets management
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/) - Cloud secrets
- [Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault) - Microsoft secrets
- [Google Cloud Secret Manager](https://cloud.google.com/secret-management) - GCP secrets
- [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) - Kubernetes secrets

---

## Phase 4: Security Testing & Verification

### Static Application Security Testing (SAST)

- [Sonarqube](https://www.sonarsource.com/products/sonarqube/) - Enterprise SAST scanner
- [Snyk Code](https://snyk.io/product/snyk-code/) - Developer-first SAST
- [Semgrep](https://semgrep.dev/) - Fast static analysis
- [Bandit](https://bandit.readthedocs.io/) - Python security linting
- [gosec](https://github.com/securego/gosec) - Go security checker
- [SpotBugs](https://spotbugs.readthedocs.io/) - Java bug detection
- [ESLint Security Plugin](https://github.com/nodesecurity/eslint-plugin-security) - JavaScript linting

### Dependency Scanning (SCA)

- [Snyk Open Source](https://snyk.io/product/snyk-open-source/) - Dependency vulnerability scanning
- [OWASP Dependency-Track](https://dependencytrack.org/) - SBOM management
- [GitHub Dependabot](https://docs.github.com/en/code-security/dependabot) - GitHub native scanning
- [WhiteSource (Mend)](https://www.whitesourcesoftware.com/) - Enterprise SCA
- [Black Duck](https://www.blackducksoftware.com/) - Synopsys platform
- [Trivy](https://github.com/aquasecurity/trivy) - Fast vulnerability scanner

### Dynamic Application Security Testing (DAST)

- [OWASP ZAP](https://www.zaproxy.org/) - Free web scanner
- [Burp Suite Community](https://portswigger.net/burp/communitydownload) - Web testing
- [42Crunch](https://42crunch.com/) - API security platform
- [Snyk API Security](https://snyk.io/product/snyk-api-security/) - API scanning
- [Acunetix](https://www.acunetix.com/) - Commercial web scanner

### Penetration Testing Frameworks

- [OWASP WSTG v4.2](https://owasp.org/www-project-web-security-testing-guide/) - Web app testing
- [PTES](http://www.pentest-standard.org/) - Penetration testing standard
- [NIST SP 800-115](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-115.pdf) - Technical testing
- [OWASP MASTG](https://mobile-security.gitbook.io/) - Mobile app testing
- [HackTricks](https://book.hacktricks.xyz/) - Penetration testing notes

### Code Review Resources

- [OWASP Code Review Guide](https://cheatsheetseries.owasp.org/cheatsheets/Code_Review_Guide.html) - Review methodology
- [CWE Top 25](https://cwe.mitre.org/top25/) - Most dangerous weaknesses
- [Gerrit](https://www.gerritcodereview.com/) - Open-source code review
- [Review Board](https://www.reviewboard.org/) - Self-hosted platform

---

## Phase 5: Release & Deployment

### Container Security

- [CIS Docker Benchmark](https://www.cisecurity.org/benchmark/docker) - Hardening guide
- [CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes) - Hardening
- [Trivy](https://github.com/aquasecurity/trivy) - Container scanner
- [Snyk Container](https://snyk.io/product/container-security/) - Image scanning
- [Podman](https://podman.io/) - Daemonless container engine
- [Falco](https://falco.org/) - Container runtime security

### Infrastructure as Code (IaC) Security

- [Checkov](https://www.checkov.io/) - IaC scanning
- [OWASP IaC Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Infrastructure_as_Code_Security_Cheat_Sheet.html) - Best practices
- [Snyk IaC](https://snyk.io/product/infrastructure-as-code-security/) - Scanning
- [Pulumi Crossguard](https://www.pulumi.com/docs/guides/crossguard/) - Policy-as-code

### Artifact & Supply Chain Security

- [Syft](https://github.com/anchore/syft) - SBOM generation
- [Cosign](https://docs.sigstore.dev/cosign/overview/) - Container signing
- [Notary](https://github.com/notaryproject/notary) - Container trust
- [SLSA Provenance](https://slsa.dev/provenance) - Build attestation
- [in-toto](https://in-toto.io/) - Supply chain integrity

### CI/CD Security

- [GitHub Secret Scanning](https://github.com/features/security) - Secret detection
- [GitGuardian](https://www.gitguardian.com/) - SaaS scanner
- [TruffleHog](https://github.com/trufflesecurity/trufflehog) - Open-source scanner
- [git-secrets](https://github.com/awslabs/git-secrets) - AWS tool
- [Jenkins Security](https://www.jenkins.io/security/) - CI/CD hardening
- [GitLab CI/CD Security](https://docs.gitlab.com/ee/ci/cloud_services/) - GitLab features

### Cloud Security Baselines

- [CIS AWS Foundations Benchmark](https://www.cisecurity.org/benchmark/aws) - AWS hardening
- [CIS Azure Benchmarks](https://www.cisecurity.org/benchmark/azure) - Azure hardening
- [CIS Google Cloud Benchmarks](https://www.cisecurity.org/benchmark/gcp) - GCP hardening
- [AWS Security Best Practices](https://aws.amazon.com/security/) - Official guidance
- [Azure Security Best Practices](https://learn.microsoft.com/en-us/azure/security/) - Microsoft guidance
- [GCP Security Best Practices](https://cloud.google.com/security) - Google Cloud guidance

---

## Phase 6: Operations & Monitoring

### Vulnerability Databases & Feeds

- [CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities) - Real-world exploits
- [NVD](https://nvd.nist.gov/) - NIST CVE database
- [GitHub Advisories](https://github.com/advisories) - GitHub vulnerabilities
- [EPSS](https://www.first.org/epss) - Exploitability prediction
- [Snyk Vulnerability Database](https://snyk.io/vulnerability-database) - Open source vulns

### Security Monitoring & SIEM

- [Wazuh](https://wazuh.com/) - SIEM and threat detection
- [OpenSearch](https://opensearch.org/) - Search and analytics
- [Elastic Stack (ELK)](https://www.elastic.co/what-is/elk-stack) - Log aggregation
- [Graylog](https://www.graylog.org/) - Log management
- [Prometheus](https://prometheus.io/) - Metrics collection
- [Grafana](https://grafana.com/) - Metrics visualization

### Incident Response

- [NIST SP 800-61 Rev. 3](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r3.pdf) - Incident handling
- [Sigma Rules](https://github.com/SigmaHQ/sigma) - Detection rules
- [Yara](https://virustotal.github.io/yara/) - Malware detection
- [OSQuery](https://osquery.io/) - System instrumentation
- [Velociraptor](https://docs.velociraptor.app/) - Digital forensics
- [MITRE ATT&CK](https://attack.mitre.org/) - Adversary tactics

### Logging Best Practices

- [OWASP Logging Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html) - Best practices
- [NIST SP 800-92](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-92.pdf) - Log management
- [Structured Logging Guide](https://www.kartar.net/2015/12/structured-logging/) - JSON logging

---

## Phase 7: Continuous Improvement

### Maturity Frameworks

- [OWASP SAMM 2.0](https://owasp.org/samm/) - Security Assurance Maturity Model
- [CMMI for Development](https://cmmiinstitute.com/) - Capability Maturity Model
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework) - Governance
- [NIST SP 800-160 SSE](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-160v1.pdf) - Systems security
- [Microsoft SDL Optimization](https://www.microsoft.com/en-us/securityengineering/sdl) - Process maturity

### Assessment Tools

- [OWASP SAMM Assessment Tool](https://samu.samsconf.org/) - Self-assessment
- [Ostorlab](https://www.ostorlab.co/) - API assessment
- [NIST CMMC](https://www.nist.gov/publications/cybersecurity-maturity-model-certification-cmmc-specification-version-20) - Government compliance

---

## Frameworks & Standards

### OWASP Resources

- [OWASP Top 10 2021](https://owasp.org/www-project-top-ten/) - Web app risks
- [OWASP API Security Top 10](https://owasp.org/www-project-api-security/) - API risks
- [OWASP ASVS 4.0](https://owasp.org/www-project-application-security-verification-standard/) - Verification standard
- [OWASP SAMM 2.0](https://owasp.org/samm/) - Maturity model
- [OWASP WSTG v4.2](https://owasp.org/www-project-web-security-testing-guide/) - Testing guide
- [OWASP MASVS](https://owasp.org/www-project-mobile-app-security-verification-standard/) - Mobile security
- [OWASP Proactive Controls](https://owasp.org/www-project-proactive-controls/) - Ranked practices

### NIST Standards

- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework) - Governance
- [NIST SSDF v1.1 (SP 800-218)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf) - Development
- [NIST SP 800-53 Rev. 5](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf) - Controls
- [NIST SP 800-61 Rev. 3](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r3.pdf) - Incident handling
- [NIST SP 800-115](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-115.pdf) - Security testing

### Weakness & Vulnerability Standards

- [CWE](https://cwe.mitre.org/) - Software weakness database
- [CWE Top 25](https://cwe.mitre.org/top25/) - Most dangerous weaknesses
- [CVSS v3.1](https://www.first.org/cvss/) - Severity scoring
- [CAPEC](https://capec.mitre.org/) - Attack patterns
- [MITRE ATT&CK](https://attack.mitre.org/) - Adversary tactics

### Supply Chain & DevOps

- [SLSA Framework](https://slsa.dev/) - Supply chain security
- [SBOM Standards](https://ntia.doc.gov/report/2021/minimum-elements-software-bill-materials-sbom) - Component inventory
- [NIST SP 800-204](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-204.pdf) - Microservices

### Compliance

- [PCI DSS v4.0](https://www.pcisecuritystandards.org/) - Payment card security
- [HIPAA Security Rule](https://www.hhs.gov/hipaa/) - Healthcare security
- [GDPR](https://gdpr.eu/) - EU privacy
- [CCPA/CPRA](https://oag.ca.gov/privacy) - California privacy
- [SOC 2](https://www.aicpa.org/soc2) - Service audit
- [ISO/IEC 27001:2022](https://www.iso.org/isoiec-27001-information-security-management.html) - Information security
- [FedRAMP](https://www.fedramp.gov/) - Federal compliance

---

## Tools by Category

### SAST (Static Code Analysis)

- [Sonarqube](https://www.sonarsource.com/products/sonarqube/) - Enterprise quality and security
- [Snyk Code](https://snyk.io/product/snyk-code/) - Developer-first SAST
- [Semgrep](https://semgrep.dev/) - Lightweight analysis
- [Bandit](https://bandit.readthedocs.io/) - Python linting
- [gosec](https://github.com/securego/gosec) - Go checker
- [SpotBugs](https://spotbugs.readthedocs.io/) - Java detection
- [ESLint](https://eslint.org/) - JavaScript linting

### SCA (Dependency Scanning)

- [Snyk Open Source](https://snyk.io/product/snyk-open-source/) - Dependency scanning
- [OWASP Dependency-Track](https://dependencytrack.org/) - Component management
- [GitHub Dependabot](https://docs.github.com/en/code-security/dependabot) - GitHub scanning
- [Trivy](https://github.com/aquasecurity/trivy) - Fast scanner
- [WhiteSource (Mend)](https://www.whitesourcesoftware.com/) - Enterprise SCA
- [Black Duck](https://www.blackducksoftware.com/) - Synopsys platform

### DAST (Dynamic Analysis)

- [OWASP ZAP](https://www.zaproxy.org/) - Free web scanner
- [Burp Suite Community](https://portswigger.net/burp/communitydownload) - Web testing
- [42Crunch](https://42crunch.com/) - API platform
- [Acunetix](https://www.acunetix.com/) - Commercial scanner

### Container & Infrastructure

- [Trivy](https://github.com/aquasecurity/trivy) - Container and IaC scanning
- [Snyk Container](https://snyk.io/product/container-security/) - Image scanning
- [Checkov](https://www.checkov.io/) - IaC scanning
- [Grype](https://github.com/anchore/grype) - Vulnerability scanner
- [Falco](https://falco.org/) - Runtime security
- [Kubewarden](https://www.kubewarden.io/) - Policy enforcement

### Secret Scanning

- [GitGuardian](https://www.gitguardian.com/) - Secret detection
- [TruffleHog](https://github.com/trufflesecurity/trufflehog) - Open-source scanner
- [git-secrets](https://github.com/awslabs/git-secrets) - AWS tool
- [detect-secrets](https://github.com/Yelp/detect-secrets) - Yelp detector

### Secrets Management

- [HashiCorp Vault](https://www.vaultproject.io/) - Open-source management
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/) - AWS secrets
- [Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault) - Azure secrets
- [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) - Kubernetes secrets
- [SOPS](https://github.com/mozilla/sops) - Encrypted storage

### SBOM & Supply Chain

- [Syft](https://github.com/anchore/syft) - SBOM generation
- [CycloneDX](https://cyclonedx.org/) - SBOM standard
- [SPDX](https://spdx.dev/) - Component metadata
- [Cosign](https://docs.sigstore.dev/) - Container signing
- [in-toto](https://in-toto.io/) - Supply chain attestation

### Monitoring & Logging

- [Wazuh](https://wazuh.com/) - SIEM and detection
- [OpenSearch](https://opensearch.org/) - Log aggregation
- [Prometheus](https://prometheus.io/) - Metrics collection
- [Grafana](https://grafana.com/) - Metrics visualization
- [OSQuery](https://osquery.io/) - System monitoring

---

## Language-Specific Resources

### JavaScript/Node.js

- [Node.js Security Best Practices](https://nodejs.org/en/docs/guides/security/) - Official guide
- [OWASP Node.js Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Nodejs_Security_Cheat_Sheet.html) - Tips
- [Express Security](https://expressjs.com/en/advanced/best-practice-security.html) - Framework guidance
- [ESLint Security Plugin](https://github.com/nodesecurity/eslint-plugin-security) - Linting

### Python

- [OWASP Python Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Python_Security_Cheat_Sheet.html) - Best practices
- [Bandit](https://bandit.readthedocs.io/) - Security linting
- [Django Security](https://docs.djangoproject.com/en/stable/topics/security/) - Framework guidance
- [FastAPI Security](https://fastapi.tiangolo.com/tutorial/security/) - Security tutorial

### Java

- [OWASP Java Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Java_Security_Cheat_Sheet.html) - Best practices
- [Spring Security](https://spring.io/projects/spring-security) - Authentication framework
- [OWASP ESAPI Java](https://owasp.org/www-project-enterprise-security-api/) - Security API

### Go

- [OWASP Go Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Go_Security_Cheat_Sheet.html) - Best practices
- [gosec](https://github.com/securego/gosec) - Security checker
- [Go Security Guidelines](https://securego.io/) - Official guidelines

### PHP

- [OWASP PHP Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/PHP_Security_Cheat_Sheet.html) - Best practices
- [Laravel Security](https://laravel.com/docs/11.x/security) - Framework guidance
- [PHPCS Security](https://github.com/WordPress/PHP_CodeSniffer) - Code standards

### Rust

- [Rust Security Guidelines](https://anssi-fr.github.io/rust-guide/) - Official guide
- [Cargo Audit](https://github.com/rustsec/cargo-audit) - Dependency checker

### C/C++

- [SEI Secure Coding C](https://www.securecoding.cert.org/confluence/display/c/Top+10+Secure+Coding+Practices) - Best practices
- [Clang Static Analyzer](https://clang-analyzer.llvm.org/) - Analysis tool

---

## Books & Papers

### Essential Books

- [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470) - Comprehensive testing guide
- [Secure by Design](https://www.amazon.com/Secure-by-Design-Loren-Kohnfelder/dp/1617294357) - Architecture fundamentals
- [Threat Modeling: Designing for Security](https://www.amazon.com/Threat-Modeling-Designing-Adam-Shostack/dp/1492056553) - Adam Shostack's guide
- [The Pragmatic Programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) - With security sections
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/) - Free reference
- [DevSecOps: Building Secure Applications](https://www.oreilly.com/library/view/devsecops/9781098131746/) - Modern approach

### Research Papers

- [NIST SP 800-218 (SSDF)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf) - Federal standard
- [NIST SP 800-61 (Incident Handling)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r3.pdf) - IR playbook
- [NIST SP 800-115 (Security Testing)](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-115.pdf) - Testing methodology
- [SLSA Framework](https://slsa.dev/) - Supply chain security

---

## Communities & Events

### Online Communities

- [OWASP Community](https://owasp.org/) - Open-source foundation
- [r/netsec on Reddit](https://www.reddit.com/r/netsec/) - Network security
- [Security Stack Exchange](https://security.stackexchange.com/) - Q&A community
- [HackerNews](https://news.ycombinator.com/) - Tech news
- [InfoSec News](https://www.infosec-news.com/) - News digest

### Conferences

- [OWASP AppSecDays](https://owasp.org/) - Global AppSec events
- [Black Hat](https://www.blackhat.com/) - Research conference
- [DEF CON](https://www.defcon.org/) - Hacker conference
- [RSA Conference](https://www.rsaconference.com/) - Enterprise security
- [LocoMocoSec](https://www.locomocosec.com/) - Hawaii AppSec

### Podcasts & Videos

- [Security Now](https://www.grc.com/SecurityNow.htm) - Weekly podcast
- [Darknet Diaries](https://darknetdiaries.com/) - True security stories
- [IppSec on YouTube](https://www.youtube.com/@ippsec) - Penetration testing
- [LiveOverflow](https://www.youtube.com/@LiveOverflow) - CTF education

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Related Awesome Lists

- [Awesome AppSec](https://github.com/paragonie/awesome-appsec) - Application security
- [Awesome Security](https://github.com/sbilly/awesome-security) - General cybersecurity
- [Awesome Penetration Testing](https://github.com/enaqx/awesome-pentest) - Penetration testing
- [Awesome DevSecOps](https://github.com/TaptuIT/awesome-devsecops) - DevSecOps practices
- [Awesome Kubernetes Security](https://github.com/aquasecurity/awesome-kubernetes-security) - Kubernetes security
