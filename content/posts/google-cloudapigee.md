---
communityNotVulnerable: true
draft: 'false'
name: Apigee
title: Google Cloud Apigee
vendor: Google Cloud
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| https://cloud.google.com/log4j2-security-advisory | [https://cloud.google.com/log4j2-security-advisory](https://cloud.google.com/log4j2-security-advisory) |


## Community Notes
| Source | Note |
| --- | --- |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Apigee installed Log4j 2 in its Apigee Edge VMs, but the software was not used and therefore the VMs were not impacted by the issues in CVE-2021-44228 and CVE-2021-45046. Apigee updated Log4j 2 to v.2.16 as an additional precaution. It is possible that customers may have introduced custom resources that are using vulnerable versions of Log4j. We strongly encourage customers who manage Apigee environments to identify components dependent on Log4j and update them to the latest version. Visit the Apigee Incident Report for more information. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/17/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-22 14:57:01 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityNotVulnerable. Updated vendor link https://cloud.google.com/log4j2-security-advisory. Updated community note. Updated community note.  |
