# crypto-intel-runner

Launcher only. This public repository holds no bot code and no secrets: its single workflow
(`.github/workflows/run.yml`) fetches the private `crypto-intel-bot` repository with a deploy key stored in
this repository's Actions secrets, runs it, and starts the next run so the bot stays online 24/7.

- Code, settings and documentation live in the private repository.
- To stop the bot: **Actions → run → ⋯ → Disable workflow**. To start it again: enable it and press **Run workflow**.
