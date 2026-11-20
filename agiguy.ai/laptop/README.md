# 7 prompts that fix a slow laptop

Open Claude Code on your laptop (the Claude desktop app's **Code** tab with a **Local** session, or `claude` in a terminal) and paste one prompt at a time. Claude runs your computer's own built-in tools to check, then tells you what it found.

**Good to know:**
- Claude Code needs a paid Claude plan, and it has to run *on* the laptop. The web version can't see your computer.
- In its default mode, Claude asks before it runs a command or changes anything. Every prompt below only looks. Deleting files or changing settings is your call, and Claude will ask first.

| # | Paste this | What Claude checks (built-in tools) |
| --- | --- | --- |
| 1 | `Test my Wi-Fi and tell me how it rates.` | Mac: `networkQuality` gives your download and upload speed plus a Low, Medium or High responsiveness rating (macOS Monterey or later). Windows: `netsh wlan show interfaces` shows signal strength and link speed (Windows has no built-in speed test) |
| 2 | `What's filling up my disk? Show the biggest folders first.` | Mac: `df -h` and `du -sh ~/*`. Windows: `Get-PSDrive` and folder sizes |
| 3 | `Find huge files in Downloads I haven't opened in 3 months. Just list them.` | Files over 500 MB, untouched for 90+ days. You choose what goes; Claude moves files to the Trash only if you say so |
| 4 | `Which apps launch when I log in and slow my startup?` | Mac: Login Items and LaunchAgents. Windows: startup commands (Task Manager > Startup apps) |
| 5 | `What's using the most memory right now?` | Mac: `top -o mem`. Windows: `Get-Process` sorted by memory. Quitting an app is your call |
| 6 | `Is my battery healthy, and what's keeping my laptop awake?` | Mac: `pmset -g batt`, `pmset -g assertions` and battery details (per-app energy is in Activity Monitor's Energy tab). Windows: `powercfg /batteryreport` and `powercfg /requests` (some need an admin prompt) |
| 7 | `Find duplicate files in my Documents. Just list them.` | Matching file hashes. For photos, use the Photos app's built-in **Duplicates** album instead |

**Bonus, security in one line each:** `Is my disk encrypted?` (Mac `fdesetup status`, Windows `manage-bde -status`) and `Is my firewall on?` Turning either on is a setting you change yourself.

More every week on Instagram [@agiguy.ai](https://www.instagram.com/agiguy.ai/).
