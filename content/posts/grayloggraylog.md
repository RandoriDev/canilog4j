---
draft: 'false'
name: Graylog
title: Graylog Graylog
vendor: Graylog
vendorPatchExists: true
---


## Community Resources
| Resource | Link |
| --- | --- |
| source | [https://www.graylog.org/post/graylog-update-for-log4j](https://www.graylog.org/post/graylog-update-for-log4j) |

## Community Notes
| Source | Note |
| --- | --- |
| [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | The vulnerable Log4j library is used to record GrayLog's own log information. Vulnerability is not triggered when GrayLog stores exploitation vector from an outer system. Graylog [version 4.2.4 fixes](https://github.com/Graylog2/graylog2-server/compare/4.2.3...4.2.4) [another vulnerability](https://www.lunasec.io/docs/blog/log4j-zero-day-update-on-cve-2021-45046/) |

## Sources
| Date | Attribution | Description |
| --- | --- | --- |
| 2021-12-17 8:29:21 | [NCSC-NL](https://github.com/NCSC-NL/log4shell/blob/main/software/README.md) | Updated vendorPatchExists. Updated community link source. Updated community note.  |
