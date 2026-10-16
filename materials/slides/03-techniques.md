# Module 3 — Techniques: examples, step-by-step, iteration

11:00–12:00 (60 min) · Slides 37–50
Concept 12 · Demo 7 · Hands-on 28 (47%) · Share-out and questions 10

**By the end, learners can:** improve a prompt by adding examples, asking for
step-by-step work, and refining with follow-up messages.

---

### Slide 37 — Module 3: Three techniques

**On slide:**
> Module 3
> Three techniques: examples, step-by-step, iteration

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

**Notes.**
- *Common mistake:* pairs writing examples so different from each other that the format is unclear.
- Point out the extra instruction ("UNASSIGNED"): examples plus a rule for the awkward case is a strong combination.
- *Tip:* fast pairs try it in a second AI tool and compare.

---

### Slide 47 — YOUR TURN: Three rounds ⏱ 18 MIN

**On slide:**
> YOUR TURN · ⏱ 18 MIN · Solo
> Take your Module 2 prompt. Improve it in three rounds. Log each change.

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

**Notes.**
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

**Notes.**
- Remind people to bring their prompt and log back; the capstone builds on them.
- *Tip:* during lunch, set the room up for the bake-off: groups of 4–5 at each table, one printed bake-off brief per table.
