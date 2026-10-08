---
name: outreach-buddy-onboarding
description: >
  This skill should be used when a new creator wants to set up their
    Outreach Buddy system for the first time, or says things like "outreach
      buddy onboarding", "start outreach buddy", "set up my outreach buddy",
        "installeer mijn outreach buddy", "ik wil mijn outreach automatiseren".
          It creates a dedicated Claude Project and builds the seven reference
            documents (tone of voice, about me, ideale klant & niche, onderhandelen
              & upsells, pitch structuur, follow-up structuur, frequentie &
                automatisering) by walking the creator through the bundled stappenplan,
                  one question at a time.
                  metadata:
                    version: "2.0.0"
                    ---

                    # Outreach Buddy Onboarding

                    ## Source of truth

                    All step content, questions, and example answers live in the bundled file stappenplan.md at the plugin root (../../stappenplan.md relative to this skill folder). Read it fresh at the start of every onboarding with the Read tool. Never hardcode step text from memory or a previous run.

                    ## Flow

                    1. Welcome the creator warmly, and explain this builds their Outreach Buddy, a version of Claude trained on their own voice, inside a dedicated Claude Project.
                    2. Read the bundled stappenplan and use Steps 1 through 11. Skip the "Voor je begint..." section.
                    3. Check whether the creator already has a Claude Project (typically named "Outreach Buddy"). If not, create one using Step 3's name and description.
                    4. For each of Steps 5 through 10, in order (Tone of voice, About me, Ideale klant & niche, Onderhandelen & upsells, Pitch structuur, Follow-up structuur):
                       a. Say in one line what the document is for, using that step's intro.
                          b. Ask exactly: "Ben je een beginner en wil je de standaard/voorbeeld-versie van dit document installeren, of beantwoord je liever elke vraag zelf?" (translate to English if the creator writes in English).
                             c. If they choose standard: use that step's beginner example answer and write the document into the Project using that step's prompt and structure.
                                d. If they answer themselves: ask that step's questions one at a time, wait for each answer, then write the document.
                                   e. Never skip a question silently; let them rephrase or skip.
                                   5. For Step 11 (Frequentie & automatisering), first ask if they have a Notion account.
                                      - If yes: walk them through duplicating the Leads Tracker template linked in Step 11 into their own workspace, get their copy's link, then run the step's prompt with that link.
                                         - If no: tell them Notion is the one external requirement for lead tracking, build the other documents now, and return to Step 11 once they have a free Notion account.
                                         6. Remind them to save each document to the Project ("Add to project").
                                         7. Close by telling them their knowledge base is ready and they can now say "zet mijn outreach automatisering aan" to turn it on.

                                         ## Tone

                                         Match the creator's language (Dutch or English). Keep it encouraging and low-pressure, like a guided wizard. It is always fine to pause and resume by invoking the skill again; check what already exists before re-asking.
                                         
