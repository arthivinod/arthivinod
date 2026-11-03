## Hi, I'm Arthi

I'm a product manager working on AI products. For the last 5+ years I've been in SaaS, currently at Employ Inc on a multi-brand hiring suite (Jobvite, Lever, JazzHR, Pillar) worth $56M in ARR.

The part of AI product work I care most about is the judgment around the model: where it belongs in a flow and where a template or a rule does the job better, how you find out whether it's right, and what the product does when it isn't. I prototype my own ideas with Claude Code, so the first conversation about an idea is usually about something you can click.

[Portfolio](https://arthivinod.github.io/myWebsite/) · [LinkedIn](https://www.linkedin.com/in/arthi-vinod-a17b3227a) · [Email](mailto:arthivinod28@gmail.com)

---

### At Employ

- **Responsible AI framework.** Once AI features started shipping, nobody owned what happens when the model is wrong, slow, or refuses to answer. I wrote the framework the team now runs against, applied across 9 production features: every AI decision a user sees has a "why", every feature has defined behaviour when the model fails, and there's an explicit line between what an AI feature can do on its own and what needs a human to approve.
- **Reading 4,000+ support tickets by hand** to separate what was actually broken from what was just loud. That moved 35% of engineering effort off work nobody needed and onto a feature that was quietly leaking revenue, protecting $788K in ARR.
- **MCP connectors (Gong, Tableau)** wired into the product myself, instead of waiting for a roadmap slot.

| **4,000+** | **35%** | **$788K** | **67%** | **9** |
|:---:|:---:|:---:|:---:|:---:|
| tickets triaged | eng effort reprioritized | ARR protected | time-on-task cut | AI features under the framework |

---

### Things I've built on my own time

<table>
<tr>
<td width="62%" valign="top">

**[Resolved](https://github.com/arthivinod/Resolved)** · prototype, pivot, PRD

Started as an agent that fights customer-support bots on your behalf. Building it showed me the business didn't hold up: consumers don't pay to complain, any chatbot can write the letter, and no company would ever partner with it. So I pivoted it into an after-sales bridge that gets a broken washer or TV to the brand's authorized service with a complete request, and gives brands structured tickets and early defect signals in return. AI is used only where typing is genuinely worse, like reading a model sticker.

[Live v2 prototype](https://arthivinod.github.io/Resolved/prototype/screens.html) · React prototype (v1) · [case study](https://arthivinod.github.io/myWebsite/case-study-resolved.html)

</td>
<td width="38%">
<img src="https://raw.githubusercontent.com/arthivinod/Resolved/main/docs/screenshots/v2-tvoptions.png" width="260" alt="Resolved v2: authorized service vs local repair">
</td>
</tr>
</table>

**[Career Coach Hallucination Eval](https://arthivinod.github.io/eval-career-coach/)** · eval design

I tested whether an AI career coach makes things up. 30 cases across six failure modes (company facts, salary numbers, ambiguous questions, false premises, visa and legal questions, controls), run against two system prompts on the same model so prompt design was the only variable. Removing one instruction, "avoid being wishy-washy", took the pass rate from 30% to 98%, and visa/legal questions from 0% to 100%. Ground truth was checked against USCIS, Glassdoor and levels.fyi, and the write-up is upfront about the method's limits.

[Live eval](https://arthivinod.github.io/eval-career-coach/) · [repo](https://github.com/arthivinod/eval-career-coach) · [write-up](https://arthivinod.github.io/myWebsite/case-study-eval-career-coach.html)

**[FinePrint](https://github.com/arthivinod/FinePrint)** · RAG

Reads a rental lease against Indian tenancy law and flags each clause as fine, questionable or a red flag, citing the law it relied on.

---

### What I'm reading and building next

LangGraph agents: specifically, when a multi-step agent actually needs a graph with explicit state and approval checkpoints, versus a single well-scoped prompt.
