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
              version: "2.0.0"
              ---

              # Outreach Buddy Automation

              ## Source of truth

              All step content lives in the bundled file stappenplan.md at the plugin root (../../stappenplan.md relative to this skill folder). Read it fresh with the Read tool and use Steps 4 and 12 through 16.

              ## Preconditions

              Confirm the creator already has their Outreach Buddy Project with its reference documents (tone of voice, about me, ideale klant & niche, onderhandelen & upsells, pitch structuur, follow-up structuur, and ideally frequentie & automatisering). If any of the first six are missing, hand off to the onboarding skill. If only the frequentie & automatiseringsdocument (Step 11) is missing, run through it now using that step's questions before continuing.

              ## Flow

              1. Connect tools (Step 4). Confirm Claude in Chrome is active and logged into Instagram, and Gmail is connected. Test both with a short read-only check.
              2. Test a first pitch (Step 12) for one real brand the creator names. Walk through the checklist before anything sends. If Claude hesitates to send, use Step 12's explicit-permission prompt.
              3. Set up the weekly cycle (Step 13) as a scheduled task, using the frequency, brands per run and notification settings from the frequentie & automatiseringsdocument, confirming with the creator.
              4. Set up the daily cycles (Steps 14-16): combine 14 and 15 into one daily scheduled task, and set up Step 16's follow-up task separately, following that document's preferences for timing and what auto-sends versus what stays a draft.
              5. Confirm all scheduled tasks by listing them back with cadence and next run time. Remind the creator they can change or stop any by describing the change in plain language.
              6. Close by telling them their Outreach Buddy is live and they can check in monthly with "outreach buddy onderhoud".

              ## Safety

              Never turn a message type into an automatically-sending scheduled task without the creator first seeing at least one manual run succeed. Always defer to the creator's own frequentie & automatiseringsdocument about what auto-sends versus what stays a draft; anything marked draft-only must stay draft-only.
              
