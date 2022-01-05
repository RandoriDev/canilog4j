---
communityVulnerable: true
draft: 'false'
name: AWS EKS, ECS, Fargate
title: Amazon AWS EKS, ECS, Fargate
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
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | "To help mitigate the impact of the open-source Apache “Log4j2"" utility (CVE-2021-44228 and CVE-2021-45046) security issues on customers’ containers, Amazon EKS, Amazon ECS, and AWS Fargate are deploying a Linux-based update (hot-patch). This hot-patch will require customer opt-in to use, and disables JNDI lookups from the Log4J2 library in customers’ containers. These updates are available as an Amazon Linux package for Amazon ECS customers, as a DaemonSet for Kubernetes users on AWS, and will be in supported AWS Fargate platform versions" |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | To help mitigate the impact of the open-source Apache “Log4j2" utility (CVE-2021-44228 and CVE-2021-45046) security issues on customers’ containers, Amazon EKS, Amazon ECS, and AWS Fargate are deploying a Linux-based update (hot-patch). This hot-patch will require customer opt-in to use, and disables JNDI lookups from the Log4J2 library in customers’ containers. These updates are available as an Amazon Linux package for Amazon ECS customers, as a DaemonSet for Kubernetes users on AWS, and will be in supported AWS Fargate platform versions |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/16/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2022-01-03 11:01:35 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated vendorPatchExists. Updated community note. Updated community link Update for Apache Log4j2 Issue (CVE-2021-44228). Updated community note.  |
| 2021-12-30 21:31:50 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendorPatchExists. Updated vendor link Update for Apache Log4j2 Issue (CVE-2021-44228). Updated community note. Updated community note.  |
