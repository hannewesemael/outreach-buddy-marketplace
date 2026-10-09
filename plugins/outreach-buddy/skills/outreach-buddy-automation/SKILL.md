---
name: outreach-buddy-automation
description: >
  This skill should be used once a creator's Outreach Buddy reference
  documents already exist (typically built via the outreach-buddy-onboarding
  skill), and they want to connect their tools and turn on the actual
  automation, or say things like "zet mijn outreach automatisering aan",
  "connect my outreach buddy tools", "start met versturen", "automate my
  outreach", "activeer mijn scheduled tasks".
metadata:
  version: "0.2.0"
---

# Outreach Buddy Automation

## Source of truth

All step content lives in the bundled file `stappenplan.md` that ships
with this plugin (in this skill's folder, and at the plugin root). Read it
fresh at the start of this skill with the Read tool, and use Steps 4 and
12 through 16. Do not rely on a hardcoded copy of these steps.

## Preconditions

Confirm the creator already has their Outreach Buddy outreach folder with
its reference documents as files (tone of voice, about me, ideale klant & niche,
onderhandelen & upsells, pitch structuur, follow-up structuur — and
ideally frequentie & automatisering). If any of the first six are
missing, hand off to the onboarding skill instead of proceeding here. If
only the frequentie & automatiseringsdocument (Step 11) is missing, run
through it now using that step's own questions before continuing — the
rest of this skill depends on the choices it captures: send frequency,
what auto-sends versus stays a draft, follow-up cadence, and notification
preference.

## Flow

1. Connect tools (Step 4). Confirm Claude in Chrome is active and logged
   into the creator's Instagram, and Gmail is connected. Test both with a
   short read-only check, exactly as Step 4 describes.
2. Test a first pitch (Step 12). Run Step 12's test prompt for one real
   brand the creator names. Walk through that step's checklist before
   anything sends. If Claude hesitates to actually click send, use Step
   12's explicit-permission prompt.
3. Set up the weekly cycle (Step 13). Once the creator is happy with a
   manual test or two, create the recurring scheduled task exactly as
   Step 13 describes — a plain-language description of what to do, how
   often, and when, which becomes the actual scheduled task. Use the
   settings (frequency, brands per run, notification channel) from the
   frequentie & automatiseringsdocument, confirming with the creator
   rather than guessing.
4. Set up the daily cycles (Steps 14-16). Combine Steps 14 and 15 into
   one daily scheduled task as instructed, and set up Step 16's follow-up
   task separately — both following that document's automation
   preferences for timing and what auto-sends versus what stays a draft.
5. Confirm all scheduled tasks were created by listing them back to the
   creator with their cadence and next run time. Remind them they can
   change or stop any of them at any time just by describing the change
   in plain language.
6. Close by telling them their Outreach Buddy is live, and that they can
   check in on it monthly by saying something like "outreach buddy
   onderhoud".

## Safety

Never turn a message type into an automatically-sending scheduled task
without the creator first seeing at least one manual run succeed. Always
defer to what the creator's own frequentie & automatiseringsdocument says
about what auto-sends versus what stays a draft — the stappenplan's
example prompts default to automatic DM-sending only, and anything the
creator marked as draft-only must stay draft-only in the scheduled tasks
you create, regardless of what an example prompt shows.
