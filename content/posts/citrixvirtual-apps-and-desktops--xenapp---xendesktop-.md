---
communityVulnerable: true
draft: 'false'
name: Virtual Apps and Desktops (XenApp & XenDesktop)
title: Citrix Virtual Apps and Desktops (XenApp & XenDesktop)
vendor: Citrix
vendorInvestigating: true
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| Citrix Statement | [https://support.citrix.com/article/CTX335705](https://support.citrix.com/article/CTX335705) |

## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://support.citrix.com/article/CTX335705](https://support.citrix.com/article/CTX335705) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | CVE-2021-4104: Not vuln ; CVE-2021-44228: Fix ; CVE-2021-45046: Investigation </ul> |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Impacted – Linux VDA (non-LTSR versions only), Not vulnerable: App Layering, Delivery Controller, Director, FAS, HDX, Profile Management, PVS, Session Recording, Storefront, Studio, Windows VDA, WEM |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | IMPACTED: Linux VDA (non-LTSR versions only)- CVE-2021-44228 and CVE-2021-45046: Customers are advised to apply the latest update as soon as possible to reduce the risk of exploitation. [Linux Virtual Delivery Agent 2112](https://www.citrix.com/downloads/citrix-virtual-apps-and-desktops/components/linux-vda-2112.html). See the [Citrix Statement](https://support.citrix.com/article/CTX335705) for additional mitigations. For CVE-2021-45105: Investigation has shown that Linux VDA is not impacted. Nonetheless, the Linux VDA 2112 has been updated (21.12.0.30, released December 20th) to contain Apache log4j version 2.17.0. NOT IMPACTED: Linux VDA LTSR all versions; All other CVAD components. |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/21/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-20 12:37:57 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated vendorInvestigating. Updated vendorPatchExists. Updated community note. Updated community link source. Updated community note.  |
| 2021-12-22 4:23:16 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated communityVulnerable. Updated vendor link Citrix Statement. Updated community note. Updated community note.  |
