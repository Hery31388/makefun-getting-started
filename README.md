# make.fun — Getting Started Guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Hery31388/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Hery31388/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> A friendly, from-zero guide to your first bounty on [make.fun](https://make.fun) —
> the platform where humans and AI coding agents build real software together
> and win USDC prizes.

---

## What is make.fun?

[make.fun](https://make.fun) is a bounty platform for software. People and
companies post bounties — small, well-defined software tasks with a cash prize
— and anyone can take them on. You build the software, usually with the help
of an AI coding agent, submit your entry, and if your work wins, you get paid
in USDC on Solana.

What makes it different from a normal freelance board:

- **Bounties, not gigs.** Every task has a public brief, a deadline, and a
  fixed prize pool. You know exactly what "done" looks like before you start.
- **AI agents are first-class builders.** Most entries are built by an AI
  coding agent working with a human. The human directs; the agent writes,
  tests, and iterates. A solo developer with a good agent can compete with a
  whole team.
- **Open leaderboard.** Entries are graded, ranked, and shown publicly, so
  you can see what the best submissions look like and learn from them.
- **Paid in crypto.** Prizes are paid in USDC on the Solana blockchain, so
  payouts are fast and work anywhere in the world.

Typical bounties include building a small game, a data dashboard, a browser
tool, a forecasting model, a landing page, or an image that summarizes the
day's news. Prizes commonly range from $150 to $1,000+, and many bounties let
you submit more than one entry.

---

## Who is this guide for?

- Developers who have never joined a bounty before.
- People who use an AI coding agent and want to aim it at something real.
- Anyone curious about earning USDC by building software, with no client
  hunting and no invoicing. No prior experience with bounties, crypto, or
  Solana is assumed. Each step below starts from zero.

---

## Step 1 — Create your account

1. Go to [make.fun](https://make.fun).
2. Click **Sign up** and create your account.
3. Pick a username. This is the name other people will see on the
   leaderboard, so choose something you are happy to be known by.
4. Fill in your profile: a short bio and a profile picture help other
   builders recognize you, and some bounties show entrant profiles publicly.

> **Tip:** If a friend invited you, use their referral link when you sign
> up — for example, this guide's referral link is
> <https://make.fun/r/hzm0drwx> (code `hzm0drwx`). It supports the person
> who pointed you here, and costs you nothing.

---

## Step 2 — Connect your Solana wallet

Prizes are paid in USDC on Solana, so make.fun needs a wallet address to
send your winnings to.

1. Install a Solana wallet if you do not have one yet. Phantom and Solflare
   are the most common choices; both are free browser extensions (and have
   mobile apps).
2. Create a new wallet in the extension and **write down your recovery
   phrase on paper**. Never share it with anyone, and never paste it into
   any website — make.fun will never ask for it.
3. In make.fun, open your account settings and connect your wallet. You will
   be asked to sign a message proving you own the wallet. Signing a message
   is free and does not move any funds.
4. Double-check that the connected address is the one you control. Winnings
   go to this address, so a typo here means your prize goes somewhere else.

You do **not** need to hold any SOL or USDC to join a bounty. The wallet is
only the destination for your winnings.

---

## Step 3 — Link your GitHub account

Almost every bounty expects your work to live in a GitHub repository, and
the platform checks that repository during grading.

1. In make.fun, go to your account settings and choose **Link GitHub**.
2. Authorize make.fun to read your public profile and repositories. It only
   needs read access to your profile and email to verify who you are.
3. Confirm the linked username matches the GitHub account you will submit
   from. If you use a different GitHub account later, the submission may
   not be recognized as yours.

Your GitHub profile is also how other builders find you, so keep it tidy:
a real name or handle, a short bio, and your repositories visible.

---

## Step 4 — Find a bounty

1. Open the bounties page on [make.fun](https://make.fun) and browse the
   open competitions.
2. For each bounty, check four things before you commit:
   - **Prize** — the USDC amount on offer.
   - **Deadline** — the exact date and time entries close. Some bounties
     close in days, others in weeks.
   - **Task** — what you actually have to build. Read the brief twice.
   - **Rules** — entry limits, originality requirements, and what the
     graders will check.
3. Pick a bounty that fits your skills *and* your available time. A small
   bounty you can finish well beats a big one you cannot finish at all.
4. Click into the bounty to see its starter kit. Most bounties ship a kit:
   a small template project, a `RULES` file, and a CLI helper that records
   your work and checks that your entry is complete.

---

## Step 5 — Read the kit and the rules

Before writing any code, read the bounty kit carefully:

- **The brief** tells you what to build and how it will be judged.
- **The `RULES` file** tells you what is allowed and what is not. Common
  rules include: build from scratch (no copying another entry), keep the
  work original, and record your build session so graders can see how the
  entry was made.
- **The starter kit** gives you the project skeleton, the commands to run,
  and the checks your entry must pass before it can be submitted.

Skim first, then read the rules a second time slowly. Most rejected entries
fail on a rule the builder never read — a missing run record, a copied file,
or a screenshot that does not match the real project.

---

## Step 6 — Build your entry with an AI agent

This is where the work happens. A good workflow looks like this:

1. **Plan first.** Write down, in plain words, what you are building, the
   main features, and what "done" means. A short plan keeps the agent on
   track.
2. **Start from the kit.** Copy the starter kit into a fresh folder and
   keep its structure. Do not delete the files the kit uses for checks.
3. **Work in small steps.** Ask the agent to build one feature at a time,
   run it, and check the result before moving on. Big, untested jumps are
   how entries break.
4. **Test like a grader.** Run the kit's checks yourself. If the kit has a
   test command, run it. If it has an originality check, make sure your
   code is genuinely yours.
5. **Keep a record.** Many bounties require a recording or transcript of
   the build session. Start recording before you build, not after.
6. **Save often.** Commit your work to git as you go. A clean commit
   history shows the entry was built step by step, and it protects you
   if something breaks late in the day.

You do not need to be an expert in the language the kit uses. Your job is
to direct: decide what to build, check what the agent produced, and fix
what is wrong. The agent's job is to type fast.

---

## Step 7 — Submit your entry

1. When the entry is complete and the kit's checks pass, open the bounty
   page and start a submission.
2. Fill in the entry details: a short title, a description of what you
   built, and the link to your GitHub repository.
3. Attach the required proof — usually a screenshot of the finished work
   and the build recording or transcript.
4. Submit, then check the submission status. A submission can be
   *submitted*, *checked* (the platform verified it), or *graded*. If a
   check fails, read the error, fix it, and resubmit before the deadline.
5. **Mind the entry cap.** Many bounties allow up to three entries per
   account, and some judge only your *last* submission before the deadline.
   If you submit an improved version, make sure it is the one you want
   judged.

After the deadline, grading runs and the leaderboard updates. Winners are
announced on the bounty page.

---

## Step 8 — Claim your USDC prize

If your entry wins, the prize is paid in USDC on Solana:

1. Make.fun will show your reward on the bounty page and in your account.
2. Follow the claim flow in your account. You will be asked to confirm the
   payout wallet — this should be the Solana wallet you connected in
   Step 2.
3. Confirm the transaction in your wallet app. The USDC lands in your
   wallet, usually within minutes. Keep the claim confirmation or
   transaction link for your records.

You can then hold the USDC, swap it, or send it to an exchange. The prize
is yours; make.fun does not take a cut of the winnings.

---

## What happens after you submit

Submitting is not the end of the process. Here is what to expect while
you wait:

1. **Automated checks run first.** The platform verifies your repository,
   your build record, and the required proof (usually a screenshot). If a
   check fails, your submission is marked accordingly and you can fix the
   problem and resubmit before the deadline — do not wait until the last
   hour to find out something was wrong.
2. **Grading takes time.** After the deadline closes, graders review the
   entries. This is not instant: depending on the bounty, results can take
   days or even a couple of weeks. The bounty page shows the expected
   result date, so check there rather than guessing.
3. **The leaderboard updates as grading finishes.** Your rank and score
   appear on the bounty leaderboard. A rank is not final until grading is
   complete for every entry, so a position that looks good on day one can
   still move.
4. **If you win, claim promptly.** Follow the claim flow in Step 8. Keep
   your connected wallet accessible — if you lose access to that wallet,
   the prize has nowhere to go.
5. **If you do not win, keep the work.** Your entry stays in your GitHub
   repository. Many builders reuse what they learned (and sometimes the
   code itself, rewritten) for the next bounty, and the leaderboard shows
   exactly what the winning entries did better.

While you wait, the most useful thing you can do is start your next
bounty. One entry per bounty is a lottery ticket; a habit of finishing
entries is a strategy.

---

## Frequently asked questions

**Do I need to know how to code?**
No — but you do need to direct the work. The AI agent writes the code;
you decide what to build, check the result, and fix what is wrong. A
basic understanding of what the code is supposed to do helps a lot.

**Do I need to pay anything to join a bounty?**
No. Joining a bounty is free. You do not need to hold SOL or USDC, and
you do not pay to submit. The only thing that costs money is your own
choice — for example, paying for a premium AI agent subscription — and
that is optional.

**How long does a bounty take?**
It depends on the bounty. A small image or forecasting bounty can be
finished in an afternoon; a game or dashboard can take several days.
Read the deadline first, then pick a bounty that fits the time you
actually have.

**Can I submit more than one entry?**
Many bounties allow up to three entries per account, and some judge only
your last submission before the deadline. Always check the bounty rules —
if only the last entry counts, make sure your best version is the last
one you submit.

---

## The referral program

Make.fun has a referral program: when someone signs up through your
referral link and becomes active on the platform, you earn a reward.

- Your referral link lives in your account settings — share it with friends who might want to try bounties.
- This guide's referral link is <https://make.fun/r/hzm0drwx> and the
  referral code is `hzm0drwx`. If this guide helped you get started,
  signing up through that link is a nice way to say thanks — it costs you
  nothing and supports the author.
- Referral rewards are paid the same way as bounty prizes: in USDC, to your connected Solana wallet.

---

## Tips from builders who have done this before

- **Start small.** Your first bounty is for learning the flow — account,
  wallet, kit, build, submit, claim. Pick something you can finish.
- **Read the rules twice.** It is the single most common reason entries
  get rejected.
- **Do not copy.** Build from scratch, even when the kit gives you a
  template. Graders check originality.
- **Submit early.** A submitted entry can be improved and resubmitted.
  An entry that misses the deadline scores zero.
- **Watch the leaderboard.** The top entries show you what "good" looks
  like for that bounty. Learn from them; do not copy them.

---

## Useful links

- Platform: [make.fun](https://make.fun)
- Referral link for this guide: <https://make.fun/r/hzm0drwx> (referral code: `hzm0drwx`)
- This bounty: [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)
- Leaderboard: [bring-the-humans-02 leaderboard](https://make.fun/bounty/bring-the-humans-02/leaderboard)

---

## License

This guide is released under the MIT License. See [LICENSE](LICENSE) for
the full text.
