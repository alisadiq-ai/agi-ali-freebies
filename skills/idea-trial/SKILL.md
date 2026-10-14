---
name: idea-trial
description: Put a business, product or content idea on trial. A prosecutor argues it will fail, a defense argues it will work, twelve jurors (each a different person, such as an accountant, a customer or your biggest competitor) vote guilty or not guilty without seeing each other's votes, and a judge reads the verdict and makes the call. Use when someone wants an idea stress-tested, pressure-tested or judged before they commit to it, or says "put this on trial".
---

# Idea trial

Claude tends to agree with whatever you bring it. This skill makes it argue with itself instead, then lets twelve independent jurors decide.

## 1. The case

Get the idea in a few sentences: what it is, who it's for, and what "success" would mean (a number and a date if possible). If one of these is missing, ask once, then go with what you have and state your assumptions.

Create a folder `idea-trial/` for the outputs and write the case to `idea-trial/00-case.md`.

## 2. Arguments

Launch two subagents (Task tool) **in one message, in parallel**. Each gets only the case.

- **Prosecution:** "Argue that this idea will fail. Use the strongest real reasons: market, money, timing, execution, competition. Name the single most likely way it dies. Under 200 words. Don't invent statistics."
- **Defense:** "Argue that this idea will work. Use the strongest real reasons: the demand signal, the unfair advantage, why now. Name the single most likely way it wins. Under 200 words. Don't invent statistics."

Save them as `idea-trial/01-prosecution.md` and `idea-trial/02-defense.md`.

## 3. The jury

Launch twelve juror subagents **in one message, in parallel**. Each gets the case, both arguments, and only its own seat. Never pass one juror's vote to another.

| # | Juror |
|---|---|
| 1 | An accountant who only trusts the numbers |
| 2 | A target customer who would have to pay for it or spend time on it |
| 3 | Your biggest competitor |
| 4 | An early-stage investor |
| 5 | A skeptical friend who has watched you start things before |
| 6 | A marketer who has to get the first 1,000 users |
| 7 | An engineer or producer who has to build it |
| 8 | A lawyer looking for risk |
| 9 | Someone who tried something similar and failed |
| 10 | A trend forecaster |
| 11 | A busy operator who cares about the time it costs |
| 12 | A fan of the founder who still wants the truth |

Prompt each juror with:

> You are juror {n}: **{seat}**. You've read the case and both arguments. You have not seen any other juror's vote. Vote **GUILTY** (the idea will fail as described) or **NOT GUILTY** (it will work as described), then give your reason in one or two sentences, from your seat. Be honest, not polite.

Save each vote as `idea-trial/jury/{nn}-{seat}.md`.

If you can't launch subagents (for example in the Claude app), run the arguments and the jurors yourself, one at a time, and record each vote before you take the next seat. Say at the end that the jury wasn't fully independent.

## 4. The verdict

Act as the judge. Read everything and write `idea-trial/verdict.md`:

1. **The count:** guilty vs not guilty, with each juror's one-line reason.
2. **What the jury agreed on:** the reasons that came up from several jurors independently.
3. **The judge's call:** one of *proceed*, *proceed with changes* or *drop it*, in two or three sentences. A split jury is not a tie-breaker for the judge's mood: weigh the reasons, not the count.
4. **If you proceed:** the three changes that would flip the guilty jurors, and the cheapest test to run this week.

Finish in the chat with the count, the call and the cheapest test.
