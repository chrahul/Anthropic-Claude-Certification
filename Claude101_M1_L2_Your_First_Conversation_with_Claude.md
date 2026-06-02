# Anthropic Claude 101

**Module:** Meet Claude
**Lesson:** Your First Conversation with Claude
**Estimated Time:** 20 minutes

---

## CONCEPT

### The Human–AI Partnership

Claude is a powerful, intelligent collaborator that amplifies your capabilities
across all of your work. Claude brings AI intelligence, but **you** bring the
context and expertise that makes the work meaningful. The best approach when
speaking to Claude is like you would a coworker — naturally, concisely, and
conversationally.

---

### Starting a Conversation

When you open **Claude.ai**, you see a clean interface with a text input area
at the bottom of the screen. Your **prompts** can range from simple questions
(like brainstorming code names for a new feature) to complex requests to
co-create files.

---

### Writing Effective Prompts

All interactions with Claude begin with a prompt, and these prompts, combined
with other context, impact Claude's response. Before your next conversation
with Claude, consider three elements:

| Element              | Question to Ask Yourself                                                                 | Example in Practice                                                      |
|----------------------|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| **Setting the stage** | What is your role and what are your objectives? Is there context Claude should know?      | "I'm the marketing lead at an indie streaming startup…"                  |
| **Defining the task** | What action do you want Claude to take — write, analyse, build, or something else?       | "…research the current state of the independent film streaming market…"  |
| **Specifying rules**  | What style, tone, or format do you need? Are there examples you can attach?              | "…structure it as a professional report of up to 5 pages, with citations…" |

**Full example prompt combining all three elements:**

```text
I'm the marketing lead at an indie streaming startup, and we're preparing an
investor pitch deck for Series A investors. Can you research the current state
of the independent film streaming market and identify key trends, competitor
positioning, and growth opportunities? Use current web research with citations
and structure it as a professional report of up to 5 pages, with an executive
summary, market analysis, competitive landscape, and growth opportunities.
```

> This prompt framework is adapted from the **4D Framework for AI Fluency**,
> developed through research collaboration between Professor Rick Dakan
> (Ringling College of Art and Design) and Professor Joseph Feller (University
> College Cork). The framework identifies four core competencies — Delegation,
> Description, Discernment, and Diligence. Anthropic offers a free
> **AI Fluency course** to explore all four in depth.

---

### Adding Context

**Uploads**, **connectors**, and **custom preferences** give Claude even more
context about your work. Claude can analyse both text and visual elements
(images, charts, graphics) in documents.

**Supported file types:**

| Category   | Formats                        |
|------------|--------------------------------|
| Documents  | PDF, DOCX, CSV, TXT            |
| Images     | PNG, JPEG (and other common formats) |

**Practical ways to use file uploads:**

- Upload a document and ask Claude to summarise the key points
- Share an image and ask Claude to describe or analyse what it sees
- Attach a spreadsheet and ask Claude to identify trends in the data
- Upload code and ask Claude to explain how it works or find bugs

Once uploaded, Claude automatically attempts to parse the file's content. The
file appears as an attachment in the chat and you can then prompt Claude about
it.

> **Pro-tip:** Go to **Settings > General > "What personal preferences should
> Claude consider?"** to set preferences that apply to every conversation.

---

### Iterating on Claude's Responses

Conversations with Claude are meant to be **iterative**. Chaining bite-sized
prompts together allows for a natural dialogue where you guide the conversation
based on Claude's replies.

| Technique              | When to Use It                                          | Example                                                                |
|------------------------|---------------------------------------------------------|------------------------------------------------------------------------|
| **Ask follow-up questions** | You need more detail, a different angle, or clarification | "Can you expand on the second point?" / "Make it more concise."        |
| **Provide feedback**        | You want to adjust tone, style, or focus                | "This is good, but the tone is too formal. Can you make it more conversational?" |
| **Redirect or restart**     | Claude went in a different direction than you intended   | "Actually, I was asking about X, not Y. Let me clarify…"               |

> **Pro-tip:** Click the **pencil icon** on any of your messages to edit and
> resubmit your prompt — useful when you want to refine your request rather
> than add a new message.

---

### Personalising Claude

Two features help Claude work better for you over time:

