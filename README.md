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

To enable Discord notifications, configure the following repository secret:
