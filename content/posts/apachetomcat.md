---
communityLog4jOptional: true
communityNotVulnerable: true
cpe: cpe:2.3:a:apache:tomcat:*:*:*:*:*:*:*:*
draft: 'false'
name: Tomcat
title: Apache Tomcat
vendor: Apache
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| Apache Tomcat Security Notes | [https://tomcat.apache.org/security-9.html](https://tomcat.apache.org/security-9.html) |
| Usage | [https://tomcat.apache.org/tomcat-8.0-doc/logging.html#Using_Log4j](https://tomcat.apache.org/tomcat-8.0-doc/logging.html#Using_Log4j) |

## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://tomcat.apache.org/tomcat-9.0-doc/logging.html](https://tomcat.apache.org/tomcat-9.0-doc/logging.html) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Not vuln ; CVE-2021-45046: Not vuln ; CVE-2021-45105: Not vuln </ul> |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Apache Tomcat 9.0.x has no dependency on any version of log4j. Web applications deployed on Apache Tomcat may have a dependency on log4j. You should seek support from the application vendor in this instance. It is possible to configure Apache Tomcat 9.0.x to use log4j 2.x for Tomcat's internal logging. This requires explicit configuration and the addition of the log4j 2.x library. Anyone who has switched Tomcat's internal logging to log4j 2.x is likely to need to address this vulnerability. In most cases, disabling the problematic feature will be the simplest solution. Exactly how to do that depends on the exact version of log4j 2.x being used. Details are provided on the [log4j 2.x security page](https://logging.apache.org/log4j/2.x/security.html) |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/21/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-27 15:29:04 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated communityNotVulnerable. Updated community note. Updated community link source.  |
| 2021-12-22 3:19:58 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated vendor link Apache Tomcat Security Notes. Updated community note. Updated community note.  |
| 2021-12-13T22:46:00-07:00 | [Randori](https://www.randori.com/log4j/) | Updated cpe. Updated communityLog4jOptional. Updated vendor link Usage.  |
