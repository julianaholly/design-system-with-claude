# How to build a design system with Claude

A step-by-step guide for people who don't code. It's the process I used, as a brand designer, to build a design system that Claude can actually work from: one where you hand over the copy and photos, Claude builds the piece in your design app, and the first draft is close enough to get approved.

It works for any brand with a body of approved work: a magazine, a company's marketing, a client's social templates. The examples are illustrations, not a case study.

## What you end up with

- **A design system** Claude can read: the look, the reusable parts, and a recipe for every kind of piece you make
- **A shortcut** (a Claude skill), so one line like "build the events page for the spring issue" starts a job
- **A log** of every decision, so nothing has to be explained twice
- **A way to keep teaching it**, so each round of feedback makes the next first draft better

## The order at a glance

Do these in order. Steps 1 to 6 happen once. Steps 7 and 8 keep going for as long as you use the system.

| # | Step | You | Claude | Done when |
| --- | --- | --- | --- | --- |
| 1 | Set the brief | Say the goal, who approves, what's in and out | Asks only what it can't find | The scope fits in a few lines |
| 2 | Open up the real files | Give access, download online-only files | Finds where the approved work lives and how it can work in your design app | You know the files and the tool Claude will use |
| 3 | Set up the system and the log | Approve the plan | Creates the empty system and a running log | Both exist |
| 4 | Study what got approved | Point to files and feedback, correct wrong guesses | Reads real files, compares drafts with finals | Values come from files, not estimates |
| 5 | Write the system | Review it for taste and truth | Writes the look, parts, two pathways and specs | Every section is written |
| 6 | Build the shortcut | Try a one-line request | Builds the skill that does the job in your app | One line starts a job |
| 7 | Test on approved work | Judge each result and give notes | Rebuilds approved pieces, compares, fixes | Every main type matches the approved structure |
| 8 | Do real jobs and keep teaching it | Review, send, pass on feedback | Builds proofs, turns notes into rules | First drafts get approved with few changes |

## Step by step

### 1. Set the brief

Decide these before anything is built:

- **The real goal.** Mine was: Claude does the production design, and first drafts get approved.
- **Who approves, and what they actually like.** Their taste beats best practice, so follow what gets approved.
- **Scope.** What's in and what's out. Include work you don't do yourself if Claude should be able to do it.
- **The period to learn from.** Use recent work only, so old habits don't creep in.
- **New or existing.** If a system already exists, say whether to update it or leave it alone.
- **Words that mislead.** Write down what people say versus what gets approved. A team might describe the brand as "bold and colourful" while every approved piece is black and white with one accent colour. The approved work wins.
- **What it isn't.** Decide whether this is a working tool or a handbook. A working tool only needs to be clear enough for someone new.

### 2. Open up the real files

- List where approved work, drafts, copy, photos, fonts, logos and feedback live.
- Check the fonts are installed and download any files that only exist in the cloud.
- Ask whether Claude can work directly in your design app. This was my biggest finding. Claude could open the last approved file, save a copy, swap in the new copy and photos, and export a proof, with no mockups in between.
- Find out where feedback really arrives (email, text messages, comments on a PDF), and don't assume.

### 3. Set up the system and the log

- Create the empty design system first, so it has a home from the start.
- Start a log with the goal, a step-by-step list, decisions to remember and open items. Ask Claude to update it after every step and every new rule. I keep mine in Notion; any document Claude can edit will do.

### 4. Study what got approved

- **Read the real files.** Take styles, sizes, colours and grids from them, not from looking at a picture.
- **Map every type of piece,** and note the file to start from for each.
- **Compare drafts with finals.** What changed between them is what gets sent back.
- **Collect real feedback** in the approvers' own words.
- **Check assumptions.** Claude once assumed a set of files held someone's markup because of how they were named. They didn't. Open the file before believing its name.

### 5. Write the system

In this order, because each part builds on the last:

1. **The look:** colours, type styles, grid and logos.
2. **The parts:** reusable components, each with its real settings in your app.
3. **Start here:** what the brand's look means in practice, and the rules that matter most.
4. **"What did I get?"** One recipe per type of piece: size, parts in order, file to start from, steps, what usually gets sent back, and the line to give Claude.
5. **"What did they say?"** A feedback decoder: who said it, what kind of note it is, and the exact fix. Include what to do with vague notes, plus a before-you-send checklist.
6. **Specs and files:** sizes, export settings, file names and where everything lives.

The two pathways in the middle are the heart of it. Almost every job starts with one of two questions: "what did I just get handed?" or "what did they just say about my draft?"

### 6. Build the shortcut

This is a Claude skill, so a short request is enough to start a job. Claude should:

- read the system and pick the recipe
- start from the last approved file, saved as a new copy
- place the supplied copy and photos as they are, and flag problems instead of fixing them
- check the result, compare it with the approved piece, and export a proof
- report what's still open: names, credits, low-resolution photos

Set the safety limits here too. See **Limits to set on day one** below.

### 7. Test on approved work

