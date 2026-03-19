# MantaRisk Plugin for Claude Code

Connect [Claude Code](https://claude.ai/code) to the [MantaRisk](https://mantarisk.com) portfolio risk analysis platform.

## What it does

This plugin gives Claude Code access to MantaRisk's tools for portfolio analytics, stress testing, and investment reporting — directly from your terminal.

## Prerequisites

- [Claude Code](https://docs.claude.com/en/quickstart) installed and authenticated
- A MantaRisk account (you'll be guided through onboarding on first use)

## Installation

Add the marketplace and install the plugin:

```shell
/plugin marketplace add mantarisk/mantarisk-claude-plugin
/plugin install mantarisk@mantarisk
```

Or from the command line:

```bash
claude plugin marketplace add mantarisk/mantarisk-claude-plugin
claude plugin install mantarisk@mantarisk
```

After installation, restart Claude Code or run `/reload-plugins`.

## Authentication

On first use, MantaRisk will trigger an OAuth flow in your browser to authenticate. Follow the prompts to log in or create an account.

## Support

- Website: [mantarisk.com](https://mantarisk.com)
- Email: support@mantarisk.com
