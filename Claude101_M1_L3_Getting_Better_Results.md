# Anthropic Claude 101

**Module:** Meet Claude
**Lesson:** Getting Better Results
**Estimated Time:** 15 minutes

---

## CONCEPT

### Common Challenges and How to Fix Them

As you start working with Claude, you'll encounter moments where the response
isn't quite what you expected. This is normal — and it's an opportunity to
refine your approach.

| Challenge | What's Happening | Try This |
|-----------|-----------------|----------|
| **Response is too generic** | Your prompt didn't include enough context about your specific situation | Add details about your audience, role, or constraints. Instead of "Write an email about the project delay," try "Write an email to our enterprise client explaining that the software integration will be delayed by two weeks. They've been patient so far but this is the second delay. Keep it professional but apologetic." |
| **Response is too long or too short** | Claude is guessing at appropriate length | Be explicit: "Give me a two-paragraph summary" or "Keep this under 100 words" or "I need a comprehensive analysis — length isn't a concern." |
| **Claude didn't follow my format** | Claude understood *what* you want but not *how* you want it presented | Show, don't just tell. Provide an example of the format, or describe the structure explicitly: "Use bullet points with bold headers for each section." |
| **Confident-sounding but incorrect information** | Claude occasionally generates plausible but incorrect information, especially with specific facts or niche topics | For high-stakes work, verify key facts independently. Ask Claude to cite sources or indicate confidence level. Enable web search to ground responses in current information. |
| **Tone isn't right** | Claude defaults to helpful and professional, which may not match your needs | Describe the tone in plain language: "Make this more conversational" or "This should sound authoritative and formal." Provide an example of writing in the style you want. |

---

### The Iteration Mindset

One of the most important shifts when working with Claude is recognising that
your first prompt rarely produces a perfect result — and that's okay. Think of
your initial prompt as the **start of a conversation**, not a one-shot request.

**Effective Claude users:**

- **Treat first drafts as starting points.** Review what Claude produces,
  identify what's working and what isn't, then refine.
- **Give specific feedback.** "Make it shorter" is fine, but "Cut the first
  two paragraphs and make the conclusion more action-oriented" is better.
- **Know when to start fresh.** If a conversation has gone off track,
  sometimes it's faster to open a new chat with a clearer prompt than to try
  to redirect.

---

### What is AI Fluency?

**AI Fluency** is the ability to collaborate effectively with AI tools — not
just knowing which buttons to click, but developing the judgement to use AI
well across different situations.

The **4D Framework for AI Fluency**, developed through research collaboration
between Professor Rick Dakan (Ringling College of Art and Design) and
Professor Joseph Feller (University College Cork), identifies four core
competencies:

| Competency      | What It Means |
|-----------------|---------------|
| **Delegation**  | Deciding what work should be done by humans, what by AI, and how to distribute tasks between them. Includes understanding your goals, AI capabilities, and making strategic choices about collaboration. |
| **Description** | Effectively communicating with AI systems. Includes clearly defining outputs, guiding AI processes, and specifying desired AI behaviours and interactions. |
| **Discernment** | Thoughtfully and critically evaluating AI outputs, processes, behaviours, and interactions. Includes assessing quality, accuracy, appropriateness, and determining areas for improvement. |
| **Diligence**   | Using AI responsibly and ethically. Includes making thoughtful choices about AI systems and interactions, maintaining transparency, and taking accountability for AI-assisted work. |

> You've already been practising these skills throughout this course. The
> prompt framework from Lesson 2 (setting the stage, defining the task,
> specifying rules) is rooted in **Description**. The troubleshooting
> techniques in this lesson draw on **Discernment** and **Diligence**.
>
> To learn more, check out Anthropic's free **AI Fluency course** that
> explores all four competencies in depth.

---

### Evaluating Claude for Your Workflows

As you start integrating Claude into more of your work, you might wonder: how
do I know if Claude is actually good at this particular task? This is where
**Discernment** becomes essential.

**Evals** (short for evaluations) are systematic ways to test how well Claude
performs on specific types of tasks that matter to you.

#### Why Evals Matter

Your work is unique. Claude might excel at drafting marketing copy but need
more guidance for technical documentation in your specific domain. Running
simple evals helps you:

- Understand where Claude adds the **most value** in your workflow
- Identify tasks where you'll need to provide **more context or examples**
- Build **confidence** in Claude's outputs for recurring tasks

#### A Simple Eval Approach

You don't need complex infrastructure to evaluate Claude. Here's a practical
approach:

1. **Gather examples.** Collect 5–10 examples of a task you do regularly —
   emails you've written, reports you've created, analyses you've done.
