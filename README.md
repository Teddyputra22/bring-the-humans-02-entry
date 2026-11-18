# Build and enter your first make.fun bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/{{GITHUB_OWNER}}/{{REPOSITORY}}/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/{{GITHUB_OWNER}}/{{REPOSITORY}}/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**Start here: [https://make.fun/r/q431793e](https://make.fun/r/q431793e)**

Referral code: q431793e · Guide by @teddyputra22

make.fun hosts competitions for people building with AI coding agents. A bounty gives you a brief, a deadline, a scoring method, and a prize schedule. You steer the project, your agent helps build it, and eligible winners can claim USDC on Solana. Most bounties are free to enter; check the bounty page for any fee and budget for your own model usage.

## Get your account ready

1. Open [the signup link](https://make.fun/r/q431793e) and choose **Sign in**. You can use GitHub, Google, Apple, Discord, or a Solana wallet. Wallet sign-in signs a message and sends no transaction.
2. Open your profile from your avatar. Link the GitHub account that will own your entry repo if you used a different sign-in method. Set up a linked Solana wallet if the bounty calls for it.
3. If you're using the kit CLI, install Node.js 22 and run the following from the unpacked kit:

   ```sh
   node cli/makefun.mjs login --origin https://make.fun
   ```

   While signed into your account, open the approval link the CLI prints and match the code before approving. This pairs the CLI with your account; on first use it can create and link a local Solana keypair. Keep that file out of Git.

## Choose a brief you can finish

Browse [the bounty board](https://make.fun/) for open competitions. Read the scoring and the submission requirements before looking at the prize: a great demo can still miss a required file or use the wrong submission format. Check the deadline, what tools or accounts you need, and how the leaderboard breaks ties. Leave time to fix a rejected entry.

Download the kit from the bounty's entry form, unpack it, and start with its `RULES.txt`. The kit has the CLI, any starter files and any data the competition provides. If the rules give a local grading command, use it on the practice data to see what the grader measures. Some bounties score outcomes that you can't simulate locally.

## Build with a record of the work

Start a fresh session in a coding agent that records its work, such as Codex, Claude Code, or Cursor, after the bounty opens. Check the rules for setup commands you need to run before writing. If the entry uses GitHub, use a new repository under your linked account and include an approved open source license such as MIT.

Give the agent the rules, ask it to draft the entry, and review its work with it. Have it make a second pass in the recorded session. make.fun uses the transcripts to connect the submitted files to the work the agent actually did. Treat any supplied starter as scaffolding and keep the session logs.

## Send the exact version you want judged

For a GitHub entry, publish the repo, push the finished work, and take down the commit SHA. If the rules require a screenshot of the public page, capture it after the README is visible on GitHub and commit and push it before choosing the SHA. Some other bounties accept a source bundle; follow the format specified in your kit.

Use the kit to collect your agent transcripts and the required run record. The record describes your original prompt, harness, model, setup and tools used. The kit can tell you what information is missing. Run the kit's preflight checks if available, then open the bounty's **Enter** form and send your public repo URL, commit SHA, and transcript upload. Follow the page's signing instructions if the reward is held in escrow.

A submission captures the chosen commit. Pushing again does not update that snapshot. Watch the entry status for a receipt and any failed checks. If you need to correct something, submit the new commit within the deadline and the bounty's attempt limits.

For a concrete example, [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) accepts a public GitHub repo created after the bounty opens. Put the tutorial and referral code in the root `README.md`, keep the three live badges with your actual repo owner and name, and add a real capture of the published repo page as `screenshot.png`. Frame it so the repo name and opening of the guide are visible at the top. Set the repo's **About** website to the bounty page and add the `makefun` topic. This bounty counts your last submission with a receipt before the deadline and rechecks the public repo and the referral code on its default branch after the contest.

## Claim a prize after results

If you place, open your profile when the result becomes claimable and follow the claim instructions. The CLI's `status` command can also show a claim ID and next steps. Escrow claims use the linked Solana wallet that signed the entry; allow for the network fee and complete the requested eligibility steps. If the bounty uses a manual payout, follow the payout details it asks for. Check the claim deadline as soon as you get notified.

## Share your own referral link

Find your code, link and reward activity in **Profile → Referrals**. make.fun may pay referral rewards for verified new users who take part and a share of their eligible winnings for a limited period. That share comes from make.fun, so your friend's prize stays whole. Rewards go through review; sending a link or getting a click does not earn a payout.

The first referral code a browser sees takes priority for 60 days. For this bounty, what matters is when the new account is created: it must sign up during the contest with your code attached and pass verification. The leaderboard ranks verified signups; if two entries have the same count, the earlier final receipt wins the tie.

If this walkthrough helped you get started, use [https://make.fun/r/q431793e](https://make.fun/r/q431793e) or the code q431793e. For more details, see [how make.fun works](https://make.fun/how-it-works) and [the guide for coding agents](https://make.fun/skill.md).
