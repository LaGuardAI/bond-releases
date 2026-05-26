<p align="center">
  <img src="https://ai-bond.dev/bond-logo.svg" alt="Bond" width="96" />
</p>

<h1 align="center">Bond</h1>

<p align="center"><em>Where your thinking continues.</em></p>

<p align="center">
  <a href="https://github.com/LaGuardAI/bond-releases/releases/latest"><b>Download</b></a> ·
  <a href="https://ai-bond.dev/quickstart/">Quickstart</a> ·
  <a href="https://ai-bond.dev/">Website</a>
</p>

<p align="center">
  <a href="https://github.com/LaGuardAI/bond-releases/releases/latest"><img src="https://img.shields.io/github/v/release/LaGuardAI/bond-releases?label=latest&color=1f3a5f" alt="Latest release" /></a>
</p>

---

Bond is a local-first desktop app that turns your AI subscriptions into a
coordinated team of persistent specialists with shared, traceable project
memory. You bring your own provider keys, configure named teammates, and your
work — decisions, facts, context — accumulates across sessions instead of
scattering across chat tabs.

**Bond is in invite-only alpha.** You'll need a license key to activate. Got an
invite? Your key is in the email. Don't have one? You can buy a license at
[ai-bond.dev](https://ai-bond.dev/).

## Download

Get the latest build from the
[**Releases page**](https://github.com/LaGuardAI/bond-releases/releases/latest).

| Platform | File |
|---|---|
| Windows 10 or later | `Bond-<version>.exe` |
| macOS 13+ — Apple silicon (M1–M4) | `Bond-<version>-arm64.dmg` |
| macOS 13+ — Intel | `Bond-<version>-x64.dmg` |

Not sure which Mac you have? Apple menu →  **About This Mac**. "Apple M…" means
Apple silicon.

## Get started

The [**Quickstart**](https://ai-bond.dev/quickstart/) is the canonical guide —
install, license, first chat, and walkthrough videos for all six surfaces
(Ask Bond, Chat, Memory, Sync, Library, Meetings).

The short version: install → open Bond → paste your license key in
**Settings → License** → add at least one provider key (Anthropic, OpenAI,
Perplexity, or Gemini; stored locally on your machine) → setup builds your
first workspace and team.

## Install notes

A few things specific to alpha that aren't in the Quickstart:

**Windows.** Installers are Authenticode-signed from v1.4.51 onward; the UAC
prompt shows **Yoram Golandsky** as the publisher — that's expected, not a
warning. Only the earliest builds (v1.4.0–v1.4.3) were unsigned and tripped
SmartScreen.

**macOS.** Builds are signed with an Apple Developer ID and notarized, so they
open without a Gatekeeper warning — you'll see **Yoram Golandsky** as the
verified developer. If macOS ever blocks the app, re-download the current
`.dmg`; if it persists, open **System Settings → Privacy & Security → Open
Anyway**, then email support.

**Upgrading from a pre-v1.4.51 build.** Auto-update does **not** bridge
v1.4.3 → v1.4.51 — the release feed moved. Install v1.4.51 (or later) once
manually from the Releases page; auto-update resumes normally after that.

## Known limitations

Bond works, and it's early. Expect:

- **First sync is slow** — 30–60 seconds the first time. Normal; later syncs
  are faster.
- **Costs are yours** — you're using your own provider keys. Bond shows cost
  per teammate and per sync.
- **Voice needs an OpenAI key** — transcription uses Whisper; the mic button
  appears but won't work without one configured.
- **Branches are for short explorations** — no branch-from-branch, and
  @-mentions don't resolve while you're on a branch in this build.
- **Occasional sync hiccup** — if a sync's analysis can't be parsed, Bond
  retries once, then continues without injections for that sync rather than
  blocking you.

## Updating

Bond checks for updates on launch and installs them the next time you quit and
relaunch. Check manually at **Settings → Advanced → About**. Your workspaces,
conversations, memories, and keys are preserved across updates.

## Support

Email [support@ai-bond.dev](mailto:support@ai-bond.dev). Found a bug? Reply to
your invite email — we read everything. Discord and a public bug tracker are
coming.

---

Full documentation and walkthrough videos live at the
[**Quickstart**](https://ai-bond.dev/quickstart/). This page just gets you to
the download and flags what's specific to alpha.
