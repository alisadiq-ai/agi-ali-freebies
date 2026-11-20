# 9 free fixes for Claude Code's worst habits

The plugins and tools are free. Claude Code itself needs a paid Claude plan. Any savings figure you see on these repos is the repo's own claim.

| # | Fix | What it does for you | Get it | Good to know |
| --- | --- | --- | --- | --- |
| 1 | **ccusage** | One command shows today's, this month's and the current 5-hour window's usage | [ccusage/ccusage](https://github.com/ccusage/ccusage) | MIT. `npx ccusage@latest`; reads local files only |
| 2 | **Caveman** | Short answers, and the code stays exact | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | Apache-2.0. Use the skill-only install |
| 3 | **claude-mem** | Takes notes so your next session starts where you left off | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | Apache-2.0. In the installer pick "your Anthropic plan" to stay free (the hosted option is a paid trial) |
| 4 | **security-guidance** (Anthropic) | Warns when a password or key lands in your code, while Claude edits and on each commit | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/security-guidance) | Apache-2.0. Needs Python 3.8+; its reviews use some of your plan |
| 5 | **commit-commands** (Anthropic) | `/commit`, `/commit-push-pr` and `/clean_gone` | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/commit-commands) | Apache-2.0. `/commit-push-pr` needs the GitHub CLI |
| 6 | **Superpowers** | Claude plans first, writes the tests first, then reviews its own work | [obra/superpowers](https://github.com/obra/superpowers) | MIT. In Anthropic's official marketplace |
| 7 | **Context Mode** | Keeps huge tool output out of Claude's context | [mksglu/context-mode](https://github.com/mksglu/context-mode) | Free (Elastic License 2.0, source-available) |
| 8 | **session-report** (Anthropic) | A clickable report of where your tokens went | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/session-report) | Apache-2.0. Needs Node |
| 9 | **claude-md-management** (Anthropic) | `/revise-claude-md` saves what Claude learned this session to its memory file | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/claude-md-management) | Apache-2.0 |

**Built in, no install:** `/usage`, `/context` and `/compact`.

More every week on Instagram [@agiguy.ai](https://www.instagram.com/agiguy.ai/).
