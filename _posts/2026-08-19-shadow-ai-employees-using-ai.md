---
layout: post
title: "Your staff are already using AI. How do you make it safe?"
canonical_url: "https://korixinc.com/learning-center/shadow-ai-employees-using-ai"
description: "71% of UK employees use unapproved consumer AI tools at work. Banning it makes it worse. Here is the governed pattern that makes shadow AI auditable and defensible."
tags: ["AI", "AI Governance", "Shadow AI", "Enterprise AI"]
date: 2026-08-19 09:00:00 +0000
---

> **This article was originally published on [korixinc.com](https://korixinc.com/learning-center/shadow-ai-employees-using-ai).**
> Read the canonical version at: <https://korixinc.com/learning-center/shadow-ai-employees-using-ai>

# Your staff are already using AI. How do you make it safe?

_71% of UK employees use unapproved consumer AI tools at work. Banning it makes it worse. Here is the governed pattern that makes shadow AI auditable and defensible._

They already are. Microsoft's 2025 UK research found that 71% of UK employees have used unapproved consumer AI tools at work, and 51% do so every week. The risk is not the AI itself; it is that it is ungoverned: no audit trail, no accountable owner, and client data leaving your control. Governance is what turns shadow AI into auditable AI you can stand behind.

You do not need a survey to know it is happening in your business, but the numbers make it concrete. Alongside that 71%, only about a third (32%) of employees say they are even concerned about the privacy of the company or customer data they put into these tools. And what goes in is not trivial: Cyberhaven's analysis of 1.6 million workers found that 11% of everything employees paste into ChatGPT is sensitive data. And the trend is accelerating: Zendesk's 2026 CX Trends Report found shadow AI use in some industries has grown by as much as 250% year over year. The question is not whether shadow AI is happening in your firm. It is whether you can see it, and whether you could defend it if a regulator asked.

## What "shadow AI" actually is

Shadow AI is your staff using consumer AI tools on real work, off the radar. Someone pastes a client email into ChatGPT to draft a reply. Someone runs a spreadsheet of customer data through a free summariser. Someone uses Copilot to write a policy document, or asks a chatbot to interpret a rule. None of it is logged, none of it is overseen, and often nobody senior knows it is happening. It is not malicious. It is people trying to get their work done faster with tools that are one browser tab away, and Microsoft's research shows the most common reason is simply that they already use these tools in their personal lives.

It is the AI-era version of shadow IT, the familiar problem of staff using unsanctioned software. The difference is that shadow AI does not just route data through an unapproved tool; it makes decisions and produces output that reach your customers, which raises the stakes. And it is not hypothetical: in 2023, Samsung engineers pasted proprietary source code and internal meeting notes into ChatGPT, and the company banned the tool within weeks.

The reason it matters is that these are not sandboxes. They are production: real client data, real decisions, and real output going to real customers, produced by a system nobody in your business can see into. The moment AI touches a customer outcome, it stops being a personal productivity trick and becomes part of how your firm operates, whether or not anyone decided it should.

## Why it is a risk in a regulated business

For an insurance broker, a financial adviser, or anyone giving regulated advice, ungoverned AI creates four specific exposures. Take a broker whose account handler uses ChatGPT to speed up renewal summaries:

- **Data leakage.** The client's details have been pasted into a consumer tool and left your control. You cannot say where that data went, who can see it, or whether it was used to train a model. Given that 11% of what employees paste into these tools is already sensitive, this is not a hypothetical.
- **No audit trail.** Under the FCA's Consumer Duty you have to be able to evidence good customer outcomes. If AI shaped the summary, the recommendation, or the wording, and you cannot show what it did or why, you cannot demonstrate the outcome was good. Absence of evidence is the exposure.
- **Decisions no one can explain or reverse.** A figure or a recommendation that came out of a black box, off the record, is one you cannot defend to a client, a complaint handler, or the regulator, and cannot cleanly undo.
- **Inconsistent output.** Ten people using ten different tools their own way is not a process. It is ten different risk profiles, and no way to know which files are affected.

The common thread is the same one behind most failed AI projects: it is not the model, it is the absence of governance around it. For the wider version of this risk once agents are involved, see [AI agent risks](https://korixinc.com/learning-center).

## Shadow AI vs governed AI, at a glance

The same underlying tools sit behind both. The difference is entirely in the wrapper around them.

| | Shadow AI | Governed AI |
| --- | --- | --- |
| Where it runs | Consumer tools, personal accounts | Inside systems you control |
| Logging | None | Every action, full audit trail |
| Owner | Nobody | One accountable human, with a kill switch |
| Reversible | No | Yes |
| Client data | Leaves your control | Stays in your systems |
| Consumer Duty | Cannot evidence outcomes | Evidenced and defensible |

## The wrong fix: banning it

The instinct is to ban the tools. It does not work. A ban does not remove the pressure that made people reach for AI in the first place, the deadline and the workload are still there, so the usage just moves further underground, onto personal phones and personal accounts where you have even less visibility. You end up with exactly the same risk, minus the ability to see it, plus a team that has learned not to tell you what they are doing. PagerDuty's 2026 research found that a third of employees (33%) who use AI at work would hide it from their managers to avoid scrutiny; a ban only sharpens that instinct. The 71% figure is what usage looks like without a serious ban; drive it underground and you simply lose the 51% who currently do it in the open.

Enforcement makes it worse, not better. You cannot audit what you have pushed into the dark. The goal is not to forbid AI. It is to govern it: take the workflows your team already finds useful and bring them in-house on terms you can stand behind. That is the difference between renting a black box and owning an auditable system, which we cover in [governed AI vs AI consultancy](https://korixinc.com/governed-ai-vs-consultancy).

## The governed pattern

Governing shadow AI means giving people the capability they were reaching for, inside a system you control:

- An audit trail on every action, so you can show a regulator what happened and why.
- One accountable human owner, with a clear kill switch, not a tool that belongs to nobody.
- Reversibility, so any decision the AI influenced can be traced and undone.
- Data that stays in systems you control, not a consumer tool's servers.
- A human checkpoint wherever the consequence is high, and automation only where the work is routine.

This is what we build. On one document workflow we run, every action is logged for a 100% audit trail across 2,847 documents, and a human reviews only the cases the agent is unsure about. For a UK-regulated financial-planning workflow, every automated decision is fully audited, which is exactly what a Consumer-Duty environment requires. Across 50-plus governed builds the pattern holds: the useful work still happens, faster than before, and you can prove exactly how. Our [21-Day AI Pilot](https://korixinc.com/ai-pilot) puts one bounded workflow live in about 21 days, fixed scope and fixed price from around $15,000, and you own the code at the end.

## What to do this week

You do not have to solve all of it at once, and you should not try to. The first move is visibility, not a policy document. Find out, without blame, what AI your team is actually using and for what. People will tell you if the question is "how are you using this" rather than "who broke the rules." Then pick the one or two workflows that show up most, the ones with real client data or real client-facing output, and govern those first. Everything else can wait. Bringing two workflows in-house, logged and owned, removes more real risk than a ban ever will.

## A five-question shadow-AI check

Ask these about your own business today:

1. Do you know what AI tools your team already uses?
2. Is any of that usage logged?
3. Is there one accountable owner for it?
4. Can you reverse a decision the AI influenced?
5. Does client data leave the building when your team uses these tools?

If the answers are no, you do not have governed AI. You have shadow AI. The good news is that the fix is not a ban or a big platform migration. It is bringing the handful of workflows that matter in-house, governed, in weeks.

## The Bottom Line

Shadow AI is not a discipline problem. It is a governance gap.

Your team reached for AI because it helps. Banning it just hides it. The safe move is to bring the workflows that matter in-house, logged, owned, and reversible, with client data in systems you control. Governed, the same tools stop being a liability and become something you can evidence and stand behind.

---

*Originally published at [korixinc.com](https://korixinc.com/learning-center/shadow-ai-employees-using-ai) — read with the full design + comments.*

*Tags: AI, AI Governance, Shadow AI, Enterprise AI*