2. **Create test prompts.** Write prompts that would generate similar outputs.
   Include the context you'd naturally have when doing this work.
3. **Compare outputs.** Run your prompts and compare Claude's responses to
   your examples. Ask yourself:
   - Does Claude capture the key information?
   - Is the tone and style appropriate?
   - What's missing or could be improved?
4. **Refine your approach.** Based on what you learn, adjust your prompts, add
   examples to show Claude what good looks like, or identify where human
   review is essential.

---

## LAB

### Lab 1 — Troubleshoot a Bad Prompt

**Goal:** Experience the common challenges first-hand by starting with a weak
prompt, diagnosing the problem, and fixing it using the troubleshooting
techniques from this lesson.

**Steps:**

1. Open a **new conversation** in Claude.ai.
2. Start with this deliberately vague prompt:

```text
Write an email about a project delay.
```

3. Read the response. It will likely be generic — no audience, no context, no
   tone guidance.
4. Now apply the fix — send this improved version in the **same chat**:

```text
Actually, let me give you more context. Write an email to our enterprise
client explaining that the software integration will be delayed by two
weeks. They've been patient so far but this is the second delay. Keep it
professional but apologetic, under 150 words.
```

5. Compare the two responses side by side.

**Observe:**
- The first response suffers from the **"too generic"** challenge.
- The second applies the fix: added audience, situation context, tone, and
  length constraint.
- Notice how much **one refined prompt** changes the quality of output.

---

### Lab 2 — Practise the Iteration Mindset

**Goal:** Build the habit of treating Claude's first response as a starting
point and refining through specific feedback.

**Steps:**

1. Open a **new conversation** in Claude.ai.
2. Send this prompt:

```text
Write a summary of best practices for cloud cost optimisation aimed at
engineering leadership.
```

3. Read the response, then send **three rounds of specific feedback**, one at
   a time:

**Round 1 — Length:**
```text
This is too long. Cut it to 5 bullet points max.
```

**Round 2 — Tone:**
```text
Good, but the tone is too textbook. Make it sound like advice from a
senior engineer to a peer, not a whitepaper.
```

**Round 3 — Format:**
```text
Now add a one-line action item after each bullet point that a team lead
could assign in JIRA.
```

4. Compare the final output to the first response.

**Observe:**
- Each round of feedback made the output **more specific and usable**.
- Specific feedback ("cut the first two paragraphs") works better than
  vague feedback ("make it shorter").
- Three short follow-ups got you to a polished result faster than one
  long, perfect prompt would have.

---

### Lab 3 — Run a Simple Eval on a Real Task

**Goal:** Use the simple eval approach to test how well Claude handles a
recurring task from your actual work.

**Steps:**

1. Pick a task you do regularly — e.g., writing a weekly status update,
   summarising a meeting, or drafting a stakeholder email.
2. Gather **2–3 examples** of that task you've already completed (past emails,
   reports, updates).
3. Open a **new conversation** in Claude.ai and write a prompt that would
   produce a similar output:

```text
I'm a Director of Cloud Engineering. Every Monday I send a status update
to my manager covering: progress this week, blockers, and next steps.
Here's the context for this week: [paste your real bullet points or notes].
Write the update in a concise, professional tone using bullet points.
Keep it under 200 words.
```

4. Compare Claude's output to your real examples. Ask yourself:
   - Does Claude capture the key information?
   - Is the tone and style appropriate?
   - What's missing or could be improved?
5. Refine the prompt based on what you find and run it again.

**Tips:**
- This is the **Discernment** competency from the 4D Framework in action —
  you're critically evaluating AI output against your own standard.
- Save your refined prompt — it becomes a **reusable template** for this
  recurring task.
- If Claude gets the facts right but the tone wrong (or vice versa), that
  tells you exactly where to focus your prompt refinement.

---

## Key Takeaways

- Common challenges (generic responses, wrong length, incorrect tone) are
  **normal** and fixable with more specific prompts.
- Adopt an **iteration mindset** — treat first responses as starting points
  and refine with specific feedback.
- **AI Fluency** is built on four competencies: Delegation, Description,
  Discernment, and Diligence (the **4D Framework**).
- Use simple **evals** (gather examples → create prompts → compare outputs →
  refine) to understand where Claude adds the most value in your workflows.
- For high-stakes work, always **verify key facts independently** — Claude can
  sound confident even when incorrect.

---

## What's Next

In the next lesson — **Claude Desktop App: Chat, Cowork, Code** — you will
explore the Claude desktop app and its three interaction modes.
