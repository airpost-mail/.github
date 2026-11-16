<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/airpost-bird-on-dark-128.png">
    <img src="assets/airpost-bird-on-light-128.png" width="96" alt="Airpost">
  </picture>
</p>

<h3 align="center">Airpost</h3>

<p align="center">
  A desktop email client for macOS and Linux with a sync engine written in Rust.<br>
  No account or server of its own: your mail syncs directly between your computer and your provider.
</p>

<p align="center">
  <a href="https://airpost.app">Website</a> ·
  <a href="https://github.com/airpost-mail/airpost">Source</a> ·
  <a href="https://github.com/airpost-mail/airpost/blob/main/docs/install.md">Install</a> ·
  <a href="https://github.com/airpost-mail/airpost/blob/main/CONTRIBUTING.md">Contributing</a>
</p>

---

Airpost is forked from Mailspring and works with Gmail, Microsoft 365, Outlook.com and any IMAP/SMTP server. One engine process holds all your accounts and serves:

- **The desktop app**, with mail, calendar and contacts (CalDAV/CardDAV), snooze, send later, templates, rules and privacy defaults like blocked remote images and stripped tracking pixels.
- **The `airpost` CLI**, with `--json` on everything and a live `watch`.
- **An MCP server** for Claude, Codex and other agents, with read / draft / send access levels, per-folder limits and an audit log.
- **A self-hosted web client** through `airpost-gateway`.

AI features (summaries, reply suggestions, inbox sorting) are optional and off by default, using your own API key or a local model.

### Repositories

| Repo | What it is |
| --- | --- |
| [airpost](https://github.com/airpost-mail/airpost) | Desktop app, Rust engine, CLI, MCP server, gateway and web client |
| [.github](https://github.com/airpost-mail/.github) | This page and org-wide community files |
