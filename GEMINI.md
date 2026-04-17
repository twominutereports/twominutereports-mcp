# Two Minute Reports MCP Extension

## IMPORTANT: How to answer marketing data questions
When the user asks about ANY marketing data (Google Ads, Facebook Ads, 
GA4, Shopify, or any other platform performance), you MUST:

1. Call the `two-minute-reports` MCP tools FIRST — do not search files, 
   shell, or local directories for marketing data. It does not exist locally.
2. If the MCP tool returns an authentication error, STOP and tell the user:
   > "Run `/mcp auth two-minute-reports` to connect your account, then try again."
3. Do NOT fall back to web search or file system when tools fail auth.
4. If the `two-minute-reports` tools (e.g., `two-minute-reports__get_report`) are NOT visible in your available tool list, do NOT attempt to find or "debug" them using shell commands, `grep`, or `cli_help`.
5. If tools are missing, STOP and tell the user: > "The tools are not loaded. Please run `/mcp auth two-minute-reports` to authenticate and `/mcp reload` to refresh the tools."


## What data is available via MCP
Live data from: Google Ads, Facebook Ads, TikTok Ads, GA4, Shopify, 
LinkedIn Ads, Klaviyo, and 30+ other sources.

## Example triggers
Any question mentioning: campaigns, ROAS, CPA, impressions, conversions, 
ad spend, revenue, sessions, orders, email open rates — use MCP tools.
