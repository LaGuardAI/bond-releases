# Installing Bond on macOS

Bond is a local-first desktop app. It runs on macOS 13 (Ventura) or
later, on both Apple silicon and Intel Macs.

## 1. Download

Download the disk image for your Mac from the
[releases page](https://github.com/LaGuardAI/bond-releases/releases):

- **Apple silicon (M1/M2/M3/M4):** `Bond-<version>-arm64.dmg`
- **Intel:** `Bond-<version>-x64.dmg`

Not sure which you have? Apple menu →  **About This Mac**. "Apple M…"
means Apple silicon; "Intel" means Intel.

## 2. Install

Open the `.dmg`, then drag the **Bond** icon into your **Applications**
folder. Eject the disk image and launch Bond from Applications.

Bond is signed with an Apple Developer ID and notarized by Apple, so it
opens without a Gatekeeper warning. macOS shows **Yoram Golandsky** as
the verified developer.

## 3. First launch

On first launch you'll be guided through setup — your workspace, an AI
provider key, and your license code. See [First run](first-run.md) for
the short version, or the full [Quickstart](https://ai-bond.dev/quickstart/)
for the walkthrough with screenshots.

---

### If macOS blocks the app

If you see "Bond can't be opened because Apple cannot check it for
malicious software," you most likely have an incomplete or older
download. Re-download the current `.dmg` from the
[releases page](https://github.com/LaGuardAI/bond-releases/releases). If
it persists, open **System Settings → Privacy & Security**, scroll to
the Bond notice, and click **Open Anyway** — then email
[support@ai-bond.dev](mailto:support@ai-bond.dev) so we can look into it.

### Updating

Bond checks for updates on launch and installs them the next time you
quit and relaunch. To check manually: **Settings → Advanced → About →
Check for updates**. Your workspaces, conversations, memories, and API
keys are preserved across updates.

---

Stuck? Email [support@ai-bond.dev](mailto:support@ai-bond.dev).
