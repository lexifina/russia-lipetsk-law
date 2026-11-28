<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Lipetsk Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:44 UTC, Lipetsk Oblast: Official Internet Portal of Legal Information (region48): 12 addresses read; 3 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Lipetsk Oblast: Official Internet Portal of Legal Information (region48)](http://publication.pravo.gov.ru/documents/block/region48) | `zakony-<year>/` | daily | 2026-11-28 05:44 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:43](checks/2026-11.md#ru-pravo-lipetsk-20261128t054346z) | pravo-lipetsk | 12 | 3 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-lipetsk-law/compare/db668890bacd...51625e3b1677) |
| [2026-11-27 05:36](checks/2026-11.md#ru-pravo-lipetsk-20261127t053606z) | pravo-lipetsk | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:40](checks/2026-11.md#ru-pravo-lipetsk-20261126t054036z) | pravo-lipetsk | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:14](checks/2026-11.md#ru-pravo-lipetsk-20261125t061419z) | pravo-lipetsk | 12 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-lipetsk-law/compare/4c51c9e1ce27...b7e7a32ddf92) |
| [2026-11-24 14:10](checks/2026-11.md#ru-pravo-lipetsk-20261124t141053z) | pravo-lipetsk | 12 | 28 | 0 | 0 | 0 (0) | changes found | [6](https://github.com/lexifina/russia-lipetsk-law/compare/4e0eb1399f5b...d08af9de3c8e) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
