
Create a Public GitHub Contributions for talent protocol wct reward 
ChatGPT said:

Thought for 15s
Great — here’s a ready-to-use, step-by-step playbook to create public GitHub contributions that will be eligible for Talent Protocol / WalletConnect WCT builder rewards. I’ll cover what counts, how to prepare your accounts, practical contribution ideas, a checklist so your work actually shows up, and copy-paste PR / commit templates you can use immediately.

I searched Talent Protocol and WalletConnect docs to make sure steps match their reward checks. Key rules: Talent Protocol counts verified contributions to public crypto repositories and you must connect your GitHub to your Talent profile; WalletConnect’s WCT eligibility also rewards GitHub contributors who register. 
Talent Protocol
+2
Talent Protocol
+2

1) Quick summary (what you must do)
Make public, meaningful contributions (PRs, merged PRs, issues, docs, tests) to public crypto / web3 repos. 
Talent Protocol

Ensure your Git commit email is added to your GitHub account so contributions link to your profile. (If commits don’t link, GitHub won’t show them.) 
GitHub Docs

Connect your GitHub account to your Talent Protocol profile (so Talent can verify). 
Talent Protocol

If targeting WalletConnect WCT, register/connect on WalletConnect’s airdrop portal and link GitHub if asked. 
WalletConnect

2) What types of GitHub activity typically count
(Use these to prioritize your work.)

Merged Pull Requests (code, bugfixes, small features) — strongest signal.

Meaningful commits in public repos (especially those merged to main/master).

Issues opened with reproducible bug reports or well-scoped feature requests.

Documentation contributions (readmes, guides, API docs) for crypto projects.

Tests / CI fixes / security fixes — high impact and often prioritized.
Talent Protocol explicitly uses “verified contributions to public crypto repositories” as part of Builder Rewards. 
Talent Protocol

3) Step-by-step checklist (do this before and after contributing)
Before you start:

 Use a public GitHub account (not private repos).

 Confirm the commit email you’ll use locally is added to your GitHub account: git config user.email "you@example.com" and add that email to GitHub under Settings → Emails. (GitHub will retroactively credit commits once the email is attached.) 
GitHub Docs

 Link your GitHub account in Talent Protocol: go to your Talent profile → connect GitHub. (Talent ingests GitHub data to compute Builder Score.) 
Talent Protocol

 If pursuing WCT, register / connect at WalletConnect airdrop page and link GitHub if available. 
WalletConnect

When making a contribution:

 Pick an open issue labelled good first issue, help wanted, or docs in a crypto/web3 repo.

 Fork → branch with a descriptive name (fix/eth-address-parsing, feat/readme-clarity) → implement → push → open PR.

 In PR description explain the problem, your change, testing steps, and include screenshots or test logs if relevant.

After your PR:

 Ensure PR gets review / approval / merge — merged PRs weigh more.

 Check GitHub profile’s contributions graph (should show contribution). If missing, confirm commit email.

 Wait for Talent Protocol to ingest activity (they periodically pull GitHub activity into Builder Score). If you connected Talent, your contribution should appear in your Builder Score history. 
Talent Protocol

4) Repo selection — where to contribute (examples)
Contribute to public crypto / infra / tooling repos — these are the projects Talent/WalletConnect expect to see:

WalletConnect repos / SDKs (connectors, SDKs) — connects directly to WCT mission. (see WalletConnect blog/airdrop pages). 
WalletConnect

Ethers.js / Web3.js / Web3-React / wagmi — widely used EVM libraries.

Hardhat, Foundry, Truffle — tooling that powers dev workflows.

Popular ecosystem repos: MetaMask, OpenZeppelin contracts, ENS, The Graph, IPFS implementations.

Smaller defi projects and SDKs you actually use — even docs/bugfix help.

(If you want, I can produce 8–12 specific active repo links tailored to your skill level; tell me whether you prefer documentation work or code fixes and I’ll pick repos.)

5) Ready-to-use PR & commit templates
Use these exact templates when opening PRs — they make it fast for maintainers to review and merged (and look professional for Talent verification).

Branch name pattern (pick one):
fix/<short-desc> or feat/<short-desc> or docs/<short-desc>

Commit message (conventional style):

feat(readme): add quick start example for WonkBase token

- add usage snippet
- update install instructions
Closes #42
Pull Request Title (short):

fix(address): handle 0x-prefixed ENS resolver addresses
Pull Request Body (copy & paste and edit):

## What
Short description of the change (1-2 sentences).

## Why
Explain the bug/feature, and why it's needed.

## How I tested
- Local tests: `npm test` (describe)
- Manual test steps: 1) ..., 2) ...
- Screenshots/logs (if any) attached below

## Related
- Fixes / Closes issue #<number>
- Related PRs: #<number>

## Notes for maintainers
Anything the reviewer should know (edge cases, migration steps, backwards compatibility).
Issue template to open (if you file an issue first):

### Describe the bug / feature
Concise description

### Reproduction steps
1. Steps to reproduce
2. Expected behavior
3. Actual behavior

### Environment
- OS:
- Node/npm version:
- Repo version / commit:

### Additional context / logs
 paste logs, stack traces, or screenshots here
6) Low-effort high-impact contribution ideas (you can do these today)
Docs improvements — fix typos, add code examples, clarify setup. (Easy wins; fast merges.)

Add tests for a reported failing edge case in an open issue.

Type fixes / small lint fixes in libraries (search for help wanted).

Examples / snippets: add a small examples/ folder demonstrating wallet connect + sign flow — many repos want better examples.

Security/Dependency updates — open PR that upgrades a pinned dependency and run CI.

Improve error messages — change a throw new Error('bad') to a clear message + add test.
