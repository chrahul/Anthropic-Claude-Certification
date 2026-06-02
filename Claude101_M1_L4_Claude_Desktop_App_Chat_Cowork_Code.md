# Anthropic Claude 101

**Module:** Meet Claude
**Lesson:** Claude Desktop App — Chat, Cowork, Code
**Estimated Time:** 6 minutes

---

## CONCEPT

### Overview

The Claude desktop app gives you three ways to work with Claude — **Chat**,
**Cowork**, and **Code** — from quick questions to complex research to building
software.

- **Chat** is the same Claude you know from claude.ai, plus extras that come
  from running natively on your computer.
- **Cowork** is an agentic tool — you give it a goal, connect it to your tools
  and resources, and let it do the work.
- **Code** is for building software — writing, testing, and deploying code.

> **Under the hood:** Cowork and Code both run on the same engine — **Claude
> Code** — local to your machine, capable of independent work, able to spin up
> sub-agents and sustain long tasks.

---

### Chat

Chat excels when you need to ask questions, brainstorm, draft, or work through
problems back and forth. It works the same as claude.ai, with extras from
running natively on your desktop:

| Feature | What It Does |
|---------|-------------|
| **Quick entry** | Double-tap the Option key (Mac) to pull up Claude over whatever you're working on. Responds in a compact overlay window that stays on top. |
| **Screenshots & window sharing** | Capture a screenshot or share a window so Claude sees exactly what you're looking at. Faster and more precise than describing your screen. (Mac) |
| **Dictation** | Talk through a problem instead of typing. Useful when thinking out loud or away from your keyboard. (Mac) |
| **Desktop connectors** | Connect local tools and services so Claude can work with other tools on your machine. |

**When to use Chat:**

- You're staring at an unfamiliar dashboard — screenshot it via quick entry and
  ask "what do these metrics mean?"
- You're between meetings and want to think through a presentation structure —
  open quick entry, switch to voice, and talk it through.
- You've been jotting ideas across Apple Notes for weeks — add the Notes
  connector and ask Claude to pull everything together and identify gaps.

---

### Cowork

**Claude Cowork** is built for work that takes real effort: pulling information
from many sources, making sense of it, and producing something finished.

Claude can **multitask**, tackling different parts of a project at a time. Before
starting, Claude often asks a short set of questions to pin down scope, format,
and constraints. It builds a **plan** you can review in the sidebar.

#### Key Cowork Features

| Feature | What It Does |
|---------|-------------|
| **Folder access** | Point Claude to a folder — it reads what's there, figures out what's relevant, and saves finished work back to the same place. |
| **Scheduled tasks** | Define recurring work (daily briefing, weekly roundup, morning inbox triage) and Claude handles it automatically each time the app is open. Catches up on missed runs when you return. |
| **Subagents** | Background workers Claude spins up to handle parts of a task in parallel. Complex requests get broken into subtasks, each with its own context, then coordinated into one finished deliverable. |
| **Dispatch** | A persistent thread that lets you continue Cowork conversations from your phone (requires both desktop and mobile apps, desktop must be awake and open). |
| **Projects** | Group related tasks into dedicated workspaces with their own files, context, instructions, and memory. Live locally on your desktop. |
| **Browser use** | Connect Claude in Chrome to navigate websites, interact with pages, and pull findings directly into the task. |
| **Computer use** | When no connector or plugin exists, Claude navigates your computer directly — clicking, typing, opening apps. Follows a priority order: connectors first → Chrome → screen interaction. Permission prompt before each app. Blocklist available. *(Research preview — Pro/Max, macOS only; Windows coming soon)* |
| **Plugins** | Add capabilities Claude doesn't have on its own — live financial data, internal knowledge base search, compliance frameworks. Browse and add from the Cowork interface. |
| **Protected environment** | Cowork runs in a contained space — Claude can read, create, and edit files within shared folders but cannot access anything outside them. |

**When to use Cowork:**

- Query across tools like a database — "review what we decided about pricing
  last quarter across meeting notes, Slack, and email, then update our Q3 deck."
- Research a new market or scope competitors — Cowork visits sites, reads
  reports, pulls pricing, and delivers a structured brief with sources.
- Work through 50+ project documents — Cowork reads every page,
  cross-references across the full set, and produces a summary memo.
- Automate recurring morning prep — set it up once as a scheduled task and
  start the day with answers instead of admin.

> **Availability:** Cowork is available to Pro, Max, Team, and Enterprise
> users, with new capabilities being added regularly.

---

### Code

The **Code** tab gives you access to the power of Claude Code running directly
inside the desktop app — a full development environment for building software.

Claude works directly in your codebase: reading what's there, writing and
modifying code, running commands. Visual diffs show what changed, a built-in
terminal shows commands as they run, and **git** tracks every version so you
can always roll back.

> **Key difference from Cowork:** Where Cowork runs in a contained workspace
> limited to shared folders, Code runs directly in your project with **full
> access** to your file system, terminal, and development tools.

#### Where Work Happens

| Environment | How It Works |
|-------------|-------------|
| **Local** | Select a folder on your computer. Claude works directly with those files, accesses local tools, and can run a dev server you preview in your browser. |
| **Remote** | Connect a GitHub repository. Claude works in a cloud environment. Sessions continue even if you close the app — start a big refactor and check back later. |

#### Interaction Modes

| Mode | Level of Autonomy |
|------|-------------------|
| **Ask** | Claude proposes every change and waits for your approval. You review a visual diff and accept or reject before anything is modified. |
| **Code** | Claude applies file changes automatically but checks before running terminal commands. |
| **Plan** | Claude outlines its full approach before touching anything. A dedicated plan viewer lets you review and revisit the strategy as work progresses. |

