# Ideals

Connect Google Antigravity to [Ideals Virtual Data Room](https://www.idealsvdr.com) through the Ideals MCP server. Your agent can then work with the data rooms you already have access to: M&A due diligence, fundraising, audits and other document-heavy deals.

## What you can do

- **Data rooms:** list your rooms and see their details, create a room, or schedule a room to close.
- **Documents:** browse folders, search by name or content, read file text, and download, upload, rename, move, copy and delete files.
- **Users and groups:** list participants and groups, invite users, and update roles.
- **Permissions:** see who can access a folder or document, and get permission reports.
- **Q&A:** list and search questions, ask, answer, and assign experts.
- **Activity:** see who viewed or downloaded what, with summaries and exports.

Every call runs as the signed-in user. The agent sees and changes only what that user's Ideals role and permissions allow.

## Setup

1. Install the **Ideals** plugin from the Antigravity Marketplace.
2. When the MCP server first connects, sign in with your Ideals account in the browser window that opens, then approve access.
3. Ask the agent about your data rooms.

Your account administrator may first need to enable integrations for your company account.

## Requirements

- An Ideals account with access to at least one data room.
- MCP access enabled for your company account. Contact your Ideals account manager if sign-in fails with an access error.

## Server

| | |
|---|---|
| Endpoint | `https://gateway.idealsvdr.com/mcp` (Streamable HTTP) |
| Auth | OAuth 2.0 authorization code with PKCE, issuer `https://auth.idealsvdr.com` |

## Support

- Help center: https://helpcenter.idealsvdr.com
- Privacy policy: https://www.idealsvdr.com/privacy/
- Terms of use: https://www.idealsvdr.com/terms-of-use/
