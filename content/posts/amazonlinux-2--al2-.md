---
draft: 'false'
name: Linux 2 (AL2)
title: Amazon Linux 2 (AL2)
vendor: Amazon
vendorPatchExists: true
---


## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://aws.amazon.com/security/security-bulletins/AWS-2021-006/](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| hotpatch | [https://aws.amazon.com/blogs/opensource/hotpatch-for-apache-log4j/](https://aws.amazon.com/blogs/opensource/hotpatch-for-apache-log4j/) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Fix </ul> |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | By default not vulnerable, and a new version of Amazon Kinesis Agent which is part of AL2 addresses the Log4j issue. Opt-in hot-patch to mitigate the Log4j issue in JVM layer is available |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-27 15:29:04 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated vendorPatchExists. Updated community note. Updated community link source. Updated community link hotpatch. Updated community note.  |
