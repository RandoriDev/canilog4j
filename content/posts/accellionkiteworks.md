---
draft: 'false'
name: Kiteworks
title: Accellion Kiteworks
vendor: Accellion
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| Kiteworks Statement | [https://www.kiteworks.com/kiteworks-news/log4shell-apache-vulnerability-what-kiteworks-customers-need-to-know/](https://www.kiteworks.com/kiteworks-news/log4shell-apache-vulnerability-what-kiteworks-customers-need-to-know/) |

## Community Resources
| Resource | Link |
| --- | --- |
| Kiteworks Statement | [https://www.kiteworks.com/kiteworks-news/log4shell-apache-vulnerability-what-kiteworks-customers-need-to-know/](https://www.kiteworks.com/kiteworks-news/log4shell-apache-vulnerability-what-kiteworks-customers-need-to-know/) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Fix </ul> |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | As a precaution, Kiteworks released a 7.6.1 Hotfix software update to address the vulnerability. This patch release adds the mitigation for CVE-2021-44228 contained in the Solr package as recommended by Apache Solr group. Specifically, it updates the Log4j library to a non-vulnerable version on CentOS 7 systems as well as adds the recommended option “$SOLR_OPTS -Dlog4j2.formatMsgNoLookups=true” to disable the possible attack vector on both CentOS 6 and CentOS 7. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | "As a precaution, Kiteworks released a 7.6.1 Hotfix software update to address the vulnerability. This patch release adds the mitigation for CVE-2021-44228 contained in the Solr package as recommended by Apache Solr group. Specifically, it updates the Log4j library to a non-vulnerable version on CentOS 7 systems as well as adds the recommended option “$SOLR_OPTS -Dlog4j2.formatMsgNoLookups=true” to disable the possible attack vector on both CentOS 6 and CentOS 7." |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/16/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2022-01-03 11:01:35 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated vendorPatchExists. Updated community note. Updated community link Kiteworks Statement. Updated community note.  |
| 2021-12-30 21:31:50 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated vendorPatchExists. Updated vendor link Kiteworks Statement. Updated community note. Updated community note.  |
