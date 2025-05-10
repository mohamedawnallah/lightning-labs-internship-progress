# Lightning Labs Internship Progress

A personal repository to track my progress during my internship at Lightning Labs. All work shared here is open-source.

## Legend

- ⬜: Not started
- ⚪: Feedback — not yet addressed
- ⏳: In review / Pending CI fixes
- ✅: Merged / done

---

## Milestone 0 — Onboarding & LND Community PRs

| Status | Period           | Activity                                                                                      | Role   | Artifact                                                                                                                                                                              |
|:------:|:----------------|:----------------------------------------------------------------------------------------------|:------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ✅     | April 30        | Set up Keybase, Electrum Wallet, development environment, and completed onboarding tasks       | Author | - My Keybase: [keybase.io/mohamed_awnallah](https://keybase.io/mohamed_awnallah)<br>- My Bitcoin address: `bc1qrwm55gg54ytcuh5qhgz0u2dx4mp925uqdsn975`                                |
| ⏳     | May 1 – May 2   | Remove deprecated endpoints: sendpayment, sendtoroute, sendtoroutesync, sendpaymentsync        | Author | [PR #8348](https://github.com/lightningnetwork/lnd/pull/8348)                                                                                                                         |
| ⏳     | May 1 – May 2   | Add support for DNS host name in NodeAnnouncement message (discovery+lnwire)                  | Author | [PR #9455](https://github.com/lightningnetwork/lnd/pull/9455)                                                                                                                         |

---

## Milestone 1 — Design Document for Neutrino Side-Header Loading

| Status | Period         | Activity                                                                                                 | Role   | Artifact             |
|:------:|:--------------|:---------------------------------------------------------------------------------------------------------|:------:|:--------------------:|
| ✅     | May 3 – May 9 | Write design document for Neutrino side-header loading                                                   | Author | Shared internally    |
| ✅     | May 3 – May 9 | Outline and prioritize milestones and actionable tasks for side-header loading project                    | Author | —                    |

---

## Milestone 2 — Block and Compressed Filter Headers File I/O Support

| Status | Period         | Activity                                                                                       | Role   | Artifact |
|:------:|:--------------|:-----------------------------------------------------------------------------------------------|:------:|:--------:|
| ⬜     | May 10 – 18    | Implement headers file I/O support                                                            | Author | —        |
| ⬜     | May 10 – 18    | Add syntactic, chaining, and sanity validation checks for headers                             | Author | —        |
| ⬜     | May 10 – 18    | Develop headers merge intervals algorithm and overlap checkpointing                           | Author | —        |
| ⬜     | May 10 – 18    | Write unit and integration tests for headers file I/O                                         | Author | —        |
| ⬜     | May 10 – 18    | Benchmark sync time with and without side-header loading using headers file I/O               | Author | —        |
| ⬜     | May 10 – 18    | Perform memory profiling for headers file I/O                                                 | Author | —        |
| ⬜     | May 10 – 18    | Document side-header loading process using file I/O                                           | Author | —        |

---

## Milestone 3 — Block and Compressed Filter Headers HTTP I/O Support

| Status | Period | Activity                                                               | Role   | Artifact |
|:------:|:------|:-----------------------------------------------------------------------|:------:|:--------:|
| ⬜     | TBD   | Implement headers HTTP I/O support                                               | Author | —        |
| ⬜     | TBD   | Write unit and integration tests for headers HTTP I/O                            | Author | —        |
| ⬜     | TBD   | Benchmark sync time with and without side-header loading using headers HTTP I/O  | Author | —        |
| ⬜     | TBD   | Perform memory profiling for headers HTTP I/O                                    | Author | —        |
| ⬜     | TBD   | Document side-header loading process using HTTP I/O                              | Author | —        |

---

## Milestone 4 — Design Document for Neutrino Parallel Header Download via Checkpoints

| Status | Period | Activity                                                                                      | Role   | Artifact |
|:------:|:------|:----------------------------------------------------------------------------------------------|:------:|:--------:|
| ⬜     | TBD   | Write design document for parallel header download using header checkpoints                    | Author | —        |
| ⬜     | TBD   | Outline and prioritize milestones for parallel header download via checkpoints                 | Author | —        |

---

## Milestone 5 — TBD

---

## Misc

| Status | Period       | Activity                                                                     | Role     | Artifact                                                            |
|:------:|:------------|:-----------------------------------------------------------------------------|:--------:|:--------------------------------------------------------------------:|
| ✅     | May 1        | Review: enhance help text for `wtclient` session and terminate subcommands   | Reviewer | [PR #9765](https://github.com/lightningnetwork/lnd/pull/9765)       |
| ⏳     | May 3        | Remove dead code (chore)                                                     | Author   | [PR #9780](https://github.com/lightningnetwork/lnd/pull/9780)        |
| ✅     | May 8        | Improve error messages for header store (headerfs)                           | Author   | [PR #314](https://github.com/lightninglabs/neutrino/pull/314)        |
| ⏳     | May 8        | Fail gracefully on header write (headerfs)                                   | Author   | [PR #313](https://github.com/lightninglabs/neutrino/pull/313)        |
