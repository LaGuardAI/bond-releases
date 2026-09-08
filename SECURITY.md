# Security policy

Security reports are prioritized above feature work.

## Reporting a vulnerability

Please **do not** open a public GitHub issue for security vulnerabilities.

Instead, email **yoram@laguardai.com** with:

- A description of the issue
- Steps to reproduce, if applicable
- The Lorah version where you observed it (visible in the desktop app's
  About menu)
- Your operating system and version
- Any relevant logs, with personally identifying information and any
  redemption codes / API keys redacted

We will acknowledge receipt within 72 hours and work with you on a
coordinated disclosure timeline.

## Supported versions

For the public Lorah Desktop release channel, security fixes are provided
in the **latest released version**. Older builds do not receive security
updates. Please upgrade promptly.

## Scope

In scope:

- The Lorah desktop application (`Lorah.Setup *.exe`, `Lorah *.dmg`)
- The Lorah license service API at `https://license.lorah.ai`
- Materials in this repository (docs, templates, configuration)

Out of scope:

- Vulnerabilities in third-party model services themselves, which should
  be reported to their operators. Vulnerabilities in Lorah's integration
  with those services remain in scope
- Social engineering or phishing reports unrelated to the product
- Vulnerabilities in third-party software that Lorah depends on, unless
  Lorah's usage of it materially worsens the impact
