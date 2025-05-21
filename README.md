# Lightning Labs Internship Progress

A personal repository to track my progress during my internship at Lightning Labs. All work shared here is open-source.

## Legend

- ⬜: Not started
- ⚪: Feedback — not yet addressed
- 🏗️: Created
- ⏳: In review
- ✅: Merged

---

## Milestone 0 — Onboarding & LND Community PRs

| Status | Period           | Activity                                                                                      | Role   | Artifact                                                                                                                                                                              |
|:------:|:----------------|:----------------------------------------------------------------------------------------------|:------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 🏗️     | April 30        | Set up Keybase, Electrum Wallet, development environment, and completed onboarding tasks       | Author | - My Keybase: [keybase.io/mohamed_awnallah](https://keybase.io/mohamed_awnallah)                               |
| ⏳     | May 1 – May 2   | Remove deprecated endpoints: sendpayment, sendtoroute, sendtoroutesync, sendpaymentsync        | Author | [PR #8348](https://github.com/lightningnetwork/lnd/pull/8348)                                                                                                                         |
| ⏳     | May 1 – May 2   | Add support for DNS host name in NodeAnnouncement message (discovery+lnwire)                  | Author | [PR #9455](https://github.com/lightningnetwork/lnd/pull/9455)                                                                                                                         |

---

## Milestone 1 — Design Document for Neutrino Side-Header Loading

| Status | Period         | Activity                                                                                                 | Role   | Artifact             |
|:------:|:--------------|:---------------------------------------------------------------------------------------------------------|:------:|:--------------------:|
| 🏗️     | May 3 – May 9 | Write design document for Neutrino side-header loading                                                   | Author | Shared internally    |
| 🏗️     | May 3 – May 9 | Outline and prioritize milestones and actionable tasks for side-header loading project                    | Author | —                    |

---

## Milestone 2 — Block and Compressed Filter Headers File I/O Support

📌 **Note:** Period extended from May 18 to May 20 due to exam on the 18th.

| Status | Period         | Activity                                                                                       | Role   | Artifact |
|:------:|:--------------|:-----------------------------------------------------------------------------------------------|:------:|:--------:|
| 🏗️     | May 10 – 20    | Creating & evaluating a/b testing experiments _collective exhaustive_ for side-header loading feature| Author | [REPO #side-header-loading-ab-testing-experiments](https://github.com/mohamedawnallah/side-header-loading-ab-testing-experiments)        |
| ⏳     | May 10 – 20    | Implement headers file I/O support                                                            | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)  |
| ⏳     | May 10 – 20    | Add syntactic, chaining, and sanity validation checks for headers                             | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 10 – 20    | Develop headers merge intervals algorithm and overlap checkpointing                           | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 10 – 20    | Write unit and integration tests for headers file I/O                                         | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 10 – 20    | Benchmark sync time with and without side-header loading using headers file I/O               | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 10 – 20    | Perform memory profiling for headers file I/O                                                 | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 10 – 20    | Document side-header loading process using file I/O                                           | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |

---

## Milestone 3 — Block and Compressed Filter Headers HTTP I/O Support

| Status | Period | Activity                                                               | Role   | Artifact |
|:------:|:------|:-----------------------------------------------------------------------|:------:|:--------:|
| ⏳     | May 13 - 20   | Implement headers HTTP I/O support                                               | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 13 - 20   | Write unit and integration tests for headers HTTP I/O                            | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 13 - 20   | Benchmark sync time with and without side-header loading using headers HTTP I/O  | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 13 - 20   | Perform memory profiling for headers HTTP I/O                                    | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |
| ⏳     | May 13 - 20   | Document side-header loading process using HTTP I/O                              | Author | [PR #317](https://github.com/lightninglabs/neutrino/pull/317)        |

---

## Milestone 4 — PRs Review

| Status | Period | Activity                                                               | Role   | Artifact |
|:------:|:------|:-----------------------------------------------------------------------|:------:|:--------:|
| ⬜     | May 20 - 22   | query: add OnMaxTries                                           | Reviewer | [PR #308](https://github.com/lightninglabs/neutrino/pull/308) |
| ⬜     | May 20 - 22   | peer, main, netsync, blockchain: parallel block downloads       | Reviewer | [PR #2226](https://github.com/btcsuite/btcd/pull/2226)        |

---

## Milestone 5 — Design Document for Neutrino Parallel Header Download via Checkpoints

| Status | Period | Activity                                                                                      | Role   | Artifact |
|:------:|:------|:----------------------------------------------------------------------------------------------|:------:|:--------:|
| ⬜     | TBD   | Write design document for parallel header download using header checkpoints                    | Author | —        |
| ⬜     | TBD   | Outline and prioritize milestones for parallel header download via checkpoints                 | Author | —        |

---        

## Milestone 6 — TBD
   
---

## Misc

| Status | Period       | Activity                                                                     | Role     | Artifact                                                            |
|:------:|:------------|:-----------------------------------------------------------------------------|:--------:|:--------------------------------------------------------------------:|
| ⏳     | May 1        | Review: enhance help text for `wtclient` session and terminate subcommands   | Reviewer | [PR #9765](https://github.com/lightningnetwork/lnd/pull/9765)       |
| 🏗️     | May 3        | Remove dead code (chore)                                                     | Author   | [PR #9780](https://github.com/lightningnetwork/lnd/pull/9780)        |
| ✅     | May 8        | Improve error messages for header store (headerfs)                           | Author   | [PR #314](https://github.com/lightninglabs/neutrino/pull/314)        |
| ⏳     | May 8        | Fail gracefully on header write (headerfs)                                   | Author   | [PR #313](https://github.com/lightninglabs/neutrino/pull/313)        |
| 🏗️     | May 16        | Validate network addresses on `UpdateNodeAnnouncement` RPC                  | Author   | [Issue #9816](https://github.com/lightningnetwork/lnd/issues/9816)     |
| ⚪     | May 21 - 28   | Add new APIs `GetPeerInfo`, `GetBlockChainInfo`, and `RawRequest` to chain interface | Author   | [PR #973](https://github.com/btcsuite/btcwallet/pull/973)     |
| ⚪     | TBD   | multi: unify RPC connection creations for chain backends | Author   | [PR #9435](https://github.com/lightningnetwork/lnd/pull/9435)     |
| ⚪     | TBD   | feat(lncli): Add --route_hints flag to sendpayment --keysend/--amp and queryroutes | Reviewer   | [PR #9721](https://github.com/lightningnetwork/lnd/pull/9721)     |
| ⚪     | TBD          | Manage shutdown requests with status codes                                   | Author   | [PR #9395](https://github.com/lightningnetwork/lnd/pull/9395)        |

---

## Stretch

### Neutrino

| Status | Period       | Activity                                                                     | Role     | Artifact                                                            |
|:------:|:------------|:-----------------------------------------------------------------------------|:--------:|:--------------------------------------------------------------------:|
| ⚪     | TBD        | query: implement likelihood sampling based peer scheduling and add work stealing across peers ([Issue #292](https://github.com/lightninglabs/neutrino/issues/292))   | Contributor | –       |
| ⚪     | TBD        | unban peer ([Issue #253](https://github.com/lightninglabs/neutrino/issues/253))   | Contributor | –       |
| ⚪     | TBD        | sync: roll back filter header chain if invalid filter is detected post-sync ([Issue #218](https://github.com/lightninglabs/neutrino/issues/218))   | Contributor | –       |
| ⚪     | TBD        | neutrino: implement BIP 151 ([Issue #69](https://github.com/lightninglabs/neutrino/issues/69))   | Contributor | –       |
| ⚪     | TBD        | blockmanager: once we're at tip, start to use sendheaders to learn of new chains ([Issue #67](https://github.com/lightninglabs/neutrino/issues/67))   | Contributor | –       |
| ⚪     | TBD        | blockmanager: aggressively pipeline getheaders requests ([Issue #66](https://github.com/lightninglabs/neutrino/issues/67))   | Contributor | –       |
| ⚪     | TBD        | rescan: only fetch blocks w/ witness data if we matched on an outpoint ([Issue #64](https://github.com/lightninglabs/neutrino/issues/64))   | Contributor | –       |
| ⚪     | TBD        | NewChainService does not traverse through all supplied Neutrino Peers before returning with error ([Issue #60](https://github.com/lightninglabs/neutrino/issues/60))   | Contributor | –       |

### BTCD

### LND
