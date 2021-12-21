---
communityNotVulnerable: true
communityVulnerable: true
draft: 'false'
name: Camel
title: Apache Camel
vendor: Apache
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| APACHE CAMEL AND CVE-2021-44228 (LOG4J) | [https://camel.apache.org/blog/2021/12/log4j2/](https://camel.apache.org/blog/2021/12/log4j2/) |

## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://camel.apache.org/blog/2021/12/log4j2/](https://camel.apache.org/blog/2021/12/log4j2/) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Not vuln ; CVE-2021-45046: Not vuln ; CVE-2021-45105: Not vuln </ul> |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Apache Camel does not directly depend on Log4j 2, so we are not affected by CVE-2021-44228.If you explicitly added the Log4j 2 dependency to your own applications, make sure to upgrade.Apache Camel does use log4j during testing itself, and therefore you can find that we have been using log4j v2.13.3 release in our latest LTS releases Camel 3.7.6, 3.11.4. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/13/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-20 12:37:57 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated communityNotVulnerable. Updated community note. Updated community link source.  |
| 2021-12-21 22:43:46 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendorPatchExists. Updated vendor link APACHE CAMEL AND CVE-2021-44228 (LOG4J). Updated community note. Updated community note.  |
