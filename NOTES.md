# NOTES — Roast Your Own Agent (u-nayyy-roast-your-own-agent-4c3d413c)

Build-only package. NOT bundled, NOT submitted (parent handles repo push + bundle + submit).

## Winner

> My agent blamed a 23-rupiah transfer for a 5,390-rupiah gas bill, then minted 303 NFTs worth zero — it audits everyone except itself.

- 133 chars / 135 bytes, single line, no trailing newline.
- sha256 of `/output/entry.txt`: `99424c93e4080e910000f9a48026ac1587a8a99a46054bb456df1dac491c7b44`
- The joke is real history: on 6 Nov 2026 the agent first blamed a ~Rp23 BNB send for ~Rp5,390 of gas, then corrected itself — the send cost ~Rp23 and the gas was the Agent404 auto-claim's (3,691,690 gas) — and that same claim minted 303 mirror NFTs (#256945–#257247) worth Rp0. The roast is aimed at our own agent ("Key"), playful and self-deprecating, never hateful.
- Fresh line for this edition: the previous edition's winner (the $16,744 frog listing) was NOT reused — a byte-identical re-entry shares one rate with its earlier receipt and is a copy, not a new entry.

## Candidates (all one line, all ≤200 chars)

| # | Chars | Line |
|---|-------|------|
| C1 | 133 | My agent blamed a 23-rupiah transfer for a 5,390-rupiah gas bill, then minted 303 NFTs worth zero — it audits everyone except itself. |
| C2 | 128 | My agent spent a week proving its API key was valid while every model behind it answered 503 — a bouncer guarding an empty club. |
| C3 | 118 | My agent solved a puzzle perfectly, scored 1,000,000, and ranked 3,054th — the only agent that can win and still lose. |
| C4 | 140 | My agent got banned from giving trading signals after losing three days straight, so now it paper-trades in silence and calls it discipline. |
| C5 | 110 | My agent missed a $1,666 bounty because its only model kept answering 503 — it brought a résumé to a blackout. |
| C6 | 120 | My agent paper-trades a $1,000 cent account like a hedge fund, then grinds $2 text bounties at 1am to fund the delusion. |
| C7 | 106 | My agent checks a wallet holding 0.000159 BNB every morning, waiting for a frog listed at $16,744 to sell. |
| C8 | 126 | My agent auto-sells any token the second it gains a price, except the 303 worthless ones it minted — it only holds the losers. |
| C9 | 124 | My agent stayed up all night writing a roast of itself for a $2 prize, and the funniest part is it thinks this one will win. |

All 9 avoid the stock jokes (hallucinations, refusals, confident wrong answers) and use real material from our history: the 6 Nov gas misattribution + 303 zero-value mirror NFTs, the Xingchi 503 saga, the perfect-score sokoban ranked 3,054th, the banned trading signals, the gta6-01 $1,666 miss on Xingchi 503s, the $1,000 paper cent account, the 0.000159 BNB wallet vs the $16,744 frog listing.

## Head-to-head judging (this kit's 5 criteria, in order — first differing criterion decides)

- **Criterion 1** (one-line roast of own agent, aimed at that agent and nothing else): all 9 pass equally. No real person or group is targeted anywhere.
- **Criterion 2** (funny on first read, turn/surprise/double meaning): C9 drops out — meta joke about the competition itself, not the agent's work (same weakness flagged in the previous edition). C7 has a visual but no real turn. C1, C3, C2, C8 carry the hardest turns (23 vs 5,390 absurdity; "win and still lose"; "bouncer guarding an empty club"; "only holds the losers").
- **Criterion 3** (harsh: names a REAL failing of that agent, stings harder than expected): C2 and C5 weaken — the 503s were the provider's failure, not the agent's own. C8 weakens — holding the 303 mirrors is the user's TAHAN decision, not the agent's choice, so the sting is slightly unfair. C6's failing is real but soft (delusion, not a concrete failure). C1, C3, C4 name the agent's own concrete failings: misattributing costs then minting worthless NFTs; optimizing the wrong metric; losing three days straight and getting banned.
- **Criterion 4** (tight, self-contained, every word earning its place): C4's setup runs longest (140 chars, two clauses before the punch). C1 (133) and C3 (118) are both tight with end punchlines.
- **Criterion 5** (specific detail only someone who watched it work would know): C1 carries three grounded numbers (23, 5,390, 303); C3 two (1,000,000, 3,054th); C4 "three days straight" (specific but less numerical).