This is the step that makes the system good. Give Claude only the raw copy and photos of a piece that's already approved, then compare its rebuild with the real one.

- Test one of each main type, simplest first, and don't move on until the structure matches.
- Expect several rounds. Type usually matches straight away. Layout, cropping, spacing and photo choice take the rounds.
- Be specific in notes: "more space between photos and captions" beats "it's off".
- When you say something's wrong, ask Claude to measure the approved file, not guess.
- Save every test in a test folder so nothing touches real work.

### 8. Do real jobs and keep teaching it

- Start with a simple job. Build a test copy first, then move it into the real folder once you're happy.
- Build the options your approver expects, as new files, never over the old ones.
- You review and send. Claude never sends anything.
- Pass on every note. Claude decodes it, fixes it and logs it.
- Tell Claude when you've edited a file by hand. Your edits are teaching material, and later rebuilds must keep them.
- When the first draft is off, try the layout closest to the last approved piece before changing the structure.

## What to make a rule

Not every note should become a rule. Sort each note first:

| Kind of note | What to do with it | Example |
| --- | --- | --- |
| True for all work | Rule in "Start here" and the checklist | Never hyphenate. |
| True for one type of piece | Put it in that recipe | Event pages get one layout, with photos to the right of the text. |
| An exact measurement that never changes | Record the number as fixed | The gap between photos and captions. |
| A measurement that changes with the content | Record it as flexible, and say how to judge it | Headline, intro and body gaps: space them evenly. |
| A specific note from an approver | Add a row to "What did they say?" | A phrase they always use, and the fix it really means. |
| An exception | Write it next to the rule it breaks, with why | One regular column keeps its heavier headings on purpose. |
| A change you made by hand before approval | Ask whether it's a one-off or a rule | Crop lead photos to the subject, not the sky. |
| A choice for this one piece | Don't make a rule | Which photo is the big one on this page. |
| A first reaction that may change | Wait until the piece is settled | An option called "crowded" on Monday can turn out to be the closest one on Tuesday. |

**Three questions before making a rule:**

1. Would this still be right on a different job next month?
2. Is it from someone who decides, or from a piece that got approved?
3. Can it be checked by looking at the finished piece?

If the answers are no, log it as a note, not a rule.

**Write every rule the same way:** say what to do, not just what's wrong, with the number if there is one. Add the note it came from, then put it everywhere it applies: the system, the checklist, the skill and the log.

## Who does what

| You | Claude |
| --- | --- |
| Set the goal and the scope | Reads files, measures and compares |
| Judge taste and say what's right | Builds proofs and checks them against the rules |
| Say which notes are rules | Proposes rules and writes them down |
| Supply access, names and missing files | Lists what's missing and flags doubts |
| Review and send everything | Never sends, and asks before anything hard to undo |

## Limits to set on day one

- Claude never sends anything to approvers or clients.
- Never overwrite an approved file. Always save a new copy.
- Ask before replacing any existing export, even if the working file looks newer.
- Ask before the first save into a shared folder.
- Never write or change the copy. Place it as supplied and flag problems.
- Never invent a name, credit, price or claim. Use a visible placeholder and list it in the report.
- Check for your own hand edits before changing a file.

## Common traps

- **Trusting a file name.** Open the file before believing what it's called.
- **Judging by the type.** Type can match perfectly while the piece still fails on photos and space.
- **Designing new layouts too early.** The fastest approval usually comes from what already got approved.
- **Comparing unlike files.** A logo can look too big only because one file has crop marks and the other doesn't. Compare at the same size.
- **Rules made too fast.** Reversing a rule later costs more than waiting a round.
- **Copy that's longer than last time.** Plan for it. Rework the layout, and don't cut copy or shrink type.
- **Duplicate or conflicting rules.** When adding a rule, search for older ones it contradicts.

## Lines to start with

**Starting a new system:**

> I want a design system so you can do the design work for [brand] and get first drafts approved. Approvals come from [people], and their taste matters more than best practice. Learn from [period]. It covers [scope] and not [exclusions]. The files are in [location]. Spell out two pathways: what did I get, and what did they say. Keep a log after every step, and give me a plan first.

**Testing:**

> Rebuild [approved piece] using only its raw copy and photos, starting from [earlier file]. Save it in the test folder, compare it with the approved one, and tell me what differs.

**Passing on feedback:**

> [Name] said: "...". Decode it, make the fix as a new file, and tell me if you think it should become a rule.

## Checklist: is the system ready?

- [ ] All values come from real approved files
- [ ] Every type of piece in scope has a recipe and a file to start from
- [ ] Every section is written and easy to find
- [ ] A one-line request starts a job
- [ ] Each main type has been rebuilt and matches the approved structure
- [ ] The safety limits are in place
- [ ] One real job has gone through to approval
- [ ] You know where new feedback arrives and how it gets into the system

---

Written by [Juliana Holly](https://julianaholly.com), with Claude. Use it, adapt it, and tell me what you'd add.
