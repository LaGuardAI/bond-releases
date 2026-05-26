# Bond alpha user guide

Bond turns your AI subscriptions into a coordinated team of persistent
specialists with shared, traceable project memory. You direct the
specialists; Bond holds the memory and the connective tissue between
them.

## How to use Bond

The how-to lives in the [Quickstart](https://ai-bond.dev/quickstart/),
which walks through each of Bond's six surfaces with short videos:

- **Ask Bond** — your command layer. Ask anything about your project;
  Bond answers, cites sources, and routes you to the right place.
- **Chat** — one-on-one with each teammate. Each keeps its own
  conversation history and memory of your project.
- **Memory** — your project's shared brain: goals, decisions, facts, and
  glossary. Every entry carries provenance — where it came from, who
  reviewed it, how often it's been used.
- **Sync** — where teammates share progress and you approve what becomes
  shared memory.
- **Library** — pin documents so teammates can reference them.
- **Meetings** — bring two or more teammates into the same room.

The deeper guide linked from the Quickstart covers the philosophy behind
Bond and every surface in detail.

## What to expect as an alpha user

Bond works, and it's early. A few things are slow, rough, or
deliberately limited in this build — worth knowing up front:

- **First sync is slow.** 30–60 seconds the first time. That's normal;
  later syncs are faster.
- **Watch your costs.** You're using your own provider keys, so usage
  bills to you. Bond shows cost per teammate and per sync — keep an eye
  on them.
- **Voice input needs an OpenAI key.** Transcription uses OpenAI Whisper.
  The mic button appears regardless, but won't work until you've added
  an OpenAI key.
- **Branches are for short explorations.** You can branch from the main
  thread of a chat, but not branch from a branch, and @-mentions aren't
  resolved while you're on a branch in this build.
- **Occasional sync hiccup.** If a sync's analysis step can't be parsed,
  Bond retries once and then continues without injections for that sync
  rather than blocking you.

## Found a bug?

Reply to your invite email, or email
[support@ai-bond.dev](mailto:support@ai-bond.dev). We read everything.
Discord and a public bug tracker are coming.
