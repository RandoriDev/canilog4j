---
communityVulnerable: true
draft: 'false'
name: AWS Kinesis Data Stream
title: Amazon AWS Kinesis Data Stream
vendor: Amazon
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| Update for Apache Log4j2 Issue (CVE-2021-44228) | [https://aws.amazon.com/security/security-bulletins/AWS-2021-006/](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |


## Community Notes
| Source | Note |
| --- | --- |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | We are actively patching all sub-systems that use Log4j2 by applying updates. The Kinesis Client Library (KCL) version 2.X and the Kinesis Producer Library (KPL) are not impacted. For customers using KCL 1.x, we have released an updated version and we strongly recommend that all KCL version 1.x customers upgrade to KCL version 1.14.5 (or higher) |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/14/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-22 19:06:21 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendorPatchExists. Updated vendor link Update for Apache Log4j2 Issue (CVE-2021-44228). Updated community note. Updated community note.  |
