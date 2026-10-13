# Chatfuel for Cursor

Manage your [Chatfuel](https://chatfuel.com) bots from Cursor. This plugin connects Cursor to the Chatfuel MCP server at `https://mcp.chatfuel.com/panel`, so the agent can look into your bots and change their setup when you ask it to.

## What you can do

- **Bots and automations.** List your bots, see how each one is set up, and turn automations on or off.
- **AI agent and knowledge base.** Read the knowledge base, add and edit FAQ answers, update company info, and turn on the AI agent for a bot.
- **Bot settings.** Change how the AI talks and what rules it keeps to, set business hours, set up bookings, and try a reply in a test chat before customers see it.
- **Comment auto-replies.** Set up automatic replies to Instagram, Facebook and TikTok post comments, by keyword or for every comment.
- **Chats.** Read recent conversations, review how the bot handled them, and find out why a bot stays silent.
- **Help and guides.** Search the Chatfuel docs and follow step-by-step guides for common tasks.

Example prompts:

- "Which of my bots have the AI agent turned off?"
- "Add an FAQ answer about delivery times to my store bot."
- "Review yesterday's chats and tell me where the bot failed to answer."

## Install

Install **Chatfuel** from the Cursor Marketplace. The plugin adds one MCP server, `chatfuel`; there is nothing to configure.

## Sign in

The first time the agent uses the server, Cursor asks you to sign in. Log in with your Chatfuel account and approve access on the consent screen. The plugin stores no token: Cursor keeps the sign-in, and the server acts with the same permissions you have in Chatfuel.

**Read-only access.** Turn on Read-only on the consent screen to let the agent only view your data. Tools that change anything are then hidden from the agent and refused by the server.

To revoke access, open Connected apps in the [Chatfuel panel](https://panel.chatfuel.com).

## Full GraphQL API

This plugin uses the catalog endpoint with a fixed, reviewed set of tools. Developers who want the whole Chatfuel GraphQL API (schema search and any query or mutation their account allows) can add the developer endpoint `https://mcp.chatfuel.com/panel/api` by hand. See [mcp.chatfuel.com](https://mcp.chatfuel.com) for setup.

## Privacy and terms

- [Privacy Policy](https://chatfuel.com/privacy-policy.html)
- [Terms of Use](https://chatfuel.com/files/TermsOfUse.pdf)

## Support

- Help center: [chatfuel.com/docs](https://chatfuel.com/docs)
- Email: [team@chatfuel.com](mailto:team@chatfuel.com)
- Plugin issues: [GitHub issues](https://github.com/chatfuel-lab/cursor-mcp-plugin/issues)

## License

[MIT](LICENSE)
