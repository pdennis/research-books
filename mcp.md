---
title: Research-Books MCP
description: 
published: true
date: 2025-12-29T22:16:45.865Z
tags: 
editor: markdown
dateCreated: 2025-12-29T22:15:36.595Z
---

# Give your chatbot direct access to our research

Chatbots like Claude and ChatGPT can be extremely useful, but hallucinations are a persistent problem. Even without hallucinations, chatbots don't have the kind of specialized and specific political knowledge needed to create effective political communication out of the box. 

We can mitigate these shortcomings by giving the chatbots direct access to this website via a specialized interface. Rather than trying to invent political attacks from scratch, then, it can check to see if there is a research report with the information it needs.

**What this gives you:** Access to opposition research on Republican candidates in competitive 2026 House, Senate, and Governor races, including detailed vulnerability research and issue-specific pages.


## Claude

### Connecting to Research Books in Claude

#### Setup Instructions

1. **Open Settings:** In the Claude web app (claude.ai), click your profile icon and go to **Settings**

2. **Find Connectors:** Look for the **"Connectors"** or **"Integrations"** tab in the settings sidebar

3. **Add New Connector:** Click **"Add MCP Integration"** or **"Add custom connector"**

4. **Enter Details:**
   - **Name:** `Research Books`
   - **URL:** `https://mcp.research-books.com/mcp`
   - **Headers/Token:** Leave blank — no authentication required

5. **Save** the integration

#### How to Use It

Once connected, you can ask Claude things like:

- "What candidates do we have research on?"
- "Pull up the research book on [Candidate Name]"
- "What are Gabe Evans's healthcare vulnerabilities?"
- "Search Research Books for tariff positions"

Claude will automatically use the Research Books tools when relevant to your questions.

#### Troubleshooting

- **Not seeing the tools?** Try refreshing the page after adding the connector
- **Connection errors?** Double-check the URL is exactly `https://mcp.research-books.com/mcp`
- **Tools not firing?** Be explicit: "Use Research Books to find..."

## ChatGPT

### Connecting to Research Books in ChatGPT

#### Setup

1. **Enable Developer Mode:** Go to **Settings → Apps → Advanced settings → Developer mode**

2. **Create the App:**
   - In ChatGPT Apps settings, click **"Create app"** next to Advanced settings
   - **URL:** `https://mcp.research-books.com/mcp`
   - **Authentication:** None required

3. The app will appear under "Drafts" in your app settings

#### Using It

1. In a conversation, choose **Developer mode** from the Plus menu
2. Select the Research Books app
3. Be explicit in your prompts:
```
Use the Research Books app to find opposition research on Gabe Evans.
Do not use browsing or other tools.
```

#### Tips

- Expand tool calls with the carat to inspect JSON payloads
- Write clear, specific prompts that name the app directly
- If tools aren't firing, try: "Use Research Books to search for [candidate name]"
