---
name: outreach-buddy-onboarding
description: >
  This skill should be used when a new creator wants to set up their
  Outreach Buddy system for the first time, or says things like "outreach
  buddy onboarding", "start outreach buddy", "set up my outreach buddy",
  "installeer mijn outreach buddy", "ik wil mijn outreach automatiseren".
  It sets up the creator's Outreach Buddy inside a Claude Code working
  folder and builds the seven reference documents (tone of voice, about me,
  ideale klant & niche, onderhandelen & upsells, pitch structuur, follow-up
  structuur, frequentie & automatisering) as files in that folder, by
  walking the creator through the bundled stappenplan, one question at a
  time.
metadata:
  version: "0.2.0"
---

# Outreach Buddy Onboarding

## Source of truth

All step content, questions, and example answers live in the bundled file
`stappenplan.md` that ships with this plugin (in this skill's folder, and
at the plugin root). Read it fresh at the start of every onboarding with
the Read tool. Never hardcode step text from memory or from a previous
run — always read the bundled file so you use its current content.

## Flow

1. Welcome the creator in one or two warm sentences. Explain in plain
   language: this builds their Outreach Buddy, a version of Claude
   trained on their own voice and pitching style, inside Claude Code,
   with their documents saved as files in a working folder.
2. Read the bundled stappenplan and use Steps 1 through 11. Skip the
   "Voor je begint..." section at the top — that is the self-serve path
   for people not using this guided skill.
3. Make sure the creator has opened Claude Code and is working in an
   outreach folder, as Step 3 describes. The reference documents you
   build are saved as files in that folder, so there is no Claude
   Project to create.
4. For each of Steps 5 through 10, in this order — Tone of voice, About
   me, Ideale klant & niche, Onderhandelen & upsells, Pitch structuur,
   Follow-up structuur:
   a. Say in one line what this document is for, using that step's own
      intro text.
   b. Ask exactly: "Ben je een beginner en wil je de
      standaard/voorbeeld-versie van dit document installeren, of
      beantwoord je liever elke vraag zelf?" (translate to English if the
      creator is writing in English).
   c. If they choose the standard version: use that step's beginner
      example answer, and save the resulting document as a file in the
      creator's outreach folder using that step's prompt and structure.
   d. If they want to answer themselves: ask that step's numbered
      questions one at a time, wait for each answer before asking the
      next, then save the document as a file in the outreach folder using
      that step's structure once all answers are in.
   e. Never skip a question silently. If the creator doesn't want to
      answer one, or wants to phrase something differently than the
      step suggests, let them — adapt to their answer rather than
      insisting on the original wording or order.
5. For Step 11 (Frequentie & automatiseringsdocument), first ask whether
   the creator already has a Notion account.
   - If yes: walk them through duplicating the Leads Tracker template
     linked in Step 11 into their own workspace, get the link to their
     own copy, then run the step's prompt (with the real link
     substituted in) the same way as Steps 5-10. The creator duplicates
     the template themselves (open the link, click "Duplicate" top right);
     do not try to duplicate it for them.
   - If no: tell them a Notion account is the one external requirement
     for lead tracking, offer to keep building the other documents now,
     and come back to Step 11 once they've made a free Notion account.
6. Once the chosen documents are built, make sure each one is saved as a
   file in the creator's outreach folder, so every future Claude Code
   session in that folder reads them automatically.
7. Close by telling them their knowledge base is ready, and that the
   next step is turning it on: they can now say something like "zet mijn
   outreach automatisering aan" to connect their tools, test a first
   pitch, and turn on the recurring automation.

## Tone

Match the creator's own language (Dutch or English — mirror whichever
they write in first). Keep it encouraging and low-pressure: this should
feel like a guided setup wizard, not a form to fill out under time
pressure. It is always fine for the creator to pause partway through and
pick this back up later by invoking the skill again — check what already
exists as files in their outreach folder before re-asking anything
already answered.