| Feature    | What It Does                                                                                                                                                    | Where to Manage        |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|
| **Memory** | Automatically saves key context from your conversations — your role, preferences, past decisions, and working style — so you don't repeat yourself every chat. | Settings > Memory       |
| **Styles** | Customise how Claude communicates. Choose presets (concise, formal, explanatory) or create your own custom style describing exactly how Claude should write.    | Settings > Styles       |

Both sync across all your devices.

---

## LAB

### Lab 1 — Craft a Three-Element Prompt

**Goal:** Practise building a prompt that includes all three elements —
setting the stage, defining the task, and specifying rules.

**Steps:**

1. Open https://claude.ai and start a new conversation.
2. Think of a real task from your current work (e.g., drafting a status
   report, summarising a vendor proposal, writing a stakeholder email).
3. Write your prompt using the three-element structure. Use this template:

```text
[Setting the stage] I'm a [your role] working on [project/objective].
[Defining the task] Can you [specific action — write / analyse / summarise /
compare] [details of what you need]?
[Specifying rules] Use [tone/style]. Structure it as [format]. Keep it
under [length].
```

4. Submit the prompt and review Claude's response.
5. Now send a **follow-up** to iterate:

```text
This is good, but can you make the tone more conversational and add
bullet points for the key findings?
```

**Observe:**
- Compare the first response to the refined one — notice how providing
  feedback steers Claude's output without starting over.
- The three-element structure gives Claude enough context to produce a
  useful first draft, reducing the number of iterations needed.

---

### Lab 2 — Upload a File and Analyse It

**Goal:** Experience Claude's ability to parse uploaded documents and respond
to questions about their content.

**Steps:**

1. Find a document you have on hand — a PDF report, a CSV spreadsheet, a
   code file, or even a screenshot of a chart.
2. In a new Claude.ai conversation, click the **attachment icon** (paperclip)
   and upload the file.
3. Use one of these prompts depending on the file type:

**For a document (PDF/DOCX):**
```text
Summarise the key points of this document in 5 bullet points. Highlight
any action items or deadlines mentioned.
```

**For a spreadsheet (CSV):**
```text
Analyse this data and identify the top 3 trends. Present your findings
in a short table.
```

**For an image (PNG/JPEG):**
```text
Describe what you see in this image. If it's a chart or diagram, explain
the key takeaways.
```

4. Review Claude's response and then iterate:

```text
Now reformat this as a short executive summary I could paste into an email.
```

**Tips:**
- Claude parses the file automatically — you do not need to copy-paste its
  contents.
- If the file is long, Claude's **large context window** (covered in
  Lesson 1) allows it to process the full content in one go.

---

### Lab 3 — Set Up Memory and a Custom Style

**Goal:** Configure Claude's personalisation features so it remembers your
context and communicates the way you prefer.

**Steps:**

1. In Claude.ai, go to **Settings > General**.
2. In **"What personal preferences should Claude consider?"**, enter
   something relevant to your role. For example:

```text
I work as a Director of Cloud Engineering. I prefer concise,
business-ready language with no jargon. Use bullet points for action
items and keep emails under 150 words.
```

3. Save your preferences.
4. Next, go to **Settings > Styles** and either:
   - Select a preset (e.g., "Concise") **or**
   - Create a custom style by describing your preferred writing approach.
5. Start a new conversation and test it:

```text
Draft a short update email to my manager about this week's progress on
our cloud migration project.
```

6. Check whether Claude's response reflects your saved preferences and
   chosen style.

**Observe:**
- Once set, **Memory** and **Styles** apply across all conversations and
  devices — you should not need to repeat your role or tone preferences in
  future chats.
- You can review, edit, or delete anything Claude remembers at any time in
  Settings.

---

## Key Takeaways

- Talk to Claude like a coworker — **naturally, concisely, and
  conversationally**.
- Structure prompts using three elements: **set the stage**, **define the
  task**, and **specify rules** for style, tone, and format.
- **Upload files** (PDF, DOCX, CSV, images) to give Claude additional context
  — it parses them automatically.
- **Iterate** on responses with follow-ups, feedback, or edits (pencil icon)
  rather than expecting perfection on the first try.
- Use **Memory** and **Styles** to personalise Claude so it retains your
  context and communicates the way you prefer.

---

## What's Next

In the next lesson — **Getting Better Results** — you will explore how to give
Claude more precise direction, adjusting its tone, format, and approach to
match exactly what you need.
