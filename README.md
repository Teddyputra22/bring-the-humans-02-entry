# Build and enter your first make.fun bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/{{GITHUB_OWNER}}/{{REPOSITORY}}/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/{{GITHUB_OWNER}}/{{REPOSITORY}}/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**New to make.fun? Open [https://make.fun/r/q431793e](https://make.fun/r/q431793e) before creating your account to start with this guide’s referral link.**

Referral code: q431793e · Guide by @teddyputra22

make.fun hosts competitions for people building with AI coding agents. A bounty gives you a brief, a deadline, a scoring method, and a prize schedule. You steer the project, your agent helps build it, and eligible winners can claim USDC on Solana. Most bounties are free to enter; check the bounty page for any fee and budget for your own model usage.

## Before you start: a 10-minute checklist

Spend ten minutes deciding whether an entry fits your time and tools:

- **Minutes 0–2: find an open bounty.** Read its deadline and timezone. Put the cutoff on your calendar and choose a personal submission target at least an hour earlier.
- **Minutes 2–4: define the smallest complete entry.** Write down every required deliverable and the scoring criteria. Choose a brief you can finish with the time and model budget you have.
- **Minutes 4–6: check access.** Confirm you can sign in, use the required agent, and access the kit. For a GitHub entry, confirm which linked account will own the repository.
- **Minutes 6–8: read the kit rules.** Note any required initialization step, recording requirement, file names, license, and submission format before you start building.
- **Minutes 8–10: plan the finish.** Reserve time for testing, screenshots if required, transcript collection, and a submission receipt. If those steps do not fit, choose a smaller brief.

Keep that deliverable list beside your agent session. It gives you a concrete definition of “finished” when extra features start to look tempting.

## Get your account ready

