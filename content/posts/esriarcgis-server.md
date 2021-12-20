---
draft: 'false'
name: ArcGIS Server
title: ESRI ArcGIS Server
vendor: ESRI
vendorPatchExists: true
---

## Vendor Resources
| Resource | Link |
| --- | --- |
| https://www.esri.com/arcgis-blog/products/arcgis-enterprise/administration/arcgis-software-and-cve-2021-44228-aka-log4shell-aka-logjam/ | [https://www.esri.com/arcgis-blog/products/arcgis-enterprise/administration/arcgis-software-and-cve-2021-44228-aka-log4shell-aka-logjam/](https://www.esri.com/arcgis-blog/products/arcgis-enterprise/administration/arcgis-software-and-cve-2021-44228-aka-log4shell-aka-logjam/) |


## Community Notes
| Source | Note |
| --- | --- |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Requires script remediation.  ESRI has created scripts to remove the JndiLookup class, but has not issued patches to upgrade the Log4j versions |
| [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Last Update: 12/17/2021 |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-18 19:04:10 | [CISAGov](https://raw.githubusercontent.com/cisagov/log4j-affected-db/develop/README.md) | Updated vendorPatchExists. Updated vendor link https://www.esri.com/arcgis-blog/products/arcgis-enterprise/administration/arcgis-software-and-cve-2021-44228-aka-log4shell-aka-logjam/. Updated community note. Updated community note.  |