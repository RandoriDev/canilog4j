---
communityNotVulnerable: true
draft: 'false'
name: Cloud Composer
title: Google Cloud Cloud Composer
vendor: Google Cloud
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| https://cloud.google.com/log4j2-security-advisory | [https://cloud.google.com/log4j2-security-advisory](https://cloud.google.com/log4j2-security-advisory) |

## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://cloud.google.com/log4j2-security-advisory](https://cloud.google.com/log4j2-security-advisory) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Not vuln ; CVE-2021-45046: Not vuln ; CVE-2021-45105: Not vuln </ul> |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Product does not use Log4j 2 and is not impacted by the issues identified in CVE-2021-44228 and CVE-2021-45046.  Cloud Composer does not use Log4j 2 and is not impacted by the issues in CVE-2021-44228 and CVE-2021-45046. It is possible that customers may have imported or introduced other dependencies via DAGs, installed PyPI modules, plugins, or other services that are using vulnerable versions of Log4j 2. We strongly encourage customers, who manage Composer environments to identify components dependent on Log4j 2 and update them to the latest version. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Product does not use Log4j 2 and is not impacted by the issues identified in CVE-2021-44228 and CVE-2021-45046.  Cloud Composer does not use Log4j 2 and is not impacted by the issues in CVE-2021-44228 and CVE-2021-45046. It is possible that customers may have imported or introduced other dependencies via DAGs, installed PyPI modules, plugins, or other services that are using vulnerable versions of Log4j 2. We strongly encourage customers, who manage Composer environments to identify components dependent on Log4j 2 and update them to the latest version. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/15/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-27 15:29:04 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated communityNotVulnerable. Updated community note. Updated community link source. Updated community note.  |
| 2021-12-30 21:31:50 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityNotVulnerable. Updated vendor link https://cloud.google.com/log4j2-security-advisory. Updated community note. Updated community note.  |
