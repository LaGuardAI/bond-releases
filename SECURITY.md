# Security policy

Bond is in **alpha**. Security reports are prioritized above feature work.

## Reporting a vulnerability

Please **do not** open a public GitHub issue for security vulnerabilities.

Instead, email **yoram@laguardai.com** with:

- A description of the issue
- Steps to reproduce, if applicable
- The Bond version where you observed it (visible in the desktop app's
  About menu)
- Your operating system and version
- Any relevant logs, with personally identifying information and any
  redemption codes / API keys redacted

We will acknowledge receipt within 72 hours and work with you on a
coordinated disclosure timeline.

## Supported versions

During alpha, we support security fixes only on the **latest released
version**. Older alpha builds will not receive security updates — please
upgrade promptly when new versions are released.

## Scope

In scope:

- The Bond desktop application (`Bond Setup *.exe`, `Bond *.dmg`)
- The Bond license service API at `https://license.ai-bond.dev`
- Materials in this repository (docs, templates, configuration)

Out of scope:

- Third-party LLM provider APIs (Anthropic, OpenAI, Google, Perplexity)
  that Bond connects to — report those directly to the provider
- Social engineering or phishing reports unrelated to the product
- Vulnerabilities in third-party software that Bond depends on, unless
  Bond's usage of it materially worsens the impact
