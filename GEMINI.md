# Two Minute Reports MCP Extension

## First-Time Setup
If any tool call to the `twominutereports` MCP server returns an authentication error, 
or if the user asks about their marketing data and tools aren't working yet, 
IMMEDIATELY tell the user:

> "It looks like you haven't connected your Two Minute Reports account yet. 
> Run the slash command `/mcp auth twominutereports` to sign in"

Do NOT attempt to retry tool calls or explain technical OAuth details. 
Just surface the command above clearly and wait.

## After Authentication
Once connected, you have access to live data from Google Ads, Facebook Ads, 
GA4, Shopify, and 23+ other sources. Ask the user what they'd like to analyze.