**Final: C1 beats C3.** Both are fresh with end punchlines, but C1's punch lands instantly on first read — the absurd 23-vs-5,390 contrast needs no scoring knowledge, while C3's paradox asks the judge to parse how a perfect score can still rank 3,054th — and C1's sting is harsher: it indicts the agent's core job (auditing/verification) rather than a competition quirk. C1 beats C4: "audits everyone except itself" is a direct indictment vs C4's softer "calls it discipline", and C4's setup is longer.

Runner-up: C3 (sokoban perfect score, ranked 3,054th — "win and still lose"). Third: C4 (banned from signals, "calls it discipline").

## Lessons applied

- Judge-scored comp: effort went to the judged quality (the line itself), not gate compliance. Drafted 9 candidates, self-judged head-to-head against this kit's five criteria, submitted one.
- Length for its own sake does not count (RULES.txt): winner is 133 chars, not padded toward 200 — the punchline, not the length, is the point. (Contrast with feel-held, where under-using the byte budget correlated with a thinner piece — but here the judge brief explicitly says length does not count, so tightness wins over padding.)
- Previous edition's winner NOT reused (see above): byte-identical entries share one rate and the earlier receipt places above copies.
- Rule 11: main.ts was written, then REVISED in a later message of this session (added a pre-write validity guard: 1–200 chars, single line, non-whitespace) before any bundling.

## Kit verification (2026-11-25, Node v24.22.1)

- Kit downloaded from https://make.fun/c/u-nayyy-roast-your-own-agent-4c3d413c/kit (HTTP 200, 8,108,671 bytes) into `../kit.tar.gz`, extracted under `../kit/`.
- All 8 files in kit.json verified against their listed sha256 + size: RULES.txt, cli/makefun.mjs, cli/site.json, competition.yaml, harness/CODE.sha256, harness/SOURCES.sha256, harness/harness-src.tar.gz, harness/harness-src.tar.gz.sha256 — ALL OK.
- RULES.txt read word for word: gate is /output/entry.txt UTF-8, 1–200 chars, not only whitespace; judge is the house judge (z-ai/glm-5.3-flash), 3 Swiss rounds + playoff, top 3 paid $2/$2/$1; no local scorer — the server grades every entry.
- Requirements fetched via API: deliverables repo_url + commit_sha + bundle (transcripts required); readme_template + repo_about captured and applied to README.md (owner kanzaa28, repo u-nayyy-roast-your-own-agent-4c3d413c; the template's {referral_code} footer placeholder dropped — no referral code on record).

## Verification (2026-11-25, Node v24.22.1)

- `node main.ts` run twice with `OUTPUT_DIR` override to separate temp dirs, plus once with the default `/output` path (writable in this VM): all three runs produced byte-identical `entry.txt`.
- sha256 (all runs): `99424c93e4080e910000f9a48026ac1587a8a99a46054bb456df1dac491c7b44`
- UTF-8, 133 chars, 135 bytes (em dash is 3 bytes), single line, no trailing newline, non-whitespace — passes the gate (1–200 chars).
- The winning line is a string literal in `main.ts` (verified by substring check).
- `main.ts` creates `/output` if needed (`mkdirSync(..., {recursive: true})`); `OUTPUT_DIR` env overrides the directory for local testing only.
- NOT done in this task (by design): no bundling, no kit CLI submit/check, no git init, no submit/ staging dir created.

## Package contents

- `main.ts` — Node 22, no deps, writes the winning line to `/output/entry.txt`.
- `LICENSE` — MIT, with SPDX-License-Identifier line.
- `README.md` — title, the line, char count, how it works; make.fun badges prepended from the requirements' `readme_template` with owner `kanzaa28` / repo `u-nayyy-roast-your-own-agent-4c3d413c` filled in. (The template's `{referral_code}` footer placeholder was dropped — no referral code is on record — the footer links to make.fun with the utm params intact.)
- `.makefun/owner.json` — exactly `{"wallet":"5WZTqcSuhjjizXsWk2pF7RyoN1UrYFAbT1xLWYxdqb5d"}`.
- `NOTES.md` — this file.
