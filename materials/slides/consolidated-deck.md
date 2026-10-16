# Prompt Engineering for Work — Consolidated Deck

The whole one-day workshop in one document: 90 slides, each with its on-screen
text, speaker notes, timer, and full exercise instructions. It replaces the
eight per-module slide files and follows [CHARTER.md](../../CHARTER.md).

## Contents

- [About this course](#about-this-course): the charter's description and objectives
- [Objective coverage](#objective-coverage): which slides and exercises deliver each objective
- [How to read this deck](#how-to-read-this-deck)
- [Brand and accessibility](#brand-and-accessibility): the UNO values applied here
- The deck:

| Section | Time | Slides | Objectives |
| --- | --- | --- | --- |
| [Opening](#opening) | 8:30–8:45 | 1–7 | — |
| [Module 1 — How AI tools work](#module-1--how-ai-tools-work) | 8:45–9:45 | 8–20 | 1 |
| [Module 2 — Anatomy of a good prompt](#module-2--anatomy-of-a-good-prompt) | 9:45–10:45 | 21–35 | 2 |
| *Break* | 10:45–11:00 | 36 | |
| [Module 3 — Techniques](#module-3--techniques) | 11:00–12:00 | 37–49 | 3, 4 |
| *Lunch* | 12:00–1:00 | 50 | |
| [Module 4 — Checking outputs](#module-4--checking-outputs) | 1:00–2:00 | 51–63 | 3, 4 |
| [Module 5 — Using AI responsibly](#module-5--using-ai-responsibly) | 2:00–2:45 | 64–75 | constraint |
| *Break* | 2:45–3:00 | 76 | |
| [Module 6 — Capstone](#module-6--capstone) | 3:00–4:00 | 77–86 | 4, 5 |
| [Closing](#closing) | 4:00–4:30 | 87–90 | — |

**Exercises**

| # | Exercise | Slide | Minutes | Format |
| --- | --- | --- | --- | --- |
| 1 | Can or can't? | 17 | 10 | Pairs |
| 2 | Test the limits | 18 | 17 | Pairs |
| 3 | Fix-it: bad prompt vs. better prompt | 32 | 12 | Pairs |
| 4 | Your own task, draft 1 | 33 | 15 | Solo |
| 5 | Show, don't tell | 46 | 10 | Pairs |
| 6 | Three rounds of iteration | 47 | 18 | Solo |
| 7 | Spot the problems | 59 | 8 | Pairs |
| 8 | Prompt bake-off: build, then judge | 60–61 | 15 + 8 | Groups of 4–5 |
| 9 | Traffic light | 72 | 10 | Small groups |
| 10 | Clean this prompt | 73 | 8 | Pairs |
| 11 | Capstone build | 83 | 18 | Solo |
| 12 | Table presentations | 84 | 15 | Table groups |

---

## About this course

Restated from [CHARTER.md](../../CHARTER.md), word for word.

**Description.** The quality of results produced by generative AI often depends
on the quality of the instructions it receives. Effective prompt design helps
users communicate their intent clearly, provide appropriate context, establish
constraints, and guide large language models (LLMs) toward more useful outputs.

In this hands-on course, participants will learn practical techniques for
designing, testing, and refining prompts for workplace applications.
Participants will explore how prompt structure influences AI-generated
responses and how thoughtful prompt design can improve quality, consistency,
and efficiency.

**Learning objectives.** Participants will be able to:

1. Explain how large language models use prompts and context to generate responses.
2. Write clear, structured prompts that produce more useful and relevant outputs.
3. Apply prompting techniques to improve accuracy, consistency, format, and usefulness.
4. Refine prompts through iterative testing and evaluation.
5. Use prompting strategies that improve efficiency while maintaining output quality.

**Audience:** working professionals in mixed roles. No programming is assumed
or taught. **What a learner leaves with:** a tested prompt template for one
recurring task from their own job, that a colleague could use without help.

---

## Objective coverage

| Objective | Slides | Exercises | Status |
| --- | --- | --- | --- |
| 1. Explain how LLMs use prompts and context to generate responses | 10–16 (what an LLM is, prediction, context, strengths, limits, variation, demo), 23, 26 | 1, 2 | Covered |
| 2. Write clear, structured prompts that produce more useful and relevant outputs | 22–31 (the five parts, before and after, live build) | 3, 4 | Covered |
| 3. Apply prompting techniques to improve accuracy, consistency, format, and usefulness | Accuracy: 41–42, 53–58 · Consistency: 39–40, 45 · Format: 28, 40 · Usefulness: 43–44 | 5, 6, 7, 8 | Covered |
| 4. Refine prompts through iterative testing and evaluation | 43–44 (iterate), 56 (four-question check), 60–62 (bake-off), 81 (capstone checklist) | 6, 8, 11 | Covered |
| 5. Use prompting strategies that improve efficiency while maintaining output quality | **79–80 (new)**, 81–82, 90 | 11 | **Gap found and filled** |

**The gap.** Before this revision, Objective 5 had only scattered content:
[brackets] for reuse in the capstone checklist and demo, and a prompt library
on the final slide. No slide taught efficiency, or how to keep quality while
going faster. Two slides are drafted to cover it:

- **Slide 79, Reuse, don't rewrite:** turning a good prompt into a template
  with [brackets], tested so a colleague could use it.
- **Slide 80, Faster, without getting worse:** batching, ready-to-use formats,
  a prompt library, and running the four-question check so speed doesn't cost
  quality.

They sit in Module 6, just before the capstone checklist, because the capstone
is where learners build a reusable prompt. To keep the day on time, the
capstone build (Exercise 11) drops from 22 to 18 minutes.

**Module 5 maps to no numbered objective.** It serves the charter's fixed
constraint, *no confidential data in any prompt*, and the original brief's
responsible-use module.

**Description coverage**

| Charter description | Where |
| --- | --- |
| Quality of results depends on the quality of instructions | Slides 22–23, 31 |
| Communicate intent clearly | 24, 27 |
| Provide appropriate context | 12, 26 |
| Establish constraints | 29 |
| Guide LLMs toward more useful outputs | 30–31, 44 |
| Hands-on | Every module is at least 40% hands-on; 12 timed exercises |
| Designing, testing, and refining prompts | Design: Module 2 · Testing: 56, 59–62 · Refining: 43–47, 83 |
| Workplace applications | Every example is a workplace task; Exercises 4, 6, 11 use the learner's own job |
| How prompt structure influences responses | 31 (live build), Exercise 3 |
| Quality, consistency, and efficiency | Quality: 56 · Consistency: 39–40, Exercise 5 · Efficiency: 79–80 |
| Leaves with a tested template a colleague could use without help | 79, 81, Exercise 11 (*done when* test) |

**Where the deck and charter disagree.** These are outside this revision and
were not changed:

| Charter says | Deck does | Decision needed |
| --- | --- | --- |
| About six hours of class | 6.5 instructional hours, 8:30–4:30 | Trim 30 minutes, or confirm 6.5 |
| Learners use a free ChatGPT account | Learners choose ChatGPT, Claude, or Copilot | Standardize on ChatGPT, or confirm the choice |
| Two groups; the instructor runs group prompts on Claude and projects them | Tables of 4–5 run their own prompts | Restructure the bake-off and Module 6 presentations, or confirm |
| *AI Ethics and Governance* is out of scope | Slide 55 (bias) and Module 5 touch on it | Keep as practical data handling, or trim |
| The approved objectives above | [COURSE-BRIEF.md](../../COURSE-BRIEF.md) and the [syllabus](../handouts/syllabus.md) list differently worded outcomes | Replace them with the charter's five |

---

## How to read this deck

- **On slide:** the text that appears on screen, at most 25 words including
  the title, one idea per slide.
- **Layout:** on the title slide, section dividers, and YOUR TURN slides, the
  UNO layout and the logo's alt text. All other slides use the standard
  content layout under [Brand and accessibility](#brand-and-accessibility).
- **Notes (N min):** the minutes for that slide, then talking points, common
  student mistakes (*Common mistake* or *Watch for*), and facilitation tips
  (*Tip*).
- **Exercise slides** start with `YOUR TURN · ⏱ N MIN · format`. The full
  exercise (task, time, format, template or starter prompt, and suggested
  answers marked *instructor only*) follows the on-slide text.

Every module follows the same pattern: a **warm-up** question or poll, a
**concept** of 15 minutes or less, a **live demo**, **hands-on exercises**
(at least 40% of the module), then 10 minutes of **share-out and questions**
ending on a recap slide.

**Ground rules built into every exercise.** Made-up data only (Brightline
Supplies, Priya, Marcus, Jordan Lee are all fictional, and learners use
invented details for their own tasks). Free tools only. Demos never promise a
specific output; each demo's notes say what to do whichever way the run goes.

**Before teaching:** rehearse the four demos (slides 16, 31, 45, 58) on the
room's Wi-Fi; build your own capstone example for slide 82; print the Exercise
1 cards, the Exercise 7 texts, the bake-off brief, the Exercise 9 scenarios,
the syllabus, and the handout; add the feedback link or QR code to slide 89;
and check that the resource searches on slide 90 still lead to the official
guides.

---

## Brand and accessibility

UNO brand values from the official online brand guide. Sources and status for
each are in the resolution log in [../brand/README.md](../brand/README.md).

| Element | Value |
| --- | --- |
| Primary color | Black, #000000. Black, gray, or white must dominate |
| Secondary colors | Dark gray #474648 · Light gray #BCBBBA · White #FFFFFF |
| Accent | UNO red #DE1D24 (PMS 186). At most 20% of a slide, never a slide background, never text on black (4.31:1 fails) |
| Fonts | URW Grotesk: Medium for headings, Regular or Light for body. PowerPoint fallback: Helvetica (or Arial Narrow) |
| Logos | University Logo, Campus Icon, and Logo Lock-up from UNO's official Logos page: two-color on white, all-white on black |
| Clear space | Logo and Lock-up: height of the "O" in "Omaha". Campus Icon: width of the O's bands |
| Minimum size | Logo 1 in wide · Lock-up 1.75 in · Campus Icon 0.35 in print, 38 px digital |

**Layouts**

- **Title:** black background, white text, all-white Logo Lock-up.
- **Section divider:** black background, white text, all-white University
  Logo, optional red accent rule.
- **YOUR TURN:** white background, dark gray banner with white text, thin
  red accent bar, black body text.
- **Standard content:** white background, black URW Grotesk text.

**Accessibility.** Every text pair here passes 4.5:1: white on black 21:1,
white on dark gray 9.39:1, black on light gray 10.96:1, black on white 21:1.
Body text is at least 24 pt. Every logo has the alt text "University of
Nebraska Omaha", and the feedback QR code has its own alt text (slide 89).
Color is never the only signal: traffic-light colors always come with their
words.

**Still open:** where the logo sits on each layout (item 10), print body size
(item 16), and whether the syllabus fits two pages in the brand fonts (item
18). See [NEEDS-CONFIRMATION.md](../../NEEDS-CONFIRMATION.md).

---

## Opening

8:30–8:45 · 15 min · Slides 1–7

Gets everyone settled, sets a low-pressure tone, and makes sure every laptop
has a working AI tool before Module 1.

---

### Slide 1 — Prompt Engineering for Work

**On slide:**
> Prompt Engineering for Work
> Getting useful results from AI tools
> [Date] · [Instructor name]

**Layout:** Title (see [Brand and accessibility](#brand-and-accessibility)). Black background, white text (21:1). Title in URW Grotesk Medium; subtitle and date in URW Grotesk Regular, 24 pt minimum. All-white UNO Logo Lock-up (`uno-lock-up-white.png`), at least 1.75 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position on the slide: NEEDS CONFIRMATION (item 10).

**Notes (1 min, during arrival).**
- Have this up as people arrive, with Wi-Fi details beside it.
- Greet people individually at the door. Ask which AI tool they plan to use today.
- *Watch for:* people sitting alone at the back. Invite them toward a table; most exercises are in pairs.
- *Tip:* start exactly on time, even with empty seats. It tells the room the schedule is real.

---

### Slide 2 — Welcome

**On slide:**
> Welcome! No experience needed.
> Today is hands-on: short explanations, lots of practice.

**Notes (2 min).**
- Introduce yourself in under a minute: name, role, one way you use AI at work.
- Say it plainly: "If you've never used an AI tool, you're in exactly the right place. Nobody here is expected to know anything yet."
- Define **AI tool** the first time: "a program you type a request into, like ChatGPT, Claude, or Copilot, that writes a response back."
- *Watch for:* experienced users signalling boredom. Tell them they'll get stretch tasks and that their experience will help their partners.
- *Tip:* admit something you got wrong with AI once. It lowers the stakes for everyone.

---

### Slide 3 — Warm-up: How do you feel about AI?

**On slide:**
> Quick poll: How do you feel about AI right now?
> 😟 Nervous · 🤔 Curious · 🙂 Comfortable · 🚀 Excited

**Notes (3 min).**
- Run as a show of hands, or a live poll if you have one set up.
- Read the result back out loud without judging it: "Lots of curious, a few nervous. Perfect. Both are reasonable."
- Ask one or two volunteers: "What's one thing you've heard about AI that worries you?" Write answers on a flipchart labelled **Parking lot**. Promise to come back to them (Module 4 and 5 answer most).
- *Watch for:* one person taking over with a long story. Thank them and move on: "Great one for the parking lot."
- *Tip:* keep the parking lot visible all day and tick items off as they're answered.

---

### Slide 4 — Today's agenda

**On slide:**
> 8:45 How AI works · 9:45 Good prompts · 11:00 Techniques
> 1:00 Checking outputs · 2:00 Using AI responsibly · 3:00 Capstone · 4:30 Finish

**Notes (2 min).**
- Walk through quickly. Point out the two 15-minute breaks (10:45 and 2:45) and lunch (12:00–1:00).
- Each module follows the same rhythm: short explanation, a demo, then you try it, then we share.
- *Watch for:* questions about leaving early. Point them to the capstone at 3:00; it's the payoff.
- *Tip:* leave the agenda printed on each table so you don't have to come back to this slide.

---

### Slide 5 — What you'll leave with

**On slide:**
> By 4:30 you'll have one tested, reusable prompt for a real task from your own job.

**Notes (1 min).**
- This is the goal of the day. Everything builds toward it.
- Ask everyone to think now about one task they do every week that involves writing, summarizing, or organizing information. They don't need to decide yet; they'll pick in Module 2.
- *Watch for:* people worrying they don't have a "good enough" task. Reassure them: emails, meeting notes, and reports all count.
- *Tip:* give two examples: "a weekly status email" and "turning messy notes into action items."

---

### Slide 6 — Ground rules

**On slide:**
> Use made-up details, never real confidential data.
> Every question is welcome.
> Try it before perfecting it.

**Notes (2 min).**
- **Made-up data:** today, never paste real customer names, colleague details, or company documents. Use fictional ones. We'll cover why in Module 5.
- **Questions:** say there are no silly questions, and mean it. Questions you can't answer go in the parking lot.
- **Try it first:** the fastest way to learn is to send a prompt and see what happens. A rough attempt beats a blank screen.
- *Watch for:* people who already pasted work material during the tool check. Gently ask them to delete that chat.
- *Tip:* point at this slide again before every exercise that uses people's own tasks.

---

### Slide 7 — Tool check

**On slide:**
> Open your AI tool. Type: "Hello! Introduce yourself in one sentence."
> Got a reply? Thumbs up 👍

**Notes (4 min).**
- Everyone opens ChatGPT, Claude, or Copilot in a browser. Free versions are fine for everything today.
- Define **chatbot**: "an AI tool you talk to in a back-and-forth conversation."
- Walk the room. Anyone stuck: pair them with a neighbour now and fix their login at the first break.
- *Watch for:* account sign-up screens, email verification codes, and work laptops that block AI sites. Have the backup plan ready: pair up.
- *Tip:* people's replies will all differ. Point that out: "Same request, different answers. Hold that thought; it's the first thing we'll explain."

---

## Module 1 — How AI tools work

8:45–9:45 · 60 min · Slides 8–20 · Objective 1
Warm-up 4 · Concept 12 · Demo 7 · Hands-on 27 (45%) · Share-out and questions 10

**Learners leave able to** explain in plain words how an AI chatbot produces an
answer, and name tasks it does well and tasks it does badly.

---

### Slide 8 — Module 1: How AI tools work

**On slide:**
> Module 1
> How AI tools work, and what they can and can't do

**Layout:** Section divider. Black background, white URW Grotesk Medium text (21:1). Optional UNO red (#DE1D24) accent rule, non-text, under 20% of the slide. All-white University Logo (`uno-logo-white.png`), at least 1 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position: NEEDS CONFIRMATION (item 10).

**Notes (under 1 min).**
- Transition: "Before we write better requests, let's look at what's on the other end."
- *Tip:* keep transitions short. The warm-up does the real opening.

---

### Slide 9 — Warm-up: What have you asked AI to do?

**On slide:**
> Name one thing you've asked AI to do.
> Never used it? What would you ask?

**Notes (4 min).**
- Go round quickly, or have people call out. Write answers on the flipchart in two columns, without labelling them yet: things AI is usually good at (left) and things it's usually bad at (right).
- At the end, reveal the column labels. That sorting is today's module in miniature.
- *Watch for:* people embarrassed they've never used it. Their "what would you ask" answers are just as useful.
- *Tip:* keep it moving. One phrase per person, not stories.

---

### Slide 10 — What is an LLM?

**On slide:**
> LLM = Large Language Model
> A program trained on huge amounts of text to predict likely next words.

**Notes (2 min).**
- Define it plainly: ChatGPT, Claude, and Copilot are all built on LLMs. "Large" because it learned from an enormous amount of writing; "language model" because it models how language usually goes.
- Analogy: phone autocomplete suggests your next word. An LLM is autocomplete scaled up enormously, predicting whole paragraphs.
- *Common mistake:* thinking the AI "understands" or "knows" like a person does. It's very good at producing text that sounds right.
- *Tip:* avoid technical terms like "neural network" or "parameters". They don't help anyone write a better prompt.

---

### Slide 11 — It predicts. It doesn't look things up.

**On slide:**
> It writes what sounds likely.
> It doesn't check a database of facts.

**Notes (2 min).**
- The single most important idea of the day. When it answers, it's generating the most plausible-sounding text, not retrieving a verified fact.
- That's why it can be fluent, confident, and wrong all at once.
- Some tools can search the web for some questions. Even then, it's still writing its own summary of what it found, and that summary can be wrong.
- *Common mistake:* treating the chatbot like a search engine. Search engines point to sources; chatbots write new text.
- *Tip:* say "it predicts, it doesn't look up" out loud a few times today. Learners will start repeating it.

---

### Slide 12 — It only knows what you tell it

**On slide:**
> It doesn't know your job, your company, or your audience.
> Unless you tell it.

**Notes (2 min).**
- Define **prompt**: "the request or instructions you type into the AI tool."
- The AI knows general things from its training. It knows nothing about your team, your customer, your deadline, or your boss's preferences, unless you put that in the prompt.
- Within one conversation, it can see what's been said so far. In a new chat, it usually starts fresh.
- *Common mistake:* expecting it to remember last week's conversation. Some tools have memory features, but don't rely on them.
- *Tip:* "If a new colleague wouldn't know it, the AI doesn't know it either."

---

### Slide 13 — Good at

**On slide:**
> ✅ Drafting · ✅ Summarizing · ✅ Rewording · ✅ Brainstorming · ✅ Explaining · ✅ Organizing messy notes

**Notes (2 min).**
- Give a one-line example of each: draft a reply to a customer; summarize long meeting notes; make an email friendlier; brainstorm 10 event names; explain a term simply; turn scattered notes into a list.
- Common thread: it's strong at shaping language when *you* provide the facts.
- *Tip:* point back to the flipchart's left column from the warm-up.

---

### Slide 14 — Struggles with

**On slide:**
> ⚠️ Recent events · ⚠️ Exact facts and numbers · ⚠️ Your private information · ⚠️ Judgment calls

**Notes (2 min).**
- **Recent events:** its training stops at a certain date. It may not know about anything since, unless the tool searches the web.
- **Exact facts:** dates, figures, quotes, and references can be invented. More on this in Module 4.
- **Your information:** it can't see your files, systems, or inbox unless you give it the content.
- **Judgment:** legal, medical, financial, or HR decisions need a qualified human.
- *Common mistake:* "It said it so confidently, it must be right." Confidence is just a writing style.
- *Tip:* point at the flipchart's right column.

---

### Slide 15 — Same prompt, different answers

**On slide:**
> Ask the same thing twice, get two different answers.
> That's normal, not broken.

**Notes (2 min).**
- Connect to the tool check: everyone typed the same "Hello" and got different replies.
- Because it predicts likely words, with some built-in variety, every run can differ.
- What this means for you: if you don't like an answer, ask again or ask differently. And for anything important, don't assume one answer is *the* answer.
- *Common mistake:* thinking a different answer means you did something wrong.
- *Tip:* this sets up the demo. Move straight to it.

---

### Slide 16 — DEMO: Two runs and an invented fact

**On slide:**
> Live demo
> Same question twice · Asking about something that doesn't exist

**Notes (7 min).**
- **Part 1 (3 min):** type "Suggest a name for a team newsletter at a small accounting firm." Run it, then open a new chat and run it again. Ask the room: what's the same, what's different?
- **Part 2 (4 min):** type "Summarize the main findings of the 2019 Hartwell Report on remote work productivity." (This report is made up.) Many tools will invent a confident summary; some will say they can't find it. Either way, ask: "How would you know if this was real?"
- Don't promise the room a specific result. Whatever happens is the lesson: if it invents, that's prediction without lookup; if it declines, point out that it won't always.
- *Watch for:* learners concluding "AI is useless." Rebalance: it's a powerful drafting tool you double-check.
- *Tip:* run both prompts once before class so you know roughly what your tool does, but don't rely on a repeat.

---

### Slide 17 — YOUR TURN: Can or can't? ⏱ 10 MIN

**On slide:**
> YOUR TURN · ⏱ 10 MIN · Pairs
> Sort 10 tasks: Great at it / Use with care / Can't do alone

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 1 — Can or can't?**

| | |
| --- | --- |
| **Task** | Sort ten task cards into three piles: *Great at it*, *Use with care*, *Can't do alone*. Be ready to explain one choice |
| **Time** | 10 minutes: 6 to sort, 4 to compare with the pair next to you |
| **Format** | Pairs |
| **Materials** | One set of cards per pair (print the list below and cut it up), or the list on the handout |

**The ten cards:**

1. Draft a polite reply to a customer complaint
2. Tell you this morning's exchange rate
3. Summarize a page of meeting notes you paste in
4. Brainstorm 15 names for a team event
5. Decide whether to fire an employee
6. Explain "net promoter score" in simple words
7. Know what your company's travel policy says
8. Calculate a payroll total you'll submit without checking
9. Translate a short note to a colleague into Spanish
10. Remember what you asked it last month

**Suggested answers (instructor only):** Great at it: 1, 3, 4, 6. Use with
care: 9 (check with a speaker for anything important), 2 and 10 (depends on the
tool's search and memory features; never assume). Can't do alone: 5
(judgment), 7 (unless you paste the policy), 8 (verify any number you'll rely
on).

**Notes (10 min).**
- Hand out cards before you say "go" so you're not talking over the activity.
- At 6 minutes, call "compare with the pair next to you."
- *Common mistake:* putting everything in *Great at it* or everything in *Can't*. Ask: "When would this one go wrong?"
- *Tip:* there's room for disagreement on 2, 9, and 10. That's good; debate is the point.

---

### Slide 18 — YOUR TURN: Test the limits ⏱ 17 MIN

**On slide:**
> YOUR TURN · ⏱ 17 MIN · Pairs
> Run three prompts. Note what worked, what was wrong, how you could tell.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 2 — Test the limits**

| | |
| --- | --- |
| **Task** | Run three prompts and fill in the notes table for each |
| **Time** | 17 minutes: about 5 per prompt, 2 to agree your best finding |
| **Format** | Pairs, one laptop, take turns typing |
| **Template** | The three starter prompts and notes table below (also on the handout) |

**Starter prompts:**

1. *Summarize:* "Summarize this in one sentence: Brightline Supplies will move
   its warehouse from Elm Street to Harbor Road on March 3. Deliveries will
   pause for two days. Customers with urgent orders should call Dana Ortiz in
   customer service before February 28." (Fictional.)
2. *Recent facts:* "What were the top three news stories this week?"
3. *References:* "List three books about workplace communication, with the
   author and year for each."

**Notes table:**

| Prompt | What worked | What was wrong or doubtful | How could you tell? |
| --- | --- | --- | --- |
| 1 | | | |
| 2 | | | |
| 3 | | | |

**Notes (17 min).**
- Expect: prompt 1 goes well (all facts were provided). Prompt 2 varies by tool; some search, some say they can't, some guess. Prompt 3 may mix real and invented books.
- For prompt 3, pairs should pick one book and search for it in a normal web browser.
- *Common mistake:* pairs only reading the output without checking anything. Ask "How do you *know* that book exists?"
- *Tip:* fast pairs: ask the AI "Are you sure? How could I check that?" and note what happens.

---

### Slide 19 — Share-out and questions ⏱ 10 MIN

**On slide:**
> What surprised you?
> Which answer would you have trusted without checking?
> Questions?

**Notes (10 min).**
- Ask two or three pairs for their best finding from Exercise 2. Prioritize anyone who caught an invented book or a wrong fact.
- Draw out the pattern: prompt 1 worked because you gave it the facts. That's the bridge to Module 2.
- Open the floor for questions. Check the parking lot for anything Module 1 answered.
- *Watch for:* technical questions about how models are trained. Answer in one sentence and offer to talk at the break; it won't improve anyone's prompts today.
- *Tip:* if nobody speaks, cold-call by pair with a gentle question: "What did your table put in *Can't do alone*?"

---

### Slide 20 — Recap: Module 1

**On slide:**
> ✔ It predicts, it doesn't look up
> ✔ It only knows what you tell it
> ✔ Great for drafting, risky for facts

**Notes (1 min, inside the share-out time).**
- Read each line and connect it to something the room saw.
- Bridge: "If it only knows what you tell it, then *what* you tell it matters a lot. That's Module 2."
- *Tip:* leave this up while people stretch for 30 seconds before Module 2.

---

## Module 2 — Anatomy of a good prompt

9:45–10:45 · 60 min · Slides 21–35, then break (36) · Objective 2
Warm-up 3 · Concept 12 · Demo 8 · Hands-on 27 (45%) · Share-out and questions 10

**Learners leave able to** write a prompt with the five parts (role, context,
task, format, constraints) and turn a vague prompt into a clear one.

---

### Slide 21 — Module 2: Anatomy of a good prompt

**On slide:**
> Module 2
> Anatomy of a good prompt

**Layout:** Section divider. Black background, white URW Grotesk Medium text (21:1). Optional UNO red (#DE1D24) accent rule, non-text, under 20% of the slide. All-white University Logo (`uno-logo-white.png`), at least 1 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position: NEEDS CONFIRMATION (item 10).

**Notes (under 1 min).**
- Transition: "We saw it works best when you give it the facts. Now: what exactly should you give it?"

---

### Slide 22 — Warm-up: Rate this prompt

**On slide:**
> Rate this prompt from 1 to 5:
> "Write an email."
> What's missing?

**Notes (3 min).**
- Fingers up, 1 to 5. Most will say 1 or 2.
- Ask "What's missing?" and write answers on the flipchart: who it's to, what it's about, how long, what tone, what result you want.
- Keep that list; you'll map it onto the five parts in two slides.
- *Tip:* if someone says 5 ("it works!"), agree it'll produce *an* email, then ask "Would you send it?"

---

### Slide 23 — Vague in, vague out

**On slide:**
> A vague request gets a generic answer.
> The AI fills every gap with a guess.

**Notes (2 min).**
- When information is missing, the AI doesn't ask; it fills the gap with the most typical answer. That's why vague prompts produce bland, middle-of-the-road results.
- Analogy: asking a new temp to "write an email" with no other information. They'd do their best, but they'd guess.
- *Common mistake:* blaming the tool for a bad answer when the prompt left it guessing.
- *Tip:* "Every gap in your prompt is a guess in the answer."

---

### Slide 24 — The five parts

**On slide:**
> Role · Context · Task · Format · Constraints
> You don't always need all five. Know which one is missing.

**Notes (2 min).**
- Introduce the framework. Map the flipchart list from the warm-up onto it: "who it's to" is context, "how long" is a constraint, and so on.
- It's a checklist, not a formula. Short tasks might need two parts; important ones need all five.
- Memory aid: "**R**eal **C**olleagues **T**alk **F**or **C**larity", or just glance at the handout.
- *Common mistake:* thinking longer is always better. Clear beats long.
- *Tip:* point to the framework on the handout. It stays on their desk all day.

---

### Slide 25 — Role

**On slide:**
> ROLE: Who should the AI act as?
> "You are an experienced customer service manager."

**Notes (1.5 min).**
- A role sets the expertise, vocabulary, and point of view.
- Be specific and realistic: "an HR coordinator at a 50-person company" beats "the world's best HR genius."
- *Common mistake:* over-the-top roles ("world-class expert") as if flattery helps. A realistic, specific role is what changes the output.
- *Tip:* sometimes the role is the audience instead: "Explain this as if to a new employee."

---

### Slide 26 — Context

**On slide:**
> CONTEXT: What's the situation?
> "A customer's order arrived two weeks late. They're a long-time client and upset."

**Notes (1.5 min).**
- Context is the background a colleague would need: who, what happened, why it matters, who the audience is.
- This is usually the most important part, and the one people leave out most.
- *Common mistake:* assuming the AI knows your company, your customer, or your history.
- *Tip:* ask "What would I tell a new colleague before handing them this?"

---

### Slide 27 — Task

**On slide:**
> TASK: What exactly should it do?
> "Write a reply apologizing and offering a 15% discount on their next order."

**Notes (1.5 min).**
- Start with a clear action verb: write, summarize, list, compare, rewrite, explain.
- One main task per prompt. If you need three things, ask in steps.
- *Common mistake:* vague verbs like "help with" or "look at."
- *Tip:* if you can't say the task in one sentence, split it.

---

### Slide 28 — Format

**On slide:**
> FORMAT: What should the result look like?
> "Under 150 words. Short paragraphs. End with a clear next step."

**Notes (1.5 min).**
- Format covers length, structure, layout: bullet list, table, email, three options, a subject line plus body.
- Asking for a format saves editing time afterwards.
- *Common mistake:* accepting a wall of text, then reformatting it by hand. Just ask.
- *Tip:* "Give me a table with columns X, Y, Z" is one of the most useful phrases there is.

---

### Slide 29 — Constraints

**On slide:**
> CONSTRAINTS: What are the rules?
> "Warm but professional. Don't blame the delivery company. No jargon."

**Notes (1.5 min).**
- Constraints are limits and must-haves: tone, words to avoid, things to include, things to leave out, reading level.
- Saying what *not* to do is often what fixes a disappointing answer.
- *Common mistake:* only saying what you want, never what you don't.
- *Tip:* when an output annoys you, turn the annoyance into a constraint.

---

### Slide 30 — Before and after

**On slide:**
> Before: "Write an email."
> After: Role + Context + Task + Format + Constraints
> (Full prompt on your handout.)

**Notes (1 min).**
- Read the full "after" prompt aloud so they hear it as one piece:
  *"You are an experienced customer service manager. A long-time client's order
  arrived two weeks late, and they're upset. Write a reply apologizing and
  offering a 15% discount on their next order. Keep it under 150 words, in short
  paragraphs, ending with a clear next step. Warm but professional; don't blame
  the delivery company; no jargon."*
- It's four sentences, not an essay.
- *Tip:* the next slide shows it running. Keep momentum.

---

### Slide 31 — DEMO: Build it live

**On slide:**
> Live demo
> One prompt, one part at a time

**Notes (8 min).**
- Start with "Write an email." and run it. Then add one part at a time (context, task, format, constraints, role), running after each addition.
- After each run, ask the room: "What changed? Better or worse?"
- If time is short, jump from the bare prompt straight to the full version.
- Don't promise a specific output. If an addition doesn't visibly help, say so: that's useful to know too.
- *Watch for:* learners copying every word you type. Tell them the full prompt is on the handout.
- *Tip:* make the font huge. Zoom the browser to 150% or more.

---

### Slide 32 — YOUR TURN: Fix the prompt ⏱ 12 MIN

**On slide:**
> YOUR TURN · ⏱ 12 MIN · Pairs
> Bad prompt → better prompt
> Use at least three of the five parts.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 3 — Fix-it: bad prompt vs. better prompt**

| | |
| --- | --- |
| **Task** | Pick two of the three bad prompts. Rewrite each using at least three of the five parts. Run the bad version and your better version, then compare |
| **Time** | 12 minutes: about 6 per prompt |
| **Format** | Pairs |
| **Template** | Bad prompts and rewrite grid below (also on the handout) |

**Bad prompts:**

- A. "Write a job posting."
- B. "Summarize this." (Paste the fictional Brightline warehouse notice from Exercise 2.)
- C. "Make this email better: *hey, the report is late again, need it asap.*"

**Rewrite grid:**

| Part | Your words |
| --- | --- |
| Role | |
| Context | |
| Task | |
| Format | |
| Constraints | |

**Notes (12 min).**
- Circulate and ask "Which part did you find hardest to fill in?" It's usually context.
- *Common mistake:* rewriting only by adding length ("Write a really good, detailed job posting"). Ask: "What does the AI know now that it didn't before?"
- *Common mistake:* inventing real details. Remind them: fictional company, fictional people.
- *Tip:* fast pairs do all three, then remove one part and see whether the result gets worse.

---

### Slide 33 — YOUR TURN: Your task, draft 1 ⏱ 15 MIN

**On slide:**
> YOUR TURN · ⏱ 15 MIN · Solo
> Pick a real work task. Write a five-part prompt. Run it.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 4 — Your own task, draft 1**

| | |
| --- | --- |
| **Task** | Choose one task you do regularly (an email, report, summary, or plan). Write a prompt for it using the five-part template. Run it once and save both the prompt and the output |
| **Time** | 15 minutes: 3 to choose, 8 to write, 4 to run and note results |
| **Format** | Solo |
| **Template** | "Your task" box on the handout |

**Starter template:**

> You are a [role].
> [Context: the situation, audience, and why it matters, with made-up names and details.]
> [Task: one clear action verb + what to produce.]
> Format: [length, structure, layout].
> Rules: [tone, must include, must avoid].

**Notes (15 min).**
- This prompt is the seed for the capstone. Tell people to keep it somewhere they can find it (a document, an email to themselves, or the handout).
- Remind them of the ground rule: replace real names and details with made-up ones.
- *Watch for:* people stuck choosing a task. Offer: weekly status update, meeting summary, reply to a common customer question, job posting, agenda for a meeting.
- *Common mistake:* picking something huge ("write our strategy"). Steer them to something they do weekly and could finish in under an hour.
- *Tip:* sit briefly with anyone who's staring at a blank page. Ask, "What did you write last Tuesday?"

---

### Slide 34 — Share-out and questions ⏱ 10 MIN

**On slide:**
> Which part made the biggest difference?
> Read us one "before" and "after."
> Questions?

**Notes (10 min).**
- Ask two pairs from Exercise 3 to read a before and after. Ask the room which part did the most work.
- Ask one or two volunteers from Exercise 4 to say what task they picked (task only, not the full prompt).
- Open for questions.
- *Watch for:* people apologizing for their prompt before reading it. Thank them warmly; it takes courage.
- *Tip:* the answer is usually "context." Name the pattern if the room finds it.

---

### Slide 35 — Recap: Module 2

**On slide:**
> ✔ Vague in, vague out
> ✔ Role · Context · Task · Format · Constraints
> ✔ Context matters most

**Notes (1 min, inside the share-out time).**
- Recap and bridge: "You now have a solid first draft. After the break: three techniques to make it better."

---

### Slide 36 — Break ⏱ 15 MIN

**On slide:**
> Break · 15 minutes
> Back at 11:00

**Notes (15 min).**
- Put a countdown timer on screen.
- Use the break to help anyone whose tool isn't working and check in with anyone who looked lost in Exercise 4.
- *Tip:* restart at 11:00 sharp, even if a few are still getting coffee.

---

## Module 3 — Techniques

11:00–12:00 · 60 min · Slides 37–49, then lunch (50) · Objectives 3, 4
Warm-up 3 · Concept 12 · Demo 7 · Hands-on 28 (47%) · Share-out and questions 10

**Learners leave able to** improve a prompt by adding examples, asking for
step-by-step work, and refining with follow-up messages.

---

### Slide 37 — Module 3: Techniques

**On slide:**
> Module 3
> Three techniques: examples, step-by-step, iteration

**Layout:** Section divider. Black background, white URW Grotesk Medium text (21:1). Optional UNO red (#DE1D24) accent rule, non-text, under 20% of the slide. All-white University Logo (`uno-logo-white.png`), at least 1 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position: NEEDS CONFIRMATION (item 10).

**Notes (under 1 min).**
- Transition: "The five parts give you a solid first draft. These three techniques get you from solid to *exactly what I wanted*."

---

### Slide 38 — Warm-up: When a draft misses

**On slide:**
> A colleague's first draft isn't quite right.
> What do you say to them next?

**Notes (3 min).**
- Collect answers: "Here's an example of what I mean," "Walk me through how you got there," "Shorter, and more formal," "Close, but change this part."
- Point out: those are the three techniques of this module. You already know how to do this with people.
- *Tip:* write the answers up and label them *Examples*, *Step-by-step*, and *Iteration* as they come in.

---

### Slide 39 — Technique 1: Show an example

**On slide:**
> Show, don't just tell.
> One or two examples teach the AI your style and format.

**Notes (2 min).**
- When describing what you want is hard ("professional but friendly"), *showing* it is easy. Paste one or two examples of what good looks like.
- You may hear this called **few-shot prompting**: "few shots" just means "a few examples."
- Works especially well for consistent formats: product descriptions, social posts, ticket summaries, action items.
- *Common mistake:* giving examples that are all nearly identical. The AI may copy them too closely. Use two that differ a little.
- *Tip:* label them clearly: "Here are two examples of the format I want:"

---

### Slide 40 — Examples in action

**On slide:**
> "Turn these notes into action items. Format like these:
> Priya — Send budget draft — Friday
> Marcus — Book venue — May 2"

**Notes (2 min).**
- Read the example aloud. Explain: the two sample lines show the pattern (Owner — Action — Due date) more clearly than any description could.
- These names are fictional, like all examples today.
- *Common mistake:* forgetting to paste the actual notes after the examples.
- *Tip:* "Format like these" plus two examples is a pattern people can reuse tomorrow.

---

### Slide 41 — Technique 2: Ask for step-by-step

**On slide:**
> For tricky problems, ask it to work through the steps before answering.

**Notes (2 min).**
- For problems with several parts (scheduling, comparing options, calculations, planning), asking it to "think step by step" or "show your reasoning" tends to produce more careful answers.
- The bonus: you can *see* the steps, so you can spot exactly where it went wrong.
- *Common mistake:* using it for simple tasks. A two-line email doesn't need step-by-step reasoning; it just makes the answer longer.
- *Tip:* some newer tools reason step by step automatically. Asking to *see* the steps still helps you check the work.

---

### Slide 42 — Step-by-step in action

**On slide:**
> "Here are three people's free times.
> Check each day step by step, then suggest the best meeting slot."

**Notes (2 min).**
- Walk through why this helps: the AI has to check each day rather than jump to an answer that sounds right.
- Even so, check the result against the calendars yourself. Step-by-step reduces mistakes; it doesn't remove them.
- *Tip:* "List the steps first, then give the answer" works too.

---

### Slide 43 — Technique 3: Iterate

**On slide:**
> The first answer is a draft.
> Iterate = improve it with follow-up messages.

**Notes (2 min).**
- Define **iterate**: "try, look at the result, adjust, try again."
- You don't need a perfect prompt first time. Send a good one, read the result, and say what to change.
- Change one thing at a time where you can, so you know what worked.
- *Common mistake:* starting a brand-new chat for every small fix and losing all the context. Follow up in the same chat unless it's gone badly off track.
- *Common mistake:* giving up after one disappointing answer.
- *Tip:* "Iteration is a conversation, not a do-over."

---

### Slide 44 — Useful follow-ups

**On slide:**
> "Make it shorter." · "More formal." · "Give me three options." · "What did you assume?" · "What's missing?"

**Notes (2 min).**
- These five follow-ups solve most problems.
- "What did you assume?" is powerful: it reveals the gaps the AI filled with guesses, which tells you what context to add.
- "What's missing?" or "What questions would you ask me?" gets the AI to help you improve your own prompt.
- *Tip:* these are on the handout. Encourage people to use them in the next exercise.

---

### Slide 45 — DEMO: Three techniques, one task

**On slide:**
> Live demo
> Messy notes → action items, using examples and follow-ups

**Notes (7 min).**
- Paste the messy meeting notes from Exercise 5 (below) with "Turn these into action items." Run it.
- Then add the two-example format from Slide 40. Run it again. Ask: "What changed?"
- Finally, iterate once: "Put them in order of due date, and flag any item with no owner."
- Don't promise a specific result. If the first output is already good, ask the room: "Is it consistent? Would the next run look the same?"
- *Tip:* this demo uses the same notes as Exercise 5, so learners see it done first.

---

### Slide 46 — YOUR TURN: Show, don't tell ⏱ 10 MIN

**On slide:**
> YOUR TURN · ⏱ 10 MIN · Pairs
> Run it without examples, then with two examples. Compare.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 5 — Show, don't tell**

| | |
| --- | --- |
| **Task** | Turn the fictional notes below into action items. First run with no examples, then add two examples of your own. Compare: which is more consistent and closer to what you'd use? |
| **Time** | 10 minutes |
| **Format** | Pairs |
| **Template** | Notes and example lines below (also on the handout) |

**Fictional meeting notes:**

> Team sync, Tuesday. Priya will draft the Q3 budget, due Friday. Venue for the
> offsite still not booked — Marcus said he'd look at the two options by May 2.
> Someone needs to email the caterer. Lena to update the client list before the
> Brightline call next Thursday. Also need new name badges, no owner yet.

**Starter prompt (with examples):**

> Turn these meeting notes into action items. Use exactly this format, one per
> line:
> Priya — Send budget draft — Friday
> Marcus — Book venue — May 2
> If there's no owner, write "UNASSIGNED".
> Notes: [paste notes]

**Notes (10 min).**
- *Common mistake:* pairs writing examples so different from each other that the format is unclear.
- Point out the extra instruction ("UNASSIGNED"): examples plus a rule for the awkward case is a strong combination.
- *Tip:* fast pairs try it in a second AI tool and compare.

---

### Slide 47 — YOUR TURN: Three rounds ⏱ 18 MIN

**On slide:**
> YOUR TURN · ⏱ 18 MIN · Solo
> Take your Module 2 prompt. Improve it in three rounds. Log each change.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 6 — Three rounds of iteration**

| | |
| --- | --- |
| **Task** | Run your Exercise 4 prompt again. Then improve it three times, using at least one technique from this module. After each round, note what you changed and whether it helped |
| **Time** | 18 minutes: about 5 per round, 3 to pick your best version |
| **Format** | Solo; check in with a neighbour at the halfway mark |
| **Template** | Iteration log on the handout |

**Iteration log:**

| Round | What I changed | Better, worse, or same? Why? |
| --- | --- | --- |
| 1 | | |
| 2 | | |
| 3 | | |

**Ideas for changes:** add an example of a good output · ask for step-by-step
reasoning · follow up with "What did you assume?" · add a missing part of the
five-part framework · turn something you didn't like into a constraint.

**Notes (18 min).**
- At 9 minutes, call a 1-minute neighbour check: "Show your neighbour your best round so far."
- *Common mistake:* changing five things at once, then not knowing which one helped. Encourage one change per round.
- *Common mistake:* not writing anything in the log. The log is what makes the capstone easy; insist gently.
- *Tip:* anyone whose prompt is already great: ask them to try to make it *shorter* without getting worse.

---

### Slide 48 — Share-out and questions ⏱ 10 MIN

**On slide:**
> Which change helped most?
> Which change made it worse?
> Questions?

**Notes (10 min).**
- Ask three people for their most helpful change. Then ask for one change that made it *worse*; those are just as instructive.
- Ask the room: "Who used an example? Who used 'What did you assume?'"
- Open for questions.
- *Tip:* celebrate the "worse" answers. They show people are experimenting properly.

---

### Slide 49 — Recap: Module 3

**On slide:**
> ✔ Show examples of what good looks like
> ✔ Ask for steps on tricky problems
> ✔ Iterate: one change at a time

**Notes (1 min, inside the share-out time).**
- Bridge: "After lunch, the question becomes: how do you know the output is actually right?"

---

### Slide 50 — Lunch ⏱ 60 MIN

**On slide:**
> Lunch · 60 minutes
> Back at 1:00
> Keep your prompt and iteration log handy.

**Notes (60 min).**
- Remind people to bring their prompt and log back; the capstone builds on them.
- *Tip:* during lunch, set the room up for the bake-off: groups of 4–5 at each table, one printed bake-off brief per table.

---

## Module 4 — Checking outputs

1:00–2:00 · 60 min · Slides 51–63 · Objectives 3, 4
Warm-up 3 · Concept 11 · Demo 5 · Hands-on 31 (52%) · Share-out and questions 10

**Learners leave able to** spot invented facts and biased wording in an AI
output, and check an output with four questions before using it. Starts with
energy after lunch: warm-up poll, short concept, then the bake-off.

---

### Slide 51 — Module 4: Checking outputs

**On slide:**
> Module 4
> Checking AI outputs: hallucinations, bias, verification

**Layout:** Section divider. Black background, white URW Grotesk Medium text (21:1). Optional UNO red (#DE1D24) accent rule, non-text, under 20% of the slide. All-white University Logo (`uno-logo-white.png`), at least 1 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position: NEEDS CONFIRMATION (item 10).

**Notes (under 1 min).**
- Transition: "This morning you got better outputs. This afternoon: how do you know a good-looking output is actually right?"
- *Tip:* stand up and move around for this one. Post-lunch energy is low.

---

### Slide 52 — Warm-up: Would you send it?

**On slide:**
> Poll: Would you send an AI-written email to your boss without reading it?
> Yes · Probably · Never

**Notes (3 min).**
- Stand-up poll: stand for "yes," half-stand for "probably," stay seated for "never." Gets people moving after lunch.
- Ask a "never" and a "yes": why?
- Close with: "Most of you said you'd read it. Today's question is *what to look for* when you read it."
- *Tip:* laugh with the room. Post-lunch, energy beats precision.

---

### Slide 53 — Fluent isn't the same as correct

**On slide:**
> AI writing sounds confident, even when it's wrong.
> Polish is not proof.

**Notes (2 min).**
- Recall Module 1: it predicts likely words. It's always fluent, but fluency says nothing about accuracy.
- People trust well-written text more. That's the trap.
- *Common mistake:* checking spelling and tone but not facts.
- *Tip:* "The better it sounds, the more carefully you check the facts."

---

### Slide 54 — Hallucination

**On slide:**
> Hallucination = when AI states something false or made-up as if it were true.
> Facts, numbers, quotes, sources.

**Notes (2 min).**
- Define the term plainly. It's the industry name, even though it's a bit dramatic.
- Most common: invented statistics, wrong dates, fake quotes, books or articles that don't exist, made-up policies or laws.
- Recall the demo's made-up report and Exercise 2's books.
- *Common mistake:* asking the AI "Is that true?" and accepting "Yes." It can be confidently wrong about its own answer too.
- *Tip:* anything you'd be embarrassed to get wrong in front of your boss, check outside the AI.

---

### Slide 55 — Bias

**On slide:**
> Bias = unfair patterns or assumptions in the output.
> AI learned from human writing, including its stereotypes.

**Notes (2 min).**
- Define it plainly. Examples: a job posting that uses language that discourages some applicants; assuming a nurse is "she" and an engineer is "he"; examples that only reflect one culture.
- It's often subtle: word choice, who gets mentioned, who's assumed to be the reader.
- *Common mistake:* thinking bias only means offensive content. Mostly it's quieter defaults.
- *Tip:* ask "Who might read this and feel left out?" Or ask the AI: "Review this for biased or exclusionary language."

---

### Slide 56 — The four-question check

**On slide:**
> 1. Accurate? 2. Complete? 3. Fair? 4. Fit for purpose?

**Notes (2 min).**
- **Accurate:** are the facts, numbers, and names right?
- **Complete:** did it do everything you asked? Did it leave out anything important?
- **Fair:** any biased, one-sided, or exclusionary wording?
- **Fit for purpose:** right tone, length, and audience? Would you actually use it?
- This check is on the handout. It's also how the bake-off will be judged.
- *Tip:* "Four questions, two minutes, every time it matters."

---

### Slide 57 — How to check

**On slide:**
> Compare with your source · Look it up independently · Ask an expert · Check the math yourself

**Notes (2 min).**
- The best check is against something *outside* the AI: your original document, a trusted website, a colleague, a calculator.
- Matching effort to stakes: a brainstorm needs no checking; a figure in a client report needs every number checked.
- *Common mistake:* asking the same AI to check itself and stopping there. That can help catch errors, but it isn't verification.

---

### Slide 58 — DEMO: Ask for sources, check one

**On slide:**
> Live demo
> Ask for sources. Check one. Real or invented?

**Notes (5 min).**
- Type: "Give me three statistics about employee burnout, with a source for each."
- Pick one source and search for it live in a browser. Does the source exist? Does it say what the AI claimed?
- Whatever happens is the lesson: a fake source shows hallucination; a real one shows checking is quick. If it's real but the number doesn't match, that's the most important outcome of all.
- Don't promise the room it will invent something.
- *Tip:* rehearse this once so you know how long a search takes on the room's Wi-Fi.

---

### Slide 59 — YOUR TURN: Spot the problems ⏱ 8 MIN

**On slide:**
> YOUR TURN · ⏱ 8 MIN · Pairs
> This AI summary has three problems. Find them.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 7 — Spot the problems**

| | |
| --- | --- |
| **Task** | Compare the source text with the AI's summary. Find the three problems and label each: wrong fact, invented detail, or missing point |
| **Time** | 8 minutes |
| **Format** | Pairs |
| **Materials** | Print or display both texts below |

**Source text (fictional):**

> Brightline Supplies' customer survey received 412 responses in September.
> 68% rated delivery speed as good or excellent, up from 61% in June. The most
> common complaint was unclear invoices. The team will redesign invoices by
> December. Satisfaction with phone support fell slightly.

**AI summary:**

> Brightline Supplies surveyed 421 customers in September. Satisfaction with
> delivery speed rose to 68%, the highest in the company's history. The top
> complaint was unclear invoices, which the team will redesign by December.

**Answers (instructor only):** (1) wrong fact: 421, not 412; (2) invented
detail: "the highest in the company's history" isn't in the source; (3) missing
point: phone support satisfaction fell.

**Notes (8 min).**
- *Common mistake:* reading only the summary. Insist they compare line by line with the source.
- Most pairs find the number; fewer catch the invented claim; the omission is the hardest. Ask: "What's in the source that isn't in the summary?"
- *Tip:* this is the four-question check in action: Accurate (number), Accurate (invented claim), Complete (omission).

---

### Slide 60 — YOUR TURN: Prompt bake-off ⏱ 15 MIN

**On slide:**
> YOUR TURN · ⏱ 15 MIN · Groups of 4–5
> 🏆 Prompt bake-off: same task for every group. Best output wins.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 8 — Prompt bake-off (part 1: build)**

| | |
| --- | --- |
| **Task** | Every group gets the same brief. Write the best prompt you can using everything from today, run it, iterate, and choose your single best output |
| **Time** | 15 minutes to build, then 8 to judge (next slide) |
| **Format** | Groups of 4–5. One typist; everyone contributes |
| **Template** | Bake-off brief below, printed one per table |

**Bake-off brief:**

> Write a welcome message for Jordan Lee, who starts Monday on the customer
> support team at Brightline Supplies (both fictional). Jordan is joining a
> team of six, works hybrid (office Tuesdays and Thursdays), and their manager
> is Sam Rivera. The message will be posted in the team's chat channel.

Groups may add reasonable made-up details but must flag them.

**Judging criteria (the four-question check):** Accurate to the brief ·
Complete · Fair and inclusive · Fit for purpose (would you post it as is?).

**Notes (15 min).**
- Read the brief aloud, then start the timer. Call time at 10 minutes left and 3 minutes left.
- Each group should keep their final prompt visible; they'll explain it.
- *Common mistake:* groups spending 12 minutes debating before running anything. At 5 minutes, ask any group that hasn't run a prompt yet to run one now.
- *Common mistake:* inventing details without flagging them. That counts against "Accurate."
- *Tip:* ask groups to paste their final output into a shared document or onto a slide so everyone can see it during judging.

---

### Slide 61 — YOUR TURN: Bake-off judging ⏱ 8 MIN

**On slide:**
> YOUR TURN · ⏱ 8 MIN · Everyone
> Read each output. Score it 1–5 on the four questions.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 8 — Prompt bake-off (part 2: judge)**

- Display each group's final output (not their prompt yet), without group names.
- Each person scores every output 1–5 on the four questions, using the scoring
  grid on the handout. Groups can't score their own.
- Tally by show of hands for each output's overall score, or use dot voting.

**Notes (8 min).**
- Keep judging brisk: about 1.5 minutes per output.
- Reveal the winner, then the winning group reads their prompt aloud.
- *Common mistake:* judging on style alone ("It's funny!"). Ask: "Was it accurate to the brief?"
- *Tip:* a small prize (chocolate, first pick of the parking lot questions) raises energy far more than it costs.

---

### Slide 62 — Share-out and questions: why did the winner win? ⏱ 10 MIN

**On slide:**
> What was different about the winning prompt?
> Which check caught the most problems?
> Questions?

**Notes (10 min).**
- The winning group reads their prompt. Ask the room to point at what made it work: more context, an example, a format, a constraint, or an iteration?
- Ask a lower-scoring group: "What would you change now that you've seen the winner?"
- Ask: "Did anyone's output include made-up details that weren't in the brief?" (Common: invented start times, office locations, or team names.)
- Open for questions.
- *Tip:* the goal isn't the winner. It's naming *why* one prompt beat another. Keep pulling the conversation back to the prompts.

---

### Slide 63 — Recap: Module 4

**On slide:**
> ✔ Fluent isn't correct
> ✔ Watch for hallucination and bias
> ✔ Four questions: Accurate · Complete · Fair · Fit

**Notes (1 min, inside the share-out time).**
- Bridge: "You know how to check what comes *out*. Next: being careful about what goes *in*."

---

## Module 5 — Using AI responsibly

2:00–2:45 · 45 min · Slides 64–75, then break (76) · Charter constraint: no confidential data
Warm-up 2 · Concept 10 · Demo 5 · Hands-on 18 (40%) · Share-out and questions 10

**Learners leave able to** decide what is safe to put into an AI tool, remove
sensitive details from a prompt, and know where to find their organization's
rules. General guidance, not legal advice: every workplace's rules differ.

---

### Slide 64 — Module 5: Using AI responsibly

**On slide:**
> Module 5
> Using AI responsibly: privacy, confidentiality, workplace rules

**Layout:** Section divider. Black background, white URW Grotesk Medium text (21:1). Optional UNO red (#DE1D24) accent rule, non-text, under 20% of the slide. All-white University Logo (`uno-logo-white.png`), at least 1 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position: NEEDS CONFIRMATION (item 10).

**Notes (under 1 min).**
- Transition: "This is the module that keeps you out of trouble. It's short, but it matters."
- *Tip:* keep the tone practical, not scary. The goal is confident, careful use, not fear.

---

### Slide 65 — Warm-up: Thumbs up or down?

**On slide:**
> 👍 or 👎?
> Pasting a customer's complaint, with their name and account number, into a free AI tool.

**Notes (2 min).**
- Thumbs vote. Most will vote down; a few may be unsure.
- Ask one "unsure" person why. Usually: "I don't know where it goes." That's exactly the next slide.
- *Tip:* don't reveal the "answer" yet. Let the module answer it.

---

### Slide 66 — Where do your words go?

**On slide:**
> What you type is sent to the company running the tool.
> It may be stored, reviewed, or used for training.

**Notes (2 min).**
- When you send a prompt, it leaves your computer and goes to the AI company's servers.
- Depending on the tool, your plan, and your settings, it may be stored, seen by staff for safety reviews, or used to train future models. Define **training**: "using text to teach future versions of the AI."
- Work accounts that your employer set up often have stronger protections than personal free accounts. Check rather than assume.
- *Common mistake:* treating the chat window like a private notepad.
- *Tip:* show where your tool's privacy or data settings are, without claiming exactly what they do. They change often.

---

### Slide 67 — Four kinds of information

**On slide:**
> 🟢 Public · 🟡 Internal · 🔴 Confidential · 🔴 Personal
> The redder it is, the more careful you are.

**Notes (2 min).**
- **Public:** already published (your website, a public job posting). Generally fine.
- **Internal:** everyday work material that isn't secret (meeting agendas, general process notes). Check your policy.
- **Confidential:** contracts, finances, strategy, anything under a non-disclosure agreement. Don't paste unless your employer explicitly approves the tool.
- **Personal:** names plus details about customers, patients, students, or employees: contact details, health, pay, performance. Don't paste.
- *Common mistake:* thinking "it's only one name" is fine. Combined with other details, one name can identify someone.

---

### Slide 68 — Know your workplace policy

**On slide:**
> Does your organization have an AI policy?
> Which tools are approved? Find out this week.

**Notes (2 min).**
- Many organizations now have an AI use policy: approved tools, banned uses, data rules, and whether you need to tell anyone.
- If there's no policy, ask your manager or IT before using AI with anything beyond public information.
- *Common mistake:* assuming "nobody said I couldn't" means "allowed."
- *Watch for:* people who say their workplace bans AI. Respect it; the skills still transfer to approved tools or personal use.
- *Tip:* this is one of the "next steps" on the final slide. Plant it now.

---

### Slide 69 — Strip it before you paste

**On slide:**
> Replace real details with placeholders:
> "Maria Chen, account 48213" → "[Customer], [account number]"

**Notes (1 min).**
- Define **redact**: "remove or hide sensitive details before sharing."
- Placeholders keep the prompt useful. The AI doesn't need the real name to write a good reply; you can add it back afterwards.
- The name in the example is fictional.
- *Common mistake:* removing the name but leaving enough other details (job title, small town, specific incident) to identify the person anyway.
- *Tip:* "Could someone who knows the situation guess who this is?" If yes, remove more.

---

### Slide 70 — Be open about AI use

**On slide:**
> You're responsible for what you send.
> Follow your workplace's rules on telling people you used AI.

**Notes (1 min).**
- AI drafted it, but your name is on it. Accuracy, tone, and fairness are on you.
- Some workplaces require you to disclose AI use for certain work; some clients or schools do too.
- *Common mistake:* "The AI wrote it" as an excuse for a mistake. It doesn't work.

---

### Slide 71 — DEMO: Redact a prompt

**On slide:**
> Live demo
> A risky prompt, cleaned up, still useful

**Notes (5 min).**
- Show the risky prompt from Exercise 10 (below) on screen. **Don't** run it. Ask the room to call out each sensitive detail.
- Rewrite it live with placeholders. Run the clean version.
- Point out: the reply is just as useful. Add the real details back in your own email program, not in the AI.
- *Tip:* this demo uses fictional data, but treat it as if it were real. Modelling the habit matters more than the content.

---

### Slide 72 — YOUR TURN: Traffic light ⏱ 10 MIN

**On slide:**
> YOUR TURN · ⏱ 10 MIN · Small groups
> Eight scenarios. Green, yellow, or red?

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 9 — Traffic light**

| | |
| --- | --- |
| **Task** | For each scenario, decide: 🟢 go ahead, 🟡 check your policy or redact first, 🔴 don't put it in an AI tool. Note one reason for each |
| **Time** | 10 minutes |
| **Format** | Small groups of 3–5 (your bake-off table) |
| **Materials** | The scenario list below, printed one per table, or on screen |

**Scenarios:**

1. Brainstorm ideas for a team lunch
2. Rewrite your company's public job posting to sound friendlier
3. Summarize internal meeting notes that mention no names
4. Draft a reply to a customer, pasting their full email with name and address
5. Paste a supplier contract marked "Confidential" and ask for a summary
6. Write an employee's performance review using their name and specific incidents
7. Polish your own résumé
8. Analyze totals from an anonymous staff survey

**Suggested answers (instructor only):** 🟢 1, 2, 7. 🟡 3 and 8 (check policy;
make sure nothing identifies anyone). 🔴 4 (redact first, then it becomes 🟡),
5 (unless an approved work tool), 6 (personal and sensitive).

**Notes (10 min).**
- *Common mistake:* marking everything red out of caution. Ask: "What's the actual risk here?" Overcaution means missing real benefits.
- There's genuine room for debate on 3, 7, and 8. Let groups disagree; the reasoning matters more than the color.
- *Tip:* ask groups to mark which scenarios could become green or yellow with redaction.

---

### Slide 73 — YOUR TURN: Clean this prompt ⏱ 8 MIN

**On slide:**
> YOUR TURN · ⏱ 8 MIN · Pairs
> Remove every sensitive detail. Keep the prompt useful.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 10 — Clean this prompt**

| | |
| --- | --- |
| **Task** | Rewrite the risky prompt below so it contains no personal or confidential details but still gets a useful result. Then check your own Module 2 prompt the same way |
| **Time** | 8 minutes: 5 for the risky prompt, 3 for your own |
| **Format** | Pairs |
| **Template** | Risky prompt below (also on the handout) |

**Risky prompt (all details fictional):**

> Write a reply to Maria Chen (maria.chen@email.example, 402-555-0187),
> account 48213. She's upset that her refund for her knee brace hasn't
> arrived. She mentioned her surgery is next week. Our manager Tom Becker
> approved a $40 credit.

**One clean version (instructor only):**

> Write a reply to a customer who is upset that a refund for a medical product
> hasn't arrived and who needs it soon. Our manager has approved a [amount]
> credit. Keep it warm, apologetic, and under 120 words. Use [Customer name] as
> a placeholder.

**Notes (8 min).**
- Items to remove: name, email, phone, account number, health details (knee brace, surgery), manager's name, exact amount (optional).
- *Common mistake:* removing the name and email but keeping the surgery detail. Health information is among the most sensitive.
- *Tip:* the last 3 minutes are the real point: people check their *own* capstone prompt.

---

### Slide 74 — Share-out and questions ⏱ 10 MIN

**On slide:**
> Which scenario caused the most debate?
> What surprised you about your own prompt?
> Questions?

**Notes (10 min).**
- Ask each group for the scenario they argued about most and where they landed.
- Ask: "Did anyone find something in their own prompt they needed to remove?"
- Return to the warm-up: "So, the customer complaint with a name and account number?" (Red as written; yellow once redacted, if policy allows.)
- Check the parking lot: many morning worries are answered by now. Tick them off.
- *Tip:* questions about specific laws or company policies: say you're not giving legal advice and point them to their IT, legal, or compliance team.

---

### Slide 75 — Recap: Module 5

**On slide:**
> ✔ What you type leaves your computer
> ✔ No personal or confidential data
> ✔ Use placeholders · Know your policy

**Notes (1 min, inside the share-out time).**
- Bridge: "After the break, you'll put the whole day together: your own task, your best prompt."

---

### Slide 76 — Break ⏱ 15 MIN

**On slide:**
> Break · 15 minutes
> Back at 3:00 for the capstone
> Have your prompt and iteration log ready.

**Notes (15 min).**
- Countdown timer on screen.
- Use the break to check on anyone without a usable capstone task. Help them pick one now.
- *Tip:* restart on time. The capstone needs every minute.

---

## Module 6 — Capstone

3:00–4:00 · 60 min · Slides 77–86 · Objectives 4, 5
Warm-up 3 · Concept 9 · Demo 5 · Hands-on 33 (55%) · Share-out and questions 10

**Learners leave able to** produce a tested, reusable prompt for one real task
from their own job, and explain the choices behind it. Slides 79–80 are new
(Objective 5); to fit them, the capstone build (Exercise 11) went from 22 to 18
minutes. With 15–25 learners, presentations happen at tables in groups of 4–5;
three volunteers present to the whole room in the closing.

---

### Slide 77 — Module 6: Capstone

**On slide:**
> Module 6 · Capstone
> Your task. Your prompt. Everything from today.

**Layout:** Section divider. Black background, white URW Grotesk Medium text (21:1). Optional UNO red (#DE1D24) accent rule, non-text, under 20% of the slide. All-white University Logo (`uno-logo-white.png`), at least 1 in wide, clear space equal to the height of the "O" in "Omaha". Alt text: "University of Nebraska Omaha". Position: NEEDS CONFIRMATION (item 10).

**Notes (under 1 min).**
- Transition: "This is what the whole day was for."
- *Tip:* say plainly that nobody's capstone needs to be perfect. It needs to be useful to them.

---

### Slide 78 — Warm-up: Your task in five words

**On slide:**
> Your capstone task, in five words or fewer.
> Go!

**Notes (3 min).**
- Quick-fire round: everyone says their task in five words. ("Weekly sales update for managers." "Reply to refund requests.")
- Hearing everyone's tasks shows the range and gives stuck people ideas.
- *Watch for:* anyone without a task. Offer one on the spot: "summarize your weekly meeting notes."
- *Tip:* with 25 people, this takes about 3 minutes if you keep it moving. Don't comment on each one.

---

### Slide 79 — Reuse, don't rewrite

**On slide:**
> Save time: turn a good prompt into a template.
> Keep what stays the same. [Bracket] what changes.

**Notes (2 min).** New for Objective 5.
- Name the failure first: rewriting the same prompt from scratch every week wastes the time AI was supposed to save, and each rewrite drops something that worked.
- A template keeps the parts that made it good (role, context, format, rules) and puts [brackets] around what changes: this week's numbers, the customer's issue, the meeting notes.
- Example: a weekly status update. Everything stays except [this week's wins], [blockers], and [next week's plan].
- The course promises you leave with a template a colleague could use without help. Test it: could someone else fill in the brackets without asking you?
- *Common mistake:* bracketing too much, so the template loses the context that made the output good.
- *Tip:* try the template with two different sets of details. If the second result is worse, the template lost something.

---

### Slide 80 — Faster, without getting worse

**On slide:**
> Batch similar items · Ask for ready-to-use formats · Keep a prompt library
> Then run the four checks.

**Notes (2 min).** New for Objective 5.
- **Batch:** handle several similar items in one prompt ("Draft replies to these three questions"). Keep batches small, about three to five; long batches tend to get sloppy toward the end.
- **Ready-to-use format:** ask for the exact shape you'll paste (a table, an email with a subject line) so you don't reformat by hand.
- **Prompt library:** save prompts that worked in one document, with [brackets]. Next time you start from a tested prompt, not a blank box.
- **Quality first:** a faster prompt only counts if its output still passes the four-question check. Speed that creates rework isn't efficiency.
- *Common mistake:* using AI for a task that's quicker to just do, like a two-line reply.
- *Tip:* time yourself once, with and without the template. The difference is the case for using it.

---

### Slide 81 — The capstone checklist

**On slide:**
> ☐ Five parts · ☐ At least one technique · ☐ Iterated twice · ☐ Four-question check · ☐ Privacy check

**Notes (5 min).**
- Walk through each box. This checklist is on the handout.
- **Five parts:** role, context, task, format, constraints (or a clear reason for leaving one out).
- **One technique:** an example, step-by-step, or a planned follow-up.
- **Iterated twice:** at least two rounds of improvement, logged.
- **Four-question check:** accurate, complete, fair, fit for purpose.
- **Privacy check:** no real personal or confidential details; placeholders where needed.
- Add: make it reusable (slides 79–80). Put [brackets] around the parts that change each time (the date, the customer's issue, the notes), so you can reuse the prompt next week.
- **The charter's test:** could a colleague use this prompt without asking you anything? That's what the course promises you leave with.
- *Common mistake:* starting over from scratch. Build on the Exercise 4 and 6 prompt.

---

### Slide 82 — DEMO: A finished capstone

**On slide:**
> Live demo
> One task, start to finish, in five minutes

**Notes (5 min).**
- Show your own example capstone, built in advance. A good one: a reusable weekly status update prompt with [brackets] for this week's details.
- Show the prompt, run it with this week's (fictional) details, run the four-question check aloud, and point out each checklist item.
- Then show the reuse: swap the bracketed details and run it again.
- Don't promise an exact output. If the run has a flaw, catch it with the four-question check; that's the best possible demo.
- *Tip:* keep it to five minutes. Learners need the build time more.

---

### Slide 83 — YOUR TURN: Build your capstone ⏱ 18 MIN

**On slide:**
> YOUR TURN · ⏱ 18 MIN · Solo
> Build your final prompt. Tick every box on the checklist.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 11 — Capstone build**

| | |
| --- | --- |
| **Task** | Turn your best prompt from Exercise 6 into a final, reusable prompt for your task. Run it, iterate at least twice, check the result, and tick every box on the checklist. **Done when** a colleague could use it without asking you anything |
| **Time** | 18 minutes: 6 to finalize, 9 to run and iterate, 3 to check and prepare to present |
| **Format** | Solo; you may ask a neighbour for a second opinion |
| **Template** | Capstone checklist and template on the handout |

**Reusable capstone template:**

> You are a [role].
> Context: [situation, audience, why it matters].
> Task: [action verb + what to produce] using the details below.
> Format: [length, structure, layout].
> Rules: [tone, must include, must avoid].
> Here is an example of the style I want: [optional example].
> Details for this time: [the bracketed details that change each time].

**Prepare to present (3 minutes each):** your task in one sentence · your
prompt, read aloud · one strength of the output · the one change that helped
most.

**Notes (18 min).**
- Call time at 10 minutes left ("you should be running it by now") and 3 minutes left ("check and prepare to present").
- Circulate. Prioritize people who haven't run anything yet.
- *Common mistake:* polishing the prompt forever without running it. Push people to run early.
- *Common mistake:* skipping the privacy check because "it's my own task." Remind them: own task, still no real names or data today.
- *Tip:* people who finish early can test their prompt in a second AI tool, or write a version for a different audience.

---

### Slide 84 — YOUR TURN: Present at your table ⏱ 15 MIN

**On slide:**
> YOUR TURN · ⏱ 15 MIN · Table groups
> 3 minutes each. Listeners: one strength, one suggestion.

**Layout:** YOUR TURN. White background. Full-width dark gray (#474648) banner with the first line in white URW Grotesk Medium (9.39:1); the timer is the largest text on the slide. Instruction line in black URW Grotesk Regular, 24 pt minimum (21:1). Thin UNO red (#DE1D24) accent bar, non-text. Logo, if used: two-color University Logo (`uno-logo-color.png`), alt text "University of Nebraska Omaha"; position NEEDS CONFIRMATION (item 10).

**Exercise 12 — Table presentations**

| | |
| --- | --- |
| **Task** | Each person presents their capstone to their table in 3 minutes. Listeners give one strength and one suggestion |
| **Time** | 15 minutes: about 3 minutes per person in a group of 4–5 |
| **Format** | Table groups of 4–5. One person keeps time |
| **Template** | Presentation outline below |

**Presentation outline:**

1. My task, in one sentence
2. My prompt (read it aloud or show it)
3. One thing the output does well
4. The change that helped most
5. Listeners: one strength, one suggestion

**Notes (15 min).**
- Ask each table to choose a timekeeper. Announce the 3-minute switch out loud if tables lose track.
- Ask each table to nominate one capstone for the whole-room "hall of fame" in the closing.
- *Watch for:* nervous presenters. Tables are small and friendly by design; remind them nobody is grading.
- *Common mistake:* listeners giving only praise. Ask for a real, specific suggestion.
- *Tip:* walk between tables and listen. Note one great prompt to highlight in the closing.

---

### Slide 85 — Share-out and questions ⏱ 10 MIN

**On slide:**
> What's the best idea you heard at your table?
> Questions?

**Notes (10 min).**
- Ask each table for one idea they'll borrow from someone else's prompt.
- Collect table nominations for the hall of fame.
- Open for final questions about the techniques.
- *Tip:* name specific good moves you overheard while walking around ("I heard someone use 'What did you assume?' to find missing context; that's exactly right").

---

### Slide 86 — Recap: Module 6

**On slide:**
> ✔ You built a tested, reusable prompt
> ✔ For a real task from your job
> ✔ You can do this again tomorrow

**Notes (1 min, inside the share-out time).**
- Pause and let it land: this morning, many were nervous. Now everyone has a working prompt.
- *Tip:* ask for a round of applause for the room. It sounds cheesy; it works.

---

## Closing

4:00–4:30 · 30 min · Slides 87–90

Celebrates the day's work, collects feedback, and sends people home with a
plan for the next week.

---

### Slide 87 — Prompt hall of fame

**On slide:**
> 🏆 Prompt Hall of Fame
> Three capstones, nominated by your tables

**Notes (10 min).**
- Invite three nominated learners to the front, or let them present from their seats. 2–3 minutes each: task, prompt, output.
- After each, ask the room: "Which part of today do you see in this prompt?"
- *Watch for:* nominees who don't want to present. Never force it; ask the table for another nominee.
- *Tip:* project their prompt so everyone can read it.

---

### Slide 88 — Today in one slide

**On slide:**
> Predicts, doesn't look up · Five parts · Examples, steps, iteration · Four-question check · Protect private data

**Notes (5 min).**
- Run through the day, one phrase per module. Ask the room to call out the five parts and the four questions from memory.
- Return to the parking lot. Answer or redirect anything still open.
- Return to the warm-up poll from 8:30. Ask: "Has anyone moved from nervous to curious, or curious to comfortable?"
- *Tip:* a quick show of hands here gives you a feel-good ending and real feedback.

---

### Slide 89 — Feedback

**On slide:**
> Two minutes, please: [feedback link / QR code]
> What worked? What should change?

**Image:** feedback QR code, alt text "QR code linking to the end-of-day feedback form". Print the link beside it for anyone who can't scan.

**Notes (7 min).**
- Give time in the room to fill in the feedback form. Response rates drop sharply once people leave.
- Suggested questions: rate the day 1–5; most useful part; what to change; confidence before vs. after; would you recommend it?
- *Tip:* stay quiet while people fill it in. Don't hover.

---

### Slide 90 — Your next steps

**On slide:**
> This week: use your prompt on a real task · Check your AI policy · Save prompts that work
> Resources on your handout

**Notes (8 min, including last questions).**
- **Next steps:**
  1. Use your capstone prompt on a real task this week. Put it in your calendar now.
  2. Find your workplace's AI policy and approved tools before using AI with work information.
  3. Start a "prompt library": a document where you save prompts that worked, with [brackets] for the parts that change.
  4. Practise a little every day. Ten minutes is enough.
- **Resources** (on the handout): the official prompting guides from OpenAI, Anthropic (makers of Claude), and Microsoft (Copilot); your organization's AI policy; today's handout.
- Thank everyone. Stay for questions as people leave.
- *Tip:* check the guide links before each run of the course. They move.
