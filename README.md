# Inbind

A local-first markdown editor with built-in AI chat. Keep your notes, your context and your drafts in one place, so the AI has something real to work with.

[Website](https://inbind.app) · [Download](https://github.com/inbindapp/inbind/releases/latest) · [Report an issue](https://github.com/inbindapp/inbind/issues)

## What you get

- **Your files, on your disk.** Open any folder of markdown files and edit them in a clean editor.
- **AI chat that works on your files.** Use your own AI provider, or run models locally with Ollama. You review every change the AI makes.
- **Sharing.** Sync a workspace with your team through GitHub.

## Download

Get the latest version from the [Releases page](https://github.com/inbindapp/inbind/releases/latest). Inbind is free.

| Platform | File |
|---|---|
| macOS, Apple Silicon | `.dmg` (`aarch64`) |
| macOS, Intel | `.dmg` (`x64`) |
| Windows 10 or 11 | `.msi` or `-setup.exe` |
| Linux | `.deb`, `.rpm` or `.AppImage` |

On macOS, open the `.dmg` and drag Inbind into Applications. On Windows, run the installer; if SmartScreen shows a warning, click **More info**, then **Run anyway**.

Inbind checks for updates by itself and asks before installing one.

## Privacy and analytics

Inbind collects a small amount of anonymous usage data so we can see what works and what does not. It never includes your notes or anything that identifies you.

### What Inbind collects and why

- **A random install ID.** Created the first time you run Inbind. It is not linked to your name, email or account.
- **App details.** Inbind version, operating system, CPU type, and whether you use the stable or nightly build.
- **Which features you use.** For example: a workspace was opened, a note was edited, a chat message was sent. We record the kind of action, not its content.
- **AI provider and model names.** For example "anthropic" and the model ID, so we know which models matter.
- **Download counts.** The number of times each Inbind installer is downloaded from GitHub. This is a count, with no information about who downloaded it.

We use this to count active users, see where new users get stuck, and decide what to build next.

### What Inbind never collects

- The contents of your notes
- Your chat prompts or AI responses
- File, folder or workspace names, or paths
- Your name, email address or username
- API keys or tokens
- Names of skills or MCP servers you installed yourself
- Your IP address

### Where the data is stored

Usage data goes to PostHog, hosted in the EU. We turn on the setting that discards IP addresses, so they are never stored.

### How to turn it off

Untick **Share Anonymous Usage Data** in the Inbind menu (macOS) or the Help menu (Windows and Linux). Inbind stops sending data right away and drops anything waiting to be sent. The choice is remembered the next time you start Inbind.

## Contact

Found a bug or have an idea? [Open an issue](https://github.com/inbindapp/inbind/issues). For anything else, including privacy questions, email hey@inbind.app.
