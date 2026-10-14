# AGI with Ali: freebies

Free Claude skills and prompts from my reels on [@agiwithali](https://www.instagram.com/agiwithali/). If you commented a keyword and landed here, your freebie is in the table below.

⭐ **Star the repo so you don't lose it.** New freebies land here with every reel.

| Freebie | What it does | Keyword |
| --- | --- | --- |
| [learn-anything](skills/learn-anything/SKILL.md) | 10 codes for learning any topic fast with Claude: ELI5, 80/20, Feynman, mind map, quiz me, first principles, analogy, steelman, pre-mortem and flashcards | CODES |
| [resume-panel](skills/resume-panel/SKILL.md) | Seven Claudes try to reject your resume, each from a different seat and without seeing the others, then one rewrites it with every issue fixed | RESUME |
| [idea-trial](skills/idea-trial/SKILL.md) | Puts your idea on trial: a prosecutor, a defense, twelve independent jurors and a judge who makes the call | TRIAL |
| [motion-styles](prompts/motion-styles/README.md) | 20 prompts that make Claude animate your logo in a different style each, written as code | STYLES |

## How to use the skills

A skill is a folder with a `SKILL.md` that teaches Claude a procedure. Once it's installed, just ask in plain words ("put my idea on trial", "Feynman: compound interest") and Claude follows it.

- **Claude Code:** `npx skills add alisadiq-ai/agi-ali-freebies`, or copy a folder from `skills/` into `~/.claude/skills/`.
- **Claude app:** download the skill's folder, zip it, and upload the zip in Claude's Skills settings.
- **Codex and other agents:** anything that reads `SKILL.md` files works the same way.

resume-panel and idea-trial run each reviewer as its own subagent, so they work best in Claude Code. In the Claude app they still run, one reviewer at a time.

## How to use the prompts

Open the prompt page, copy a prompt, change the placeholder, paste it into Claude.

## More

Real examples of what Claude can do, every week on [Instagram @agiwithali](https://www.instagram.com/agiwithali/).
