# Discord Notify Workflow

A GitHub Actions workflow that automatically sends notifications to a Discord channel whenever updates are made to your project. The workflow generates detailed commit notifications, including developer info, commit message, changed files, and more.

---

## Features
- **Automatic Discord notifications**: Triggered by commits on the `main` branch.
- **Detailed commit info**: Includes commit message, author, repository, and file changes.
- **Customizable**: Modify developer mentions, commit details, and more.

---

## Prerequisites

Before setting up the workflow, ensure you have the following:

1. **GitHub Repository**: The repository where you want to set up the workflow.
2. **Discord Webhook URL**: You'll need to create a Discord webhook URL to send the notifications to your server.
3. **GitHub Secrets**: Store the Discord Webhook URL in your repository’s secrets with the key `DISCORD_WEBHOOK`.