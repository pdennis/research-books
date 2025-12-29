---
title: Research-Books MCP
description: 
published: true
date: 2025-12-29T22:35:55.757Z
tags: 
editor: markdown
dateCreated: 2025-12-29T22:15:36.595Z
---

# Give chatbots direct access to opposition research

![evansclaude2.gif](/evansclaude2.gif)

Chatbots like Claude and ChatGPT can be extremely useful, but hallucinations are a persistent problem. Even without hallucinations, chatbots don't have the kind of specialized political knowledge needed to create effective political communication out of the box.

We can mitigate these shortcomings by giving chatbots direct access to this website via a specialized interface. Rather than trying to invent political attacks from scratch, they can check to see if there's a research report with the information they need.

**What this gives you:** Access to opposition research on Republican candidates in competitive 2026 House, Senate, and Governor races, including detailed vulnerability research and issue-specific pages.

---

## Claude (Anthropic)

### Setup Instructions

1. **Open Settings:** In the Claude web app (claude.ai), click your profile icon and go to **Settings**
2. **Find Connectors:** Look for the **"Connectors"** or **"Integrations"** tab in the settings sidebar
3. **Add New Connector:** Click **"Add MCP Integration"** or **"Add custom connector"**
4. **Enter Details:**
   - **Name:** `Research Books`
   - **URL:** `https://mcp.research-books.com/mcp`
   - **Headers/Token:** Leave blank — no authentication required
5. **Save** the integration

### How to Use It

Once connected, you can ask Claude things like:

- "What candidates do we have research on?"
- "Pull up the research book on [Candidate Name]"
- "What are Gabe Evans's healthcare vulnerabilities?"
- "Search Research Books for tariff positions"

Claude will automatically use the Research Books tools when relevant to your questions.

### Troubleshooting

- **Not seeing the tools?** Try refreshing the page after adding the connector
- **Connection errors?** Double-check the URL is exactly `https://mcp.research-books.com/mcp`
- **Tools not firing?** Be explicit: "Use Research Books to find..."

---

## ChatGPT (OpenAI)

> **Note:** Requires a Pro, Plus, Business, Enterprise, or Education account.

### Setup

1. **Enable Developer Mode:** Go to **Settings → Apps → Advanced settings → Developer mode**
2. **Create the App:**
   - In ChatGPT Apps settings, click **"Create app"** next to Advanced settings
   - **URL:** `https://mcp.research-books.com/mcp`
   - **Authentication:** None required
3. The app will appear under "Drafts" in your app settings

### Using It

1. In a conversation, choose **Developer mode** from the Plus menu
2. Select the Research Books app
3. Be explicit in your prompts:
```
Use the Research Books app to find opposition research on Gabe Evans.
Do not use browsing or other tools.
```