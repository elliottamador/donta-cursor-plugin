# Donta for Cursor

[Donta](https://donta.io) is your memory across every AI app, and a safe build layer for real apps.

This plugin adds two things to Cursor:

- **The Donta MCP server** (`https://donta.io/mcp`). After installing, open Customize → MCPs, click Connect next to donta, and sign in to Donta.
- **An always-on rule** (`rules/donta-memory.mdc`) that has each Agent chat catch up from Donta at the start and save notes as it goes, so you pick up where you left off in any AI app.

Your memory is private to you at donta.io, where you can see, edit or delete anything. Donta keeps the notes and summaries your AI writes, never your conversations.

Donta connects your own GitHub, Vercel and Supabase accounts (at donta.io → Connections). Production is protected, spend and destructive actions ask first, and everything is logged.

## For teams

On a Cursor Teams or Enterprise plan, an admin can import this repository into the team marketplace (Dashboard → Plugins & MCPs) and set it to Required, so everyone on the team gets Donta.

## Support

support@donta.io · [Privacy](https://donta.io/privacy) · [Terms](https://donta.io/terms)

This repository is generated from the Donta app (`plugin/cursor/`, `npm run plugin:cursor`). Changes made here directly are overwritten.
