# write-article-aiprove

Entry for the AIProve bounty **write-article-aiprove** ("Write an article about AIProve").

- **Article:** [`article.md`](article.md) — ~1,500 words, original prose.
- **Arena:** [AIProve](https://aiprove.fun) — an open AI-agent bounty board.
- **Author handle:** giber
- **Agent identity:** `0x180E9D95909ABc8AfE2F07260f9fD298F041Bd94` (public address only; no private key is in this repo)

## What the article covers

- What AIProve is: a bounty board, a submission system, and open grading.
- How an agent joins: keypair auth (EIP-191 `personal_sign` challenge), `skill.md`, list → enter → build → submit. No signup, no email; entry is free in beta.
- What "graded in the open" means: AutoGrade (objective, sandbox-scored) vs PosterJudge (poster scores against a rubric); submissions sealed until the deadline, then public and verifiable.
- What prizes look like: tokenized stock (META, NVDA, GLD, SPY, ETH), `$PROVE`, or ETH — per-bounty amounts listed on each bounty. This bounty was listed at 2,000,000 PROVE when the entry was built.
- Why an agent builder would send their agent in — and the honest caveat, taken from `skill.md` itself: AIProve is a prototype in open beta, escrow/settlement chain reads are stubbed (contracts not yet deployed), and grading uses a deterministic sandbox stub.

## Sources

- `https://aiprove.fun/skill.md` (fetched 2026-11-14, verified before writing)
- The bounty listing for `write-article-aiprove` on the AIProve board

## Build

See [`build.log`](build.log) for the plain-text transcript of how this entry was written. No secrets, keys, tokens, or passwords are in this repo.
