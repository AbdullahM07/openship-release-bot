# openship-release-bot

Watches [oblien/openship](https://github.com/oblien/openship) releases and posts an announcement to Discord when a new one is published.

Runs entirely via a scheduled GitHub Action (`.github/workflows/watch-releases.yml`) — no server, no bot process. Requires one repository secret:

- `DISCORD_WEBHOOK_URL` — the Discord webhook URL for the announcement channel.
