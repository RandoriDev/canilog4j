---
communityVulnerable: true
draft: 'false'
name: Bamboo Server & Data Center
title: Atlassian Bamboo Server & Data Center
vendor: Atlassian
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| FAQ for CVE-2021-44228  Atlassian Support  Atlassian Documentation | [https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |

## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Only vulnerable when using non-default config, cloud version fixed |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | So far, we do not believe our on-premises products are vulnerable to exploitation in their default configuration. However, if a you have modified the default logging configuration (log4j.properties) to enable the JMS Appender functionality, remote code execution may be possible |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-15 14:06:17 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated communityVulnerable. Updated community link source. Updated community note.  |
| 2021-12-15 2:46:48 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendorPatchExists. Updated vendor link FAQ for CVE-2021-44228  Atlassian Support  Atlassian Documentation. Updated community note.  |
