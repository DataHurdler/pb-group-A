# Module 1 — How LLMs work, and what they can and can't do

8:45–9:45 (60 min) · Slides 8–20
Concept 12 · Demo 7 · Hands-on 27 (45%) · Share-out and questions 10

**By the end, learners can:** explain in plain words how an AI chatbot produces
an answer, and name tasks it does well and tasks it does badly.

---

### Slide 8 — Module 1: How AI tools work

**On slide:**
> Module 1
> How AI tools work, and what they can and can't do

**Layout:** Section divider ([brand spec](../brand/README.md), 3.2). `logo-reversed`, alt text "University of Nebraska Omaha".

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

**Layout:** YOUR TURN ([brand spec](../brand/README.md), 3.3). Banner in `brand-secondary`; timer is the largest text; body 24 pt minimum. Logo, if used: alt text "University of Nebraska Omaha".

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

**Notes.**
- Hand out cards before you say "go" so you're not talking over the activity.
- At 6 minutes, call "compare with the pair next to you."
- *Common mistake:* putting everything in *Great at it* or everything in *Can't*. Ask: "When would this one go wrong?"
- *Tip:* there's room for disagreement on 2, 9, and 10. That's good; debate is the point.

---

### Slide 18 — YOUR TURN: Test the limits ⏱ 17 MIN

**On slide:**
> YOUR TURN · ⏱ 17 MIN · Pairs
> Run three prompts. Note what worked, what was wrong, how you could tell.

**Layout:** YOUR TURN ([brand spec](../brand/README.md), 3.3). Banner in `brand-secondary`; timer is the largest text; body 24 pt minimum. Logo, if used: alt text "University of Nebraska Omaha".

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

**Notes.**
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
