### Hi there

I build small, dependable developer tools and AI agent tooling. Everything below is open source, tested in CI, and runs **locally with no network calls and no runtime dependencies** unless stated otherwise.

## Command-line tools

| Tool | What it does | Install |
|---|---|---|
| [**fitfix**](https://github.com/Emincanozen/fitfix) | Repairs corrupted or truncated Garmin `.FIT` activity files: header, CRC, cut-off records, missing lap/session messages. | `npm install -g fitfix` |
| [**pstpeek**](https://github.com/Emincanozen/pstpeek) | Opens Outlook `.pst`, `.ost` and `.msg` files without Outlook. Browse, search, export to EML, mbox or JSON. *(alpha)* | `npm install -g pstpeek` |
| [**ownerskit**](https://github.com/Emincanozen/ownerskit) | A faithful CODEOWNERS parser, matcher and linter: who owns this file, which files have no owner. | `npm install -g ownerskit` |
| [**docker-credential-gh**](https://github.com/Emincanozen/docker-credential-gh) | Docker credential helper for `ghcr.io` that reuses your GitHub CLI session. No personal access token to create or store. | `npm install -g docker-credential-gh` |
| [**cardsafe**](https://github.com/Emincanozen/cardsafe) | Verified offload of camera memory cards: copy to several drives, re-read every copy, keep a checksum manifest. *(early)* | `pip install cardsafe` |

## AI agent tooling

- [**Orchestrator-Control-Room**](https://github.com/Emincanozen/Orchestrator-Control-Room): a local-first control room for Windows that runs Claude Code, Codex CLI and Antigravity side by side in isolated git worktrees, verifies their work, and shows it live.
- [**apex-code-architect**](https://github.com/Emincanozen/apex-code-architect) and [**counterfactual-premortem-oracle**](https://github.com/Emincanozen/counterfactual-premortem-oracle): agent skills for blast-radius analysis and pre-execution failure simulation.
- [**stage-career-studio**](https://github.com/Emincanozen/stage-career-studio): a privacy-first skill and toolkit for internship hunting.
- [**aether-agent-suite**](https://github.com/Emincanozen/aether-agent-suite): a multi-agent sales and marketing suite built on Claude, with one repository per agent.

## Apps and platforms

[plateau-100-games](https://github.com/Emincanozen/plateau-100-games) (100 offline games, Expo) · [wikibulya](https://github.com/Emincanozen/wikibulya) (daily Wikipedia guessing game) · [tiktok-live-arena](https://github.com/Emincanozen/tiktok-live-arena) (TikTok LIVE game overlays) · [force-structuree-lms](https://github.com/Emincanozen/force-structuree-lms) (learning platform) · [avisio-nfc-platform](https://github.com/Emincanozen/avisio-nfc-platform) (NFC review platform)

## How I work

Small scope, honest READMEs (limitations and "not validated yet" are stated up front), tests and CI from the first commit, and security reports welcome through each repository's `SECURITY.md`.

Issues and pull requests are welcome on every project above.
