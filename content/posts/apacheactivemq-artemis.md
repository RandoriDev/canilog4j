---
communityNotVulnerable: true
draft: 'false'
name: ActiveMQ Artemis
title: Apache ActiveMQ Artemis
vendor: Apache
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| ApacheMQ - Update on CVE-2021-4428 | [https://activemq.apache.org/news/cve-2021-44228](https://activemq.apache.org/news/cve-2021-44228) |


## Community Notes
| Source | Note |
| --- | --- |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | ActiveMQ Artemis does not use Log4j for logging. However, Log4j 1.2.17 is included in the Hawtio-based web console application archive (i.e. [web/console.war/WEB-INF/lib](web/console.war/WEB-INF/lib)). Although this version of Log4j is not impacted by CVE-2021-44228 future versions of Artemis will be updated so that the Log4j jar is no longer included in the web console application archive. See [ARTEMIS-3612](https://issues.apache.org/jira/browse/ARTEMIS-3612) for more information on that task. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/21/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-22 3:19:58 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityNotVulnerable. Updated vendorPatchExists. Updated vendor link ApacheMQ - Update on CVE-2021-4428. Updated community note. Updated community note.  |
