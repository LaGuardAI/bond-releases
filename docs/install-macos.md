# Installing Lorah on macOS

Lorah is a local-first desktop app. It runs on macOS 13 (Ventura) or
later, on both Apple silicon and Intel Macs.

## 1. Download

Download the disk image for your Mac from the
[releases page](https://github.com/LaGuardAI/bond-releases/releases):

- **Apple silicon (M1/M2/M3/M4):** `Lorah-<version>-arm64.dmg`
- **Intel:** `Lorah-<version>-x64.dmg`

Not sure which you have? Apple menu →  **About This Mac**. "Apple M…"
means Apple silicon; "Intel" means Intel.

## 2. Install

Open the `.dmg`, then drag the **Lorah** icon into your **Applications**
folder. Eject the disk image and launch Lorah from Applications.

Lorah's release builds are signed with an Apple Developer ID and notarized
by Apple. macOS may ask you to confirm the first launch of an application
downloaded from the internet. The developer shown is **Yoram Golandsky**.

## 3. First launch

On first launch, set up a project and connect model access through one of
the supported setup paths; each path shows its own model requirements. A
beta invitation or license code is not required to start; redeem a beta or
purchase code only if you have one. See [First run](first-run.md) for the
short version, or the [Quickstart](https://lorah.ai/quickstart/) for the
detailed walkthrough.

---

### If macOS blocks the app

If macOS cannot verify the application or reports that it is damaged or
malicious, stop the installation. Confirm that you downloaded the current
release from the official
[releases page](https://github.com/LaGuardAI/bond-releases/releases). If
the problem persists, contact [support@lorah.ai](mailto:support@lorah.ai)
with the exact message, the Lorah version and your macOS version. Do not
disable Gatekeeper or bypass your organization's security policy.

### Updating

Lorah checks for updates on launch and installs them the next time you
quit and relaunch. To check manually, open **Settings → Advanced** and
click **Check for updates** on the version tile. Your workspaces,
conversations, memories, and API keys are preserved across updates.

---

Stuck? Email [support@lorah.ai](mailto:support@lorah.ai).
