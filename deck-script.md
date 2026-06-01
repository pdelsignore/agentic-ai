# Agentic AI — Deck Script

Use this document to recreate the **Agentic AI** slide deck. Each section is written as a build prompt: copy a slide block into your slide-deck generator, or use the full deck prompt at the end.

---

## Global deck prompt

Create a single-file HTML presentation titled **Agentic AI** with **15 slides**. Use the **chat-to-claw** visual system:

- **Fonts:** Playfair Display (headlines) + Space Grotesk (body)
- **Colors:** cream background `#f8f6f2`, text `#1a1814`, muted `#8a8680`, terracotta accent `#c84b2f`
- **Feel:** editorial, light mode, subtle grain overlay, faint Unsplash backgrounds on every slide
- **Navigation:** Prev/Next buttons, slide counter, arrow keys, click left/right halves, swipe on mobile, bottom progress bar
- **Transitions:** opacity crossfade between slides (no slide-level translate transforms); active slide stacks above exiting slide
- **Animations:** staggered `.anim` entrance on text; special behaviors noted per slide below

**Assets folder:** six evolution diagrams — `assets/01r.png` through `assets/06r.png` — used on slides 4–9 (left panel, ~20% smaller than default full width).

---

## Slide 1 — Hero

**Prompt:**

> Build a hero slide (slide 1). Left-aligned editorial layout with a horizontal rule above the title.
>
> **Title:** Agentic AI (italicize “AI” in terracotta accent)
>
> **Subtitle:** Latest Trends, Autonomous Agents, and the Next Evolution of Intelligence
>
> **Footer row:** terracotta pill tag **AI Brief** + byline **Paul DelSignore** (uppercase, letter-spaced)
>
> **Background:** faint atmospheric Unsplash image (AI/tech mood), very low opacity.
>
> Stagger-animate: rule → title → subtitle → footer.

---

## Slide 2 — Trends in Motion

**Prompt:**

> Build a left-aligned list slide titled **Trends in Motion** (line break: “Trends” / “in Motion”). Large display headline.
>
> **Numbered trends** (four rows, 01–04, with hover underline animation). Each row animates in **one at a time** when the slide becomes active (staggered delays, not all at once):
>
> 1. Vibe coding  
> 2. Localized Agents  
> 3. Agent Skills  
> 4. Agentic automation  
>
> **Background:** faint earth-from-space or tech Unsplash image.

---

## Slide 3 — Satya Nadella quote

**Prompt:**

> Build a centered quote slide.
>
> **Opening quote mark** (large, faint terracotta)
>
> **Quote:** AI agents will become the primary way we interact with computers in the future.
>
> **Attribution:** Satya Nadella (uppercase, letter-spaced, accent color)
>
> **Background:** faint neural-network / AI visualization Unsplash image.

---

## Slide 4 — Chatbots (evolution 1 of 6)

**Prompt:**

