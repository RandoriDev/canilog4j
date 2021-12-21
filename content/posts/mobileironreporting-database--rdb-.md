---
communityVulnerable: true
draft: 'false'
name: Reporting Database (RDB)
title: MobileIron Reporting Database (RDB)
vendor: MobileIron
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j?language=en_US | [https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j?language=en_US](https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j?language=en_US) |


## Community Notes
| Source | Note |
| --- | --- |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | The mitigation instructions listed in a subsequent section removes a vulnerable Java class (JNDILookUp.class) from the affected Log4J Java library and as a result removes the ability to perform the RCE attack.  The workaround needs to be applied in a maintenance window. You will not be able to access the admin portal during the procedure, however, end user devices will continue to function. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/20/21 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-21 22:43:46 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendorPatchExists. Updated vendor link https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j?language=en_US. Updated community note. Updated community note.  |
