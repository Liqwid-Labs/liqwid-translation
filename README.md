# How to Contribute to the Liqwid App Translations

Thank you for your interest in contributing to the translations for the Liqwid app. Your contributions help make the app more accessible to users around the world. Before you get started, here are some essential guidelines.

## Getting Started

To contribute to the translations, you should be familiar with the basics of creating a merge request (PR) on GitHub. If you're new to this, GitHub provides excellent [documentation](https://docs.github.com/en/get-started/quickstart/contributing-to-projects) to help you get started.

## Translation Format

All language files are in JSON format with the following structure:

```json
{
  "id": "text"
}
```
Alternatively, we can also use the following structure:
```json
{
  "id": {
    "id": "text"
  }
}
```

When making translations, please ensure that you keep the "id" intact and only modify the "text" part. This helps maintain the structure and functionality of the app.

## Have Questions?

If you have any questions or need assistance during the translation process, our community is here to help. Feel free to reach out for support or clarification:

- Join our Discord server and create a ticket. Someone will be there to assist you. [Join Liqwid Discord](https://discord.gg/PZ3GUWamY8)