You can run multiple sessions across projects and filter them by status
(Active / Archived) and environment (Local / Cloud) from the sidebar.

> **Availability:** Code tab is available on Pro, Max, Team, and Enterprise
> plans.

---

### Comparing the Three Modes

|  | Chat | Cowork | Code |
|--|------|--------|------|
| **Optimised for** | Quick exchanges: exploring ideas, iterative drafting, quick answers, learning through dialogue | Complex or sustained work: research, analysis, file organisation, producing finished documents and deliverables | Building software: writing, testing, running, and deploying code |
| **Key features** | Quick entry, dictation | Work from local folders, plugins, subagents, scheduled tasks | Ask/Code/Plan modes, visual diffs, git integration, local and remote environments |
| **Tools & extensions** | Connectors, Skills, Claude in Chrome | Connectors (local & remote), Skills, Claude in Chrome, Plugins, Computer Use | Connectors, Skills, Claude in Chrome, Plugins, Hooks |

---

## LAB

### Lab 1 — Quick Entry and Screenshot in Chat

**Goal:** Experience Chat's native desktop features — quick entry and
screenshot — to get answers without leaving your current work.

**Steps:**

1. Open any application on your desktop — a dashboard, a spreadsheet, a
   document, or a webpage.
2. **Double-tap the Option key** (Mac) to invoke quick entry.
3. Use the screenshot/window sharing feature to capture what's on your screen.
4. In the quick entry overlay, type:

```text
What am I looking at? Summarise the key information on this screen and
highlight anything that needs attention.
```

5. Review Claude's response in the overlay while your original app stays
   visible behind it.

**Observe:**
- You never left the app you were working in — this is the value of
  **quick entry**.
- Claude interpreted visual content from the screenshot, not just text you
  typed — this is faster and more precise than describing your screen.

> **Note:** If you're on Windows or don't have the desktop app yet, you can
> simulate this by taking a manual screenshot, opening Claude.ai, and
> uploading the image as an attachment.

---

### Lab 2 — Choose the Right Mode

**Goal:** Build the judgement to pick the correct mode (Chat, Cowork, or Code)
for a given task.

**Steps:**

1. Review the following five work scenarios.
2. For each, decide which mode — **Chat**, **Cowork**, or **Code** — is the
   best fit, and write down your reasoning.

| # | Scenario | Your Answer |
|---|----------|-------------|
| 1 | You need a quick summary of what "blue-green deployment" means | ? |
| 2 | You want to research 5 competitors, compare their pricing, and produce a polished briefing document with sources | ? |
| 3 | You need to refactor a Python FastAPI backend to add a new API endpoint with database migrations | ? |
| 4 | You're drafting a short email to your manager about this week's progress | ? |
| 5 | Every Monday morning you want a summary of last week's Slack messages and calendar highlights waiting for you | ? |

3. Check your answers against the key below:

| # | Best Mode | Why |
|---|-----------|-----|
| 1 | **Chat** | Quick question, single back-and-forth exchange |
| 2 | **Cowork** | Multi-source research, sustained effort, finished deliverable |
| 3 | **Code** | Direct codebase work — file edits, terminal commands, git tracking |
| 4 | **Chat** | Short iterative drafting task |
| 5 | **Cowork** (Scheduled task) | Recurring automated work pulling from multiple tools |

**Tips:**
- A good rule of thumb: if the task involves **multiple sources and a finished
  deliverable**, it's Cowork. If it's **code in a repo**, it's Code.
  Everything else is Chat.
- When in doubt, start in Chat — you can always escalate to Cowork or Code if
  the task grows in complexity.

---

### Lab 3 — Plan a Cowork Task

**Goal:** Design a Cowork task for a real work scenario, including the goal,
sources, and expected output — so you're ready to run it when you have access.

**Steps:**

1. Open a **new conversation** in Claude.ai (or the desktop app Chat mode).
2. Paste the following prompt:

```text
I want to set up a Cowork task for the following scenario:

Every Monday morning, I need a prep brief for my week. It should:
- Pull my calendar events for the week
- Check Slack for any unread messages or threads I was mentioned in
- List any overdue or due-this-week JIRA tickets assigned to me
- Summarise everything into a single briefing document with sections:
  Calendar, Messages Needing Attention, and Task Priorities

Help me write the exact goal description and list the connectors/tools
I would need to set up in Cowork for this to work as a scheduled task.
```

3. Review Claude's output — it should give you a goal description and a list
   of required connectors.
4. Save this as a reference for when you set up your first real Cowork
   scheduled task.

**Tips:**
- This lab works even if you don't have Cowork access yet — you're
  **planning** the task so you're ready to execute it.
- The connectors Claude suggests (Slack, Calendar, JIRA) will need to be
  configured in **Settings** within the desktop app when you run it for real.

---

## Key Takeaways

- The Claude desktop app offers three modes: **Chat** (quick exchanges),
  **Cowork** (complex, multi-source work), and **Code** (building software).
- **Chat** adds native desktop features over claude.ai: quick entry,
  screenshots, dictation, and desktop connectors.
- **Cowork** is agentic — it uses subagents, scheduled tasks, folder access,
  browser/computer use, and plugins to produce finished deliverables.
- **Code** gives full development environment access with Ask/Code/Plan
  interaction modes, visual diffs, git integration, and local or remote
  environments.
- Both Cowork and Code run on **Claude Code** under the hood — local to your
  machine, capable of independent, long-running tasks.

---

## What's Next

In the next module — **Organising Your Work and Knowledge** — you will learn
how to use **Projects** to give Claude structure and reusable knowledge.