> Build a **two-column evolution slide** (full-bleed split layout). Left: diagram image. Right: text stack (left-aligned).
>
> **Diagram:** `assets/01r.png` — Chatbots diagram (“knows but doesn't do”)
>
> **Period label:** 2022 — Early 2023  
> **Headline:** Chatbots (italicize “bots”)  
> **Tagline:** Knows but doesn't do  
> **Body:** The ChatGPT moment blew minds. Ask a question from a web browser, get an answer. But in a very short space of time, context windows ran out and you kind of ran out of things to do with it. Useful on the side, but limited.
>
> Vertical rule between columns. Faint Unsplash background. Diagram sized ~20% smaller than max column width.

---

## Slide 5 — Reasoning (evolution 2 of 6)

**Prompt:**

> Same two-column evolution layout as slide 4.
>
> **Diagram:** `assets/02r.png`
>
> **Period label:** 2023 — Early 2025  
> **Headline:** Reasoning (italic, accent)  
> **Tagline:** Plans multi-step tasks  
> **Body:** Chain-of-thought prompting changed the game. Models began planning in multiple steps, and tools like LangChain agents emerged. Feeding context back into the system produced progressively better outcomes — each loop smarter than the last.

---

## Slide 6 — Tool Use (evolution 3 of 6)

**Prompt:**

> Same two-column evolution layout.
>
> **Diagram:** `assets/03r.png`
>
> **Period label:** Mid 2023 — 2024  
> **Headline:** Tool Use (italicize “Use”)  
> **Tagline:** Can call tools and APIs  
> **Body:** The first big shift. Models gained access to the outside world — browsing the internet, connecting to APIs, Zapier, Wolfram Alpha. Remember when "book me a flight" was the killer demo? Not a great use case, but it proved capability.

---

## Slide 7 — Operator (evolution 4 of 6)

**Prompt:**

> Same two-column evolution layout.
>
> **Diagram:** `assets/04r.png`
>
> **Period label:** 2025  
> **Headline:** Operator (italic, accent)  
> **Tagline:** Browser actions on your behalf  
> **Body:** ChatGPT got its own browser. Moving a mouse, clicking buttons, interpreting screenshots. It wasn't just answering — it was acting. Slow, yes. But the shift from responding to doing was profound. Not just knowing, but operating.

---

## Slide 8 — Coworker (evolution 5 of 6)

**Prompt:**

> Same two-column evolution layout.
>
> **Diagram:** `assets/05r.png`
>
> **Period label:** Late 2025 — Early 2026  
> **Headline:** Coworker (italicize “worker”)  
> **Tagline:** Human still in the loop  
> **Body:** Claude Code. AI moved directly onto your device — manipulating files, using browsers, writing code in your workspace. The paradigm shift: AI coming closer to you. But every action still requires a human click. "I accept that this is what's happening."

---

## Slide 9 — Autonomous (evolution 6 of 6)

**Prompt:**

> Same two-column evolution layout.
>
> **Diagram:** `assets/06r.png`
>
> **Period label:** 2026  
> **Headline:** Autonomous (italic, accent) — **no quotation marks** around the word  
> **Tagline:** Always on. Event-triggered.  
> **Body:** Dedicated hardware. Full permissions — emails, calendar, browser. People talk to agents via Telegram and WhatsApp while the agent works continuously in the background. Mac Minis sold out. It's always on, acting on triggers even when you're not asking.

---

## Slide 10 — The Inflection Point

**Prompt:**

> Build a centered statement slide.
>
> **Accent line** (short horizontal rule, centered, above title)
>
> **Headline:** The Inflection Point (italicize “Inflection”; line break after “Inflection”)
>
> **Subline:** Dec 2025 – Feb 2026 (uppercase, muted, letter-spaced)
>
> Large display type. Faint Unsplash background (news/data mood).

---

## Slide 11 — Andrej Karpathy quote

**Prompt:**

> Build a centered quote slide with **longer body text** (smaller than slide 3 quote size).
>
> **Opening quote mark**
>
> **Quote:** …programming is becoming unrecognizable. You're not typing computer code into an editor like the way things were since computers were invented, that era is over. You're spinning up AI agents, giving them tasks in English and managing and reviewing their work in parallel.
>
> **Attribution:** Feb 2026 · X post · Andrej Karpathy
>
> Faint Unsplash background (laptop/code mood).

---

## Slide 12 — What is vibe coding?

**Prompt:**

> Build a centered concept slide with **click-to-reveal** bullets (each Next/arrow advance reveals one item before leaving the slide).
>
> **Eyebrow:** Concept  
> **Headline:** What is vibe coding? (italicize “vibe coding?”)
>
> **Bullets** (reveal one at a time, with arrow prefix →):
> 1. Describe what you want in plain English.  
> 2. AI writes the code.  
> 3. You iterate on what you see.
>
> **Footer hint** (reveal last): DESCRIBE → SEE RESULT → DESCRIBE AGAIN (arrows between words, muted separators)
>
> Faint Unsplash background (circuit/tech mood).

---

## Slide 13 — Vibe Coding examples

**Prompt:**

> Build a **dense reference slide** with scroll if needed. Centered headline, two-column grid below.
>
> **Headline:** Vibe Coding examples (italicize “examples”)
>
> **Six categories with bullet lists:**
>
> **Data & Visualization**  
> - Interactive charts & graphs  
> - Dashboards from data sources  
>
> **Creative & Media**  
> - Animated SVG illustrations  
> - Music visualizers  
> - Digital zines or interactive stories  
>
> **Documents & reports**  
> - Branded PDF or HTML reports  
> - Auto-generated slide decks  
> - Newsletters and email templates  
>
> **Productivity & Workflow**  
> - Personal CRM or contact trackers  
> - Habit or goal trackers  
> - Meeting agenda generators  
> - Markdown-based wikis or knowledge bases  
>
> **Games & Interactive experiences**  
> - Simple browser games (trivia, word games, puzzle)  
> - Interactive quizzes and assessments  
> - Escape room-style logic puzzles  
>
> **Prototypes & Mockups**  
> - Clickable UI prototypes  
> - Design system component libraries  
>
> Stagger-animate headline then grid. Faint team/workspace Unsplash background.

---

## Slide 14 — Tools vs. Skills

**Prompt:**

> Build a centered quote slide (short, punchy — like slide 3).
>
> **Opening quote mark**
>
> **Quote:** Tools give agents access. Skills give agents capability.  
> (Bold/highlight **Tools** and **Skills** in terracotta; rest in italic display type)
>
> No attribution line.
>
> Faint server-room / infrastructure Unsplash background.

---

## Slide 15 — Agent skills definition

**Prompt:**

> Build a centered quote slide with **definition-length** text (use smaller long-quote typography).
>
> **Opening quote mark**
>
> **Quote:** Agent skills are reusable actions, workflows, or tools available to an AI agent.  
> (Highlight **Agent skills** in terracotta bold)
>
> No attribution line.
>
> Faint city/architecture Unsplash background.

---

## Full deck prompt (single copy-paste)

Create a 15-slide HTML deck titled **Agentic AI** using the chat-to-claw design system (Playfair Display + Space Grotesk, cream `#f8f6f2`, terracotta `#c84b2f`, grain overlay, Unsplash backgrounds, Prev/Next nav, 15-slide counter). Include:

1. **Hero** — Agentic AI; subtitle “Latest Trends, Autonomous Agents, and the Next Evolution of Intelligence”; AI Brief tag; Paul DelSignore  
2. **Trends in Motion** — four trends (Vibe coding, Localized Agents, Agent Skills, Agentic automation) stagger in one-by-one  
3. **Quote** — Nadella: “AI agents will become the primary way we interact with computers in the future.”  
4–9. **Evolution series** — six two-column slides with `01r.png`–`06r.png`: Chatbots; Reasoning; Tool Use; Operator; Coworker; Autonomous (no quotes on Autonomous) — full copy per slides 4–9 above  
10. **The Inflection Point** — Dec 2025 – Feb 2026  
11. **Quote** — Karpathy long quote on programming/agents (Feb 2026 · X post)  
12. **What is vibe coding?** — three click-reveal bullets + flow hint  
13. **Vibe Coding examples** — six-category two-column grid (all bullets listed above)  
14. **Quote** — “Tools give agents access. Skills give agents capability.”  
15. **Quote** — “Agent skills are reusable actions, workflows, or tools available to an AI agent.”

Use opacity-only slide transitions with z-index stacking to avoid compositor glitches. No `mix-blend-mode` on background images.

---

## Slide order summary

| # | Type | Title / theme |
|---|------|----------------|
| 1 | Hero | Agentic AI |
| 2 | List | Trends in Motion |
| 3 | Quote | Satya Nadella |
| 4 | Evolution | Chatbots |
| 5 | Evolution | Reasoning |
| 6 | Evolution | Tool Use |
| 7 | Evolution | Operator |
| 8 | Evolution | Coworker |
| 9 | Evolution | Autonomous |
| 10 | Statement | The Inflection Point |
| 11 | Quote | Andrej Karpathy |
| 12 | Concept (reveal) | What is vibe coding? |
| 13 | Grid | Vibe Coding examples |
| 14 | Quote | Tools vs. Skills |
| 15 | Quote | Agent skills definition |
