```bash
$ whoami
Arthi Vinod — Product Manager, AI-powered SaaS (5+ yrs)

$ cat mission.txt
Most PMs write a spec and wait for engineering.
I open Claude Code and build the thing myself.

$ ls ./proof/
resolved/  eval-career-coach/  how-i-build/  track-record/
$ 
```

## AI Product Manager who ships working software — and tests whether it's telling the truth.
<sub>Product Manager @ Employ Inc — AI-powered SaaS, $56M ARR portfolio</sub>

Engineering background. Product instincts. I use Claude and Claude Code to go from "what if" to a working, demoable prototype — without waiting on an engineering team to validate the idea first. Some people call this vibe coding. I call it skipping the part where someone else builds the prototype to find out if the idea works.

The build is half of it. The other half is knowing when an AI feature is confidently wrong — so I design evals for that too, not just features.

**Latest proof:** [**Resolved**](https://github.com/arthivinod/Resolved) — an AI agent that fights back against companies using AI to deny customer complaints at scale. Real Claude API calls, live repo, no slides required. Most recently: a [**hallucination eval**](https://arthivinod.github.io/myWebsite/case-study-eval-career-coach.html) on an AI career coach — the test-design-and-measurement side of AI PM work, not just the build side. ↓

---

## What I've shipped

Not case studies. Not Figma mocks labeled "product thinking." Working software, with real model calls, that you can clone and run yourself.

<table>
<tr>
<td width="62%" valign="top">

### [Resolved](https://github.com/arthivinod/Resolved)

**They have AI to deny your complaint. Now you have AI to fight back.**

Drop in a photo, screenshot, or forwarded email of a bad order. Resolved extracts the facts with Claude's vision model, picks a vendor-specific strategy — the right channel, tone, and the exact clause of Indian consumer law to cite — drafts a firm complaint via streamed generation, and auto-escalates through five channels (vendor → public post → grievance officer → national helpline → consumer court) until someone pays attention. Zero further effort from the user.

`React 18` · `Vite` · `Claude API (vision + streaming)` · `CSS custom properties`

→ [github.com/arthivinod/Resolved](https://github.com/arthivinod/Resolved)

</td>
<td width="38%">
<img src="https://raw.githubusercontent.com/arthivinod/Resolved/main/design-exports/Hackathon/screenshots/home-after-dark.png" width="320" alt="Resolved app, home screen">
</td>
</tr>
</table>

<table>
<tr>
<td valign="top">

### [Career Coach Hallucination Eval](https://arthivinod.github.io/myWebsite/case-study-eval-career-coach.html)

**I didn't just build an AI feature. I measured whether it lies.**

30 test cases across six failure modes — company facts, salary stats, ambiguous questions, adversarial false premises, out-of-scope visa/legal questions, and controls — scored against two system prompts of the *same* model, so the only variable was prompt design. Pass rate: 30% → 98%, from removing one hallucination-inducing instruction ("avoid being wishy-washy"). On the riskiest category — visa/legal questions — it went from 0% to 100%. Every ground-truth fact was checked against real sources (USCIS, Glassdoor, levels.fyi), not invented, and the write-up states plainly where the method's limits are.

`Claude` · `Eval design` · `Prompt engineering` · `Grounded fact-checking`

→ [Explore the live, filterable eval](https://arthivinod.github.io/eval-career-coach/) · [github.com/arthivinod/eval-career-coach](https://github.com/arthivinod/eval-career-coach) · [Read the write-up](https://arthivinod.github.io/myWebsite/case-study-eval-career-coach.html)

</td>
</tr>
</table>

Also shipped: [**FinePrint**](https://github.com/arthivinod/FinePrint) — a RAG tool that reads Indian tenancy law and flags risky lease clauses, with real citations instead of guesses.

---

## How I build

I don't hand off an idea and wait for a sprint to find out if it works. I open Claude Code and build it — product thinking, interface design, and a working prototype, in one pass, solo.

Resolved went from idea to a working React app making real Claude API calls without a single engineering ticket filed — because there was no engineering team to file one to. I've done the same thing inside Employ: shipped an internal AI tool end-to-end, Figma design through working prototype, without a separate design or eng cycle.

The practical edge isn't that I can code. It's that by the time a feature reaches a roadmap conversation, I've usually already built the version that proves — or kills — the idea.

---

## Track record

I own product charters end-to-end — OKRs, roadmap, discovery through production — across a multi-brand enterprise suite worth $56M in ARR at Employ Inc. That scope only means something if the decisions under it hold up.

One of them: reading through thousands of support tickets by hand to separate what was actually broken from what was just loud — then killing the engineering work nobody needed and redirecting the team to a feature that was quietly leaking revenue instead.

| **4,000+** | **35%** | **$788K** | **67%** |
|:---:|:---:|:---:|:---:|
| tickets triaged | eng effort reprioritized | ARR protected | time-on-task cut |

Once AI features started shipping, nobody owned what happens when the model is wrong, slow, or refuses to answer. I wrote the Responsible AI framework Employ runs against now — applied across 9 production features — and wired MCP connectors (Gong, Tableau) into the product myself instead of waiting for a roadmap slot.

<details>
<summary><b>What's actually in the Responsible AI framework</b></summary>
<br>

- **Explainability** — every AI decision surfaced to a user has a "why," not just a "what"
- **Failure & degradation protocols** — defined behavior for when the model is wrong, slow, or unavailable, instead of silent failure
- **Permissions model** — explicit boundaries on what an AI feature can act on autonomously vs. what it has to surface for human approval

Applied across 9 production features.

</details>

---

<div align="center">

Let's talk.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthi-vinod-a17b3227a)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthivinod28@gmail.com)

</div>
