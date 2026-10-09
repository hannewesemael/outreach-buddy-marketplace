---
name: outreach-buddy-maintenance
description: >
  This skill should be used for a periodic (typically monthly) check-in
  on an already-running Outreach Buddy system, or when the creator says
  things like "outreach buddy onderhoud", "outreach buddy check-in",
  "review my outreach buddy", "update my outreach buddy documents".
metadata:
  version: "0.2.0"
---

# Outreach Buddy Maintenance

## Source of truth

All step content lives in the bundled file `stappenplan.md` that ships
with this plugin (in this skill's folder, and at the plugin root). Read
Step 17 (Onderhoud) from it fresh at the start of this skill with the Read
tool — do not rely on a hardcoded copy.

## Flow

1. Walk through Step 17's checklist with the creator, one item at a
   time: new brands or collaborations to add to the about me document,
   rate changes, frequency or cadence adjustments, and tone-of-voice
   refinements based on what has landed well or poorly recently.
2. For anything the creator wants changed, read the relevant existing
   document file from their outreach folder, make the edit, and write the
   updated version back. Don't ask them to redo a whole document from
   scratch for a small change.
3. If the creator mentions wanting to temporarily or permanently shift
   niche focus, remind them they can do that any time by saying "vanaf
   nu deze niches: [...]" — that's handled live by their ideale klant &
   niche document and needs no changes here.
4. If they mention a scheduled task feels off (wrong time, too
   frequent, wrong notification channel), tell them they can adjust or
   stop it just by describing the change in plain language — no need to
   rebuild it from scratch.
5. Close with a one-line summary of what changed during this check-in.
