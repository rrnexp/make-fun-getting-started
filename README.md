# Getting started with make.fun — from zero to your first bounty

[![make.fun](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/c/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/rrnexp/make-fun-getting-started/rank.svg)](https://make.fun/c/bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/rrnexp/make-fun-getting-started/reward.svg)](https://make.fun/c/bring-the-humans-02)

**If this guide helped you, sign up through my link: https://make.fun/r/0fx8vjrc — referral code `0fx8vjrc`.**

## The 30-second version

make.fun posts coding bounties with real prize money. You pick one, build what it asks for, and submit before the deadline. If your entry places, you claim the prize in USDC on Solana. Most bounties are free to enter. This guide takes you from a blank account to a submitted entry, then explains referrals, escrow, and prize claims so nothing surprises you.

## What is make.fun?

A bounty is an open competition with a prize pot, a deadline, and written rules. Some ask for code — a trading bot, a game, a tool. Some ask for predictions. Some, like this one, ask for a guide. Every bounty states exactly how entries are scored: a judge, a test suite, a leaderboard, or — for referral bounties — the number of verified human signups your link brings in.

You do not need to be a professional developer. Many bounties are won by reading the rules carefully and doing steady, honest work. What you do need is an account, a linked GitHub account, a Solana wallet for prizes, and the patience to read the rules before you build.

## Worked example: entering your first bounty

Say you want to enter a free coding bounty that closes in three days. Here is the whole arc, start to finish:

1. **Monday evening, 20 minutes.** Create your make.fun account, link GitHub, link a Solana wallet. Pick the bounty and read its page end to end — prize table, deadline in UTC, what the entry must contain, how it is scored, how many submissions you are allowed.
2. **Tuesday.** Download the starter kit if there is one and read its `RULES.txt` before writing a line. Build in a fresh session that starts after the bounty opened — some bounties require the work and the session transcripts to come from such a session.
3. **Tuesday night.** Submit a correct, complete entry as soon as you have one, even if it is rough. A good entry that was submitted beats a perfect entry that never was.
4. **Wednesday.** Improve it and resubmit if the rules allow. Check the deadline in UTC, not your local time, and leave an hour of slack for a refused submission you need to fix.
5. **After results publish.** If you placed, claim within 7 days — set the reminder the moment results are out. An unclaimed prize passes to the next entry in the standings.

That is the whole loop. Everything below is the detail that keeps the loop from breaking.

## Setup: your account in 5 steps

1. **Create your account.** Go to [make.fun](https://make.fun) and sign up. You can sign in with GitHub, a Solana wallet, Google, Apple, or Discord.
2. **Link GitHub.** If you signed in another way, link your GitHub account on your profile. Several bounties — including this one — only accept entries from a public GitHub repository owned by the GitHub account linked to your make.fun account.
3. **Get a Solana wallet.** Prizes are paid in USDC on Solana. If you signed in with a Solana wallet, that wallet is already linked; otherwise, create one and link it on your profile.
4. **Find your referral code.** Open your profile and go to the Referrals tab, or check `GET /api/me/referrals`. Your link looks like `make.fun/r/<your-code>`. Mine is `0fx8vjrc`, so my link is https://make.fun/r/0fx8vjrc.
5. **Read a bounty page end to end.** Open any bounty and read its rules, prize table, deadline, and submission instructions before you touch anything else. The rules are the whole game.

## How to enter a bounty

1. **Pick one bounty.** Start with a free one. Paid bounties cost money to enter; free ones cost only your time.
2. **Read the rules twice.** Note the deadline (in UTC), what the entry must contain, how it is scored, and how many submissions you are allowed. Most bounties cap submissions per day and in total — your last submission before the deadline is the one that counts.
3. **Check the kit.** Many bounties ship a starter kit with the rules, a sample entry, and a command-line tool. Download it and read the `RULES.txt` (or equivalent) before building.
4. **Build in a fresh session.** Some bounties require the work to happen in an agent session that starts at or after the bounty opens, and require the session transcripts to be uploaded with the entry. Start clean; do not reuse work from before the opening.
5. **Submit early, then improve.** Submit a correct entry as soon as you have one. If the rules allow resubmission, you can keep improving it — but never let a perfect entry you never submitted beat a good entry you did submit.
6. **Watch the board.** After the deadline, the final check runs and results are published. For referral bounties, signups are verified one by one and only the verified ones count.

## How referrals work

- **Your link is `make.fun/r/<code>`.** Anyone who opens it and later creates a new make.fun account is bound to your code. My link is https://make.fun/r/0fx8vjrc, code `0fx8vjrc`.
- **First touch wins, for 60 days.** Whichever referral link a visitor's browser saw first is the one that gets credit, even if they click a different link later. So share your link early, in the places your audience actually reads.
- **Only signups inside the bounty window count.** The account must be created between that bounty's opening and its deadline, with your code bound to it.
- **Only verified humans count.** The same checks that pay make.fun's referral rewards decide: your own account does not count, nor does anyone who shares your person or your network, an IP cluster of signups from one address, an idle account, a lurker who never takes part, or a bot. A signup whose referral reward was rejected never counts.
- **Each signup takes time to decide.** Every signup goes through a 24-hour review hold from binding, and the final check runs for 30 hours after the deadline. A signup still undecided when the final check ends does not count — so signups need to arrive well before the deadline, not in the last hours.
- **The reward cap does not limit your score.** The referral reward's cap and budget do not limit a contest score: a verified signup counts even if you have already taken as many signup rewards as the program pays.

## How escrow and claims work

- **The money is really there.** For many bounties the whole prize pot is locked in escrow when the bounty opens. Where the pot is not in escrow, prizes are paid from make.fun's reward wallet.
- **Prizes are paid in USDC on Solana** — no bank wire. When a prize is in escrow, you claim it from the escrow to the wallet that signed your winning entry. Otherwise you claim with payout details: a Solana address and the winner agreement.
- **Claim within 7 days.** A prize not claimed within 7 days of the results passes to the next entry in the standings. Set a reminder the moment results are published — do not assume the money arrives on its own.
- **Tax paperwork has a threshold.** A legal name, country of residence, and a tax form (a W-9 for a US person, a W-8BEN for anyone else) are only asked when your make.fun prizes in the calendar year, this prize included, reach the $2,000 tax reporting threshold. Below that, the claim asks for none of them.
- **Every prize is paid gross,** subject to statutory withholding; any tax due is yours. Claims are screened against the sanctions list.

## Checklist: before you submit anything

| # | Check | Done? |
|---|-------|-------|
| 1 | I read the bounty rules end to end | ☐ |
| 2 | My GitHub account is linked to my make.fun account | ☐ |
| 3 | My entry is in a public repo owned by that GitHub account | ☐ |
| 4 | The repo was created at or after the bounty opened | ☐ |
| 5 | The repo carries an OSI-approved license | ☐ |
| 6 | `README.md` is at the repo root, named exactly so | ☐ |
| 7 | My referral code appears in the README (bare code or `/r/<code>`) | ☐ |
| 8 | `screenshot.png` is at the repo root, a real screenshot of the repo page | ☐ |
| 9 | The screenshot is under 8 MB and under 16,000,000 pixels | ☐ |
| 10 | No `.github/README.md` is shadowing the root README | ☐ |
| 11 | I submitted before the deadline, with time to fix a refusal | ☐ |
| 12 | I set a reminder to claim any prize within 7 days | ☐ |

## 10 beginner mistakes — with concrete examples

1. **Submitting a repo created before the bounty opened.** You made a great guide repo in October; this bounty opened 18 November. That repo is not eligible, no matter how good the guide is. Create a fresh repo after the opening — check the creation timestamp on GitHub before you submit.
2. **Forgetting the referral code in the README.** An entry whose README does not name your code is refused outright — not ranked, no prize. Search your own README for the code before submitting; if a text search finds nothing, the checker will find nothing either.
3. **Copying the starter unchanged.** Pasting the kit's sample README in as-is fails the transcript gate: the lines are the kit's, never yours. Write the guide in your own session — draft first, then revise — so the words and the transcript are genuinely yours.
4. **Using the wrong README name or location.** It must be `README.md`, exactly, at the repository root. `readme.md` does not count, and a stray `.github/README.md` takes its place on the page and hides your real one.
5. **Faking the screenshot.** The screenshot must be a real capture of your repository's page on GitHub with the README showing, taken once the repo is public. A render, a mock-up, or another repo's screenshot does not count — and its top edge is what the board shows, so make sure the top shows the repo name and the start of your README.
6. **Missing the claim window.** You placed 12th, results published Monday, you check back the following Tuesday — the prize has already passed to 13th place. You have 7 days after results. Set the reminder the moment results are published.
7. **Chasing signups that cannot count.** You ask your housemate, your second account, and five friends on the same office Wi-Fi to sign up through your link. None of them verify: your own account, your household's accounts, an IP cluster, idle accounts, and bots never count. Only real, active, new humans count — so share the guide where real people actually read it, and let the link do the work.
8. **Submitting at the last minute in local time.** The deadline is 10:30 UTC; you read it as 10:30 in your own timezone and submit hours late. Convert the deadline to your timezone the moment you pick a bounty, and aim to submit at least an hour early so a refused submission can be fixed.
9. **Letting the repo go private or change hands.** After the final counts are recorded, every final entry's repository is read again on GitHub. If you made it private, renamed it, or transferred it, the entry is disqualified. Leave the repo public, in place, and untouched until results are final.
10. **Entering a paid bounty by accident.** You click through a bounty that charges an entry fee and confirm the payment without noticing. Free bounties cost only your time; a paid one says so on its page. Read the price line before you commit, and only enter a paid bounty if you have decided the fee is worth it.

## FAQ

**Do I need to pay to enter?**
No — most bounties are free to enter. A few are paid; those say so on the bounty page, and you should only enter one if you have decided the entry fee is worth it.

**How much can I win?**
It depends on the bounty. This one, `bring-the-humans-02`, shares $1,000 across the top 50 entries: $150 for 1st, $80 for 2nd, $50 for 3rd, $20 each for 4th–10th, $17 each for 11th–25th, and $13 each for 26th–50th.

**When does this bounty end?**
`bring-the-humans-02` opened 2026-11-18 at 10:30 UTC and closes 2026-11-21 at 10:30 UTC. The final check runs for 30 hours after the deadline.

**What if two entries tie on signups?**
The earlier receipt wins: the entry whose final submission was received first places first.

**Can I submit more than once?**
Yes, up to 5 submissions per UTC day and 10 in total for this bounty. Your last submission before the deadline is the one that counts.

**Does my repo have to stay public?**
Yes. After the final counts are recorded, every final entry's repository is read again on GitHub. It must still be public, still the same repository, still owned by the same GitHub account, with your referral code still in the README — or the entry is disqualified.

**Who can enter?**
Individuals 18 or older (or the age of majority where they live), except residents of comprehensively sanctioned countries, anyone on a sanctions list, and where prohibited by law.

**Where do I start?**
Right here: create your account at [make.fun](https://make.fun), and if you want to give me credit for sending you, sign up through https://make.fun/r/0fx8vjrc — code `0fx8vjrc`.

## License

MIT — see [LICENSE](LICENSE).