1. Open [the signup link](https://make.fun/r/q431793e) and choose **Sign in**. You can use GitHub, Google, Apple, Discord, or a Solana wallet. Wallet sign-in signs a message and sends no transaction.
2. Open your profile from your avatar. Link the GitHub account that will own your entry repo if you used a different sign-in method. Set up a linked Solana wallet if the bounty calls for it.
3. If you're using the kit CLI, install Node.js 22 and run the following from the unpacked kit:

   ```sh
   node cli/makefun.mjs login --origin https://make.fun
   ```

   While signed into your account, open the approval link the CLI prints and match the code before approving. This pairs the CLI with your account; on first use it can create and link a local Solana keypair. Keep that file out of Git.

## Choose a brief you can finish

Browse [the bounty board](https://make.fun/) for open competitions. Read the scoring and the submission requirements before looking at the prize: a great demo can still miss a required file or use the wrong submission format. Check the deadline, what tools or accounts you need, and how the leaderboard breaks ties. Set aside time before the cutoff to read submission errors, fix missing requirements, and retry within the allowed attempt limit.

Download the kit from the bounty's entry form, unpack it, and start with its `RULES.txt`. The kit has the CLI, any starter files and any data the competition provides. If the rules give a local grading command, use it on the practice data to see what the grader measures. Some bounties score outcomes that you can't simulate locally.

## Build with a record of the work

Start a fresh session in a coding agent that records its work, such as Codex, Claude Code, or Cursor, after the bounty opens. Check the rules for setup commands you need to run before writing. If the entry uses GitHub, use a new repository under your linked account and include an approved open source license such as MIT.

Give the agent the rules, ask it to draft the entry, and review its work with it. Ask it to compare the draft against each requirement, fix omissions, and explain the changes in the recorded session. Review the revised files yourself before submitting. make.fun uses the transcripts to connect the submitted files to the work the agent actually did. Treat any supplied starter as scaffolding and keep the session logs.

## Send the exact version you want judged

For a GitHub entry, publish the repo, push the finished work, and copy the full commit SHA. If the rules require a screenshot of the public page, capture it after the README is visible on GitHub and commit and push it before choosing the SHA. Some other bounties accept a source bundle; follow the format specified in your kit.

Use the kit to collect your agent transcripts and the required run record. The record describes your original prompt, harness, model, setup and tools used. The kit can tell you what information is missing. Run the kit's preflight checks if available, then open the bounty's **Enter** form and send your public repo URL, commit SHA, and transcript upload. Follow the page's signing instructions if the reward is held in escrow.

A submission captures the chosen commit. Pushing again does not update that snapshot. Watch the entry status for a receipt and any failed checks. If you need to correct something, submit the new commit within the deadline and the bounty's attempt limits.

For a concrete example, [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) accepts a public GitHub repo created after the bounty opens. Put the tutorial and referral code in the root `README.md`, keep the three live badges with your actual repo owner and name, and add a real capture of the published repo page as `screenshot.png`. Frame it so the repo name and opening of the guide are visible at the top. Set the repo's **About** website to the bounty page and add the `makefun` topic. This bounty counts your last submission with a receipt before the deadline and rechecks the public repo and the referral code on its default branch after the contest.

## Worked example: a first entry in one afternoon

Imagine Maya is new to make.fun and has three hours available. This is an illustrative schedule, not a claim about a currently open bounty or its deadline.

1. **13:00 — choose the smallest open brief.** Maya compares two open bounties: one needs a deployed app, while the other asks for a short beginner tutorial and supporting files. She chooses the tutorial because she can complete every required deliverable. Its hypothetical deadline is 17:00, so she sets a personal submission target of 15:30.
2. **13:10 — turn the rules into a task list.** She downloads that bounty’s kit, reads `RULES.txt`, confirms the required setup and recording steps, and starts a recorded agent session. Her prompt is specific: “Draft a beginner tutorial that covers these requirements. Include one runnable example and list anything you cannot verify.” She supplies the actual rules with the prompt.
3. **13:30 — build and review with the agent.** Maya tries the tutorial’s instructions herself. When a setup step is missing, she asks the agent to revise it and simplify the example. She compares the result against her deliverable list, checks the required license and supporting files, and keeps the session transcript.
4. **14:45 — prepare the version to submit.** For this hypothetical GitHub entry, she publishes the required files, captures the public page if the rules request it, and pushes the final commit. She copies that commit’s full SHA, collects the required transcript and run record, and follows the kit’s submission instructions.
5. **15:15 — submit and confirm receipt.** Maya enters the repository URL and exact SHA with the required uploads. She reads the returned status and confirms a receipt before 17:00. If the submission reports a missing file, her buffer leaves time to fix it and submit a new commit within the attempt limit. She keeps the receipt alongside the submitted SHA.

Maya’s first entry is complete when the required work has a receipt before the cutoff. Extra features can wait; a larger scope is only useful if it still leaves time to finish and submit.

## Claim a prize after results

If you place, open your profile when the result becomes claimable and follow the claim instructions. The CLI's `status` command can also show a claim ID and next steps. Escrow claims use the linked Solana wallet that signed the entry; allow for the network fee and complete the requested eligibility steps. If the bounty uses a manual payout, follow the payout details it asks for. Check the claim deadline as soon as you get notified.

## Share your own referral link

Find your code, link and reward activity in **Profile → Referrals**. make.fun may pay referral rewards for verified new users who take part and a share of their eligible winnings for a limited period. That share comes from make.fun, so your friend's prize stays whole. Rewards go through review; sending a link or getting a click does not earn a payout.

The first referral code a browser sees takes priority for 60 days. For this bounty, what matters is when the new account is created: it must sign up during the contest with your code attached and pass verification. The leaderboard ranks verified signups; if two entries have the same count, the earlier final receipt wins the tie.

Ready to make your first entry? Open [https://make.fun/r/q431793e](https://make.fun/r/q431793e), then create your account and choose an open bounty using the checklist above. If signup asks for a referral code, enter q431793e. Use the link before signing up; a later visit does not replace the first referral code already attached to your browser. For more details, see [how make.fun works](https://make.fun/how-it-works) and [the guide for coding agents](https://make.fun/skill.md).
