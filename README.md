# Axolotl Verify

A Discord verification bot with DM-based mathematical challenges and staff notifications for failed verification attempts.

## Features

- `/botsus` sends a mathematical verification challenge to a selected user by DM.
- Up to three answer attempts, with a 60-second timeout per wait.
- A failed verification sends a notification containing the user's Discord username and ID to the configured staff account.
- `/dm` sends a message to a selected Discord user.

> **Implementation note:** The supplied `bot.py` does not currently assign verification roles, persist verification results to a database, or collect IP addresses directly. Documentation should be updated if the implementation changes.

## Documentation

- [Terms of Service](TERMS_OF_SERVICE.md)
- [Privacy Policy](PRIVACY_POLICY.md)
- [Official website](https://maltesecraft.github.io/Axolotl-Verify/)

## Setup

1. Install Python 3.10+ and `discord.py`.
2. Create a Discord application and bot in the Discord Developer Portal.
3. Store the bot token in an environment variable; never commit tokens or secrets.
4. Configure the staff Discord user ID through a secure environment variable.
5. Invite the bot with only the permissions and intents it needs.

The supplied source contained a hard-coded bot token. **Revoke/reset that token immediately** in the Discord Developer Portal before running or publishing the source. Do not commit the old or replacement token.

## Legal contact

Before public launch, replace the contact and controller placeholders in the legal documents with the operator's real details. These templates are informational starting points, not legal advice.
