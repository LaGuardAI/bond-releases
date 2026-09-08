# Lorah

Your project stays. Models can change.

[Download Lorah](https://github.com/LaGuardAI/bond-releases/releases/latest) ·
[Quickstart](https://lorah.ai/quickstart/) ·
[Website](https://lorah.ai/) ·
[Plans](https://lorah.ai/pricing/)

Lorah is a local-first desktop workspace for AI-assisted project work. Give
specialists different roles, work with supported cloud or customer-controlled
models, and keep your documents and reviewed project knowledge together.
The project belongs to you, not to one model provider.

Generated memory starts as a proposal. You decide what becomes lasting
project knowledge, inspect its origin, and correct it when the work changes.
Shared Memory in the standalone app is shared between your AI specialists;
it is not a shared workspace for multiple human users.

This public repository distributes the standalone application, documentation
and starter workspaces. It is not the Lorah application source repository.
Enclave server packages and enterprise deployment materials are not included
in this distribution.

## Download

Choose an installer from the [latest published release](https://github.com/LaGuardAI/bond-releases/releases/latest).
Read that release's notes and platform requirements before installing.

| Platform | Installer |
|---|---|
| Windows | `.exe` installer |
| macOS, Apple silicon | `arm64.dmg` |
| macOS, Intel | `x64.dmg` |

On a Mac, open **About This Mac** to check whether the machine uses Apple
silicon or Intel. A local model has its own hardware requirements, separate
from the requirements for running Lorah.

Installation help: [Windows](docs/install-windows.md) · [macOS](docs/install-macos.md).

## Start with one useful question

You do not need a beta invitation to download and start using the Free plan.
Pro access and beta license grants are separate from access to the download.
See [Plans](https://lorah.ai/pricing/) and the installed application's license
settings for the current offer and feature availability.

1. Create a project or open a starter workspace.
2. Configure a supported provider API key or compatible model endpoint.
3. Choose a specialist and ask a question about a real piece of work.
4. Review any proposed memory before accepting it for later use.

API access is separate from consumer chat subscriptions. Specialist model
support also does not mean that every automatic setup or internal AI job can
use that same model. Check the requirements shown for the operation.

The [first-run guide](docs/first-run.md) covers the short path. The website
[Quickstart](https://lorah.ai/quickstart/) provides the detailed walkthrough.
For features newly introduced in a release, follow the notes for your
installed version rather than assuming a development feature is available.

## Data and model usage

Standalone project data is stored on your machine. When you use a cloud
model, the context sent for that operation goes to the configured provider.
A customer-controlled endpoint is a separate execution destination, not a
promise that every Lorah operation is offline.

Model usage is billed under your provider account. Lorah's subscription and
model usage are separate costs. Recorded usage can include estimates or
unpriced work; no reported API charge does not mean local compute is free.

Licensing, updates, optional diagnostics and user-requested tools have their
own network behavior. Read the [privacy explanation](https://lorah.ai/privacy/)
and the operation's disclosure before using sensitive material.

## Updates and support

Follow the installed application's update controls or download an installer
from the official release page. Keep a current workspace backup before an
upgrade. Do not delete your project data to troubleshoot an installation.

For help, email [support@lorah.ai](mailto:support@lorah.ai). Include the Lorah
version, operating system and steps to reproduce the problem, without API
keys, private documents or confidential conversation content.

Report vulnerabilities privately using [SECURITY.md](SECURITY.md), not a
public issue. Release-specific changes are listed in the
[release history](https://github.com/LaGuardAI/bond-releases/releases).
