# 5 connectors that let Claude do the work

Stop asking Claude to explain the work. Give it the tools to actually do it.

| # | Connector | What Claude can do with it | Link |
| --- | --- | --- | --- |
| 1 | FavStash | Reads your Instagram, TikTok and YouTube, so you can ask why your last reel flopped and get your real numbers back. I built this one. | [favstash.app/start](https://www.favstash.app/start) |
| 2 | Scrape Creators | Pulls any creator's latest reels with their views, so it knows what's actually working in your niche | [scrapecreators.com](https://scrapecreators.com/) · [docs](https://docs.scrapecreators.com/) |
| 3 | Microsoft Clarity | Watches real visitors on your site and tells Claude where they rage-click and leave | [Clarity](https://clarity.microsoft.com/) · [MCP server](https://github.com/microsoft/clarity-mcp-server) |
| 4 | Playwright | Gives Claude hands: it opens your site, clicks every button and tells you what's broken | [Playwright MCP](https://github.com/microsoft/playwright-mcp) |
| 5 | Notion | Everything Claude finds lands in your docs instead of dying in a chat | [Notion MCP](https://www.notion.com/help/notion-mcp) |

Add them in Claude under Settings → Connectors (or `claude mcp add` in Claude Code), then just ask: "Why did my last reel flop?", "Open my site and click every button", "Put this in my Notion".
