# Installing Bond on Windows

Bond is a local-first desktop app. It runs on Windows 10 or later.

## 1. Download

Download the latest Bond installer (`Bond-<version>.exe`) from the
[releases page](https://github.com/LaGuardAI/bond-releases/releases).

## 2. Run the installer

Open the `.exe` from your Downloads folder. Windows shows a User Account
Control (UAC) prompt — this is expected. The publisher reads
**Yoram Golandsky**. Bond's installers are Authenticode-signed (v1.4.51
and later), so you should not see a SmartScreen "unknown publisher"
warning. Click through and Bond installs.

## 3. First launch

On first launch you'll be guided through setup — your workspace, an AI
provider key, and your license code. See [First run](first-run.md) for
the short version, or the full [Quickstart](https://ai-bond.dev/quickstart/)
for the walkthrough with screenshots.

---

### If you see a SmartScreen warning

Only the earliest alpha builds (v1.4.0–v1.4.3) were unsigned and
triggered SmartScreen. If you somehow have one of those, download
v1.4.51 or later from the
[releases page](https://github.com/LaGuardAI/bond-releases/releases) and
install it once manually — auto-update resumes from there. Current
releases are signed.

### Updating

Bond checks for updates on launch and installs them the next time you
quit and relaunch. To check manually: **Settings → Advanced → About →
Check for updates**. Your workspaces, conversations, memories, and API
keys are preserved across updates.

---

Stuck? Email [support@ai-bond.dev](mailto:support@ai-bond.dev).
