# Outreach Buddy 2.0

A plugin that turns Claude into a UGC/content creator's personal outreach assistant: pitching, negotiating, following up, and managing brand DMs and email - all trained on the creator's own voice.

## Overview

This plugin walks a new creator through building their own Outreach Buddy, then helps them turn it into a running automation, and later keep it up to date. All step content lives in a bundled file (stappenplan.md, included with the plugin) that each skill reads at runtime, so the plugin is fully self-contained and does not depend on any external page.

## Components

- outreach-buddy-onboarding ("outreach buddy onboarding") - Creates a Claude Project and builds the seven reference documents by walking the creator through the bundled stappenplan, question by question.
- - outreach-buddy-automation ("zet mijn outreach automatisering aan") - Connects Instagram (via Claude in Chrome) and Gmail, tests a first pitch, and sets up the recurring weekly and daily scheduled tasks.
  - - outreach-buddy-maintenance ("outreach buddy onderhoud") - A monthly check-in: refresh reference documents, adjust cadence, tweak tone of voice.
   
    - ## Leads Tracker template
   
    - A creator who wants to use the Leads Tracker (Step 11) duplicates this template into their own Notion workspace, so everyone works in their own file:
   
    - https://app.notion.com/p/85aaac9cf3f44ee58df696941b231f30
   
    - Keep that template shared as "Anyone with the link can view" (and allow duplicate).
   
    - ## Usage
   
    - Install the plugin, then in any chat type one of the trigger phrases above (Dutch or English). Type "outreach buddy onboarding" to start. Type /update to get the latest version.
    - 
