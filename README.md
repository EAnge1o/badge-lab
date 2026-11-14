# badge-lab

A small, self-contained playground for practising GitHub collaboration
workflows (branches, pull requests, discussions) and for keeping a record
of how profile achievements are earned. Nothing here is production code.

## What is in here

| Path | Purpose |
| --- | --- |
| `README.md` | this overview |
| `docs/achievement-notes.md` | badge criteria, thresholds and gotchas |
| `CONTRIBUTING.md` | how to make a small, reviewable change here |

## Badge checklist

| Achievement | Requirement | Tier 1 |
| --- | --- | --- |
| Quickdraw | close an issue or PR within 5 minutes of opening it | 1 |
| YOLO | merge a pull request without a review | 1 |
| Pull Shark | open pull requests that get merged | 2 |
| Pair Extraordinaire | co-author a commit in a merged PR | 1 |
| Galaxy Brain | discussion answers marked as accepted | 2 |
| Starstruck | a public repository receives stars | 16 |
| Public Sponsor | publicly sponsor an open-source maintainer | 1 |

Starstruck and Public Sponsor cannot be self-served: they need real stars
from other people and a real sponsorship.

## Ground rules

Every pull request in this repository makes a real, readable change. No
empty commits, no dummy PR spam. Achievements are calculated asynchronously
by GitHub and can take anywhere from minutes to 48 hours to appear; the
source repository must stay public or the badge can be revoked.

## Reproduce

See `github_badges.py` (kept outside this repo) for the REST calls used to
create the branches, file changes, pull requests, issue and discussions.
