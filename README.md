# GitHub Actions Notifications

This repository contains GitHub Actions workflows for sending automated notifications to multiple messaging platforms, including Gmail, Discord, and Microsoft Teams.

## Supported Platforms

| Platform        | Status         |
| --------------- | -------------- |
| Discord         | ✅ Implemented |
| Gmail           | 🚧 Planned     |
| Microsoft Teams | 🚧 Planned     |

## Current Features

- Send a Discord notification when a new Pull Request is opened.
- Include Pull Request details such as title, author, source branch, target branch, and URL.
- Use GitHub Secrets to securely manage webhook credentials.

## Configuration

### Discord Webhook

1. Open your Discord server.
2. Navigate to **Server Settings → Integrations → Webhooks**.
3. Create a new webhook and select the target channel.
4. Copy the Webhook URL.

### GitHub Secrets

Add the following repository secret:

| Secret                | Description         |
| --------------------- | ------------------- |
| `DISCORD_WEBHOOK_URL` | Discord Webhook URL |

Navigate to **Settings → Secrets and variables → Actions → New repository secret** to add the secret.

Once configured, GitHub Actions will automatically send a notification to your Discord channel whenever a new Pull Request is opened.
