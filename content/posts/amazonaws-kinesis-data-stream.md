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

## Community Resources
| Resource | Link |
| --- | --- |
| Update for Apache Log4j2 Issue (CVE-2021-44228) | [https://aws.amazon.com/security/security-bulletins/AWS-2021-006/](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Fix </ul> |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | We are actively patching all sub-systems that use Log4j2 by applying updates. The Kinesis Client Library (KCL) version 2.X and the Kinesis Producer Library (KPL) are not impacted. For customers using KCL 1.x, we have released an updated version and we strongly recommend that all KCL version 1.x customers upgrade to KCL version 1.14.5 (or higher) |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | We are actively patching all sub-systems that use Log4j2 by applying updates. The Kinesis Client Library (KCL) version 2.X and the Kinesis Producer Library (KPL) are not impacted. For customers using KCL 1.x, we have released an updated version and we strongly recommend that all KCL version 1.x customers upgrade to KCL version 1.14.5 (or higher) |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/14/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-31 9:06:53 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated vendorPatchExists. Updated community note. Updated community link Update for Apache Log4j2 Issue (CVE-2021-44228). Updated community note.  |
| 2021-12-30 21:31:50 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendorPatchExists. Updated vendor link Update for Apache Log4j2 Issue (CVE-2021-44228). Updated community note. Updated community note.  |
