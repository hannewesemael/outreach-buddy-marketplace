# Claude Outreach Buddy — stappenplan

Stap voor stap je eigen UGC/content outreach automatiseren met Claude.

Dit bestand is de bron van waarheid voor de Outreach Buddy skills. Lees het telkens vers in aan het begin van een skill. De onboarding-skill gebruikt Stap 1 t.e.m. 11, de automation-skill Stap 4 en 12 t.e.m. 16, en de maintenance-skill Stap 17. Alles verloopt in Claude Code (het Code-tabblad in de Claude desktop app, of claude.ai/code).

---

## Voor je begint

Hoe wil je dit doorlopen? Kies wat het beste bij je past:

1. Handmatig, stap voor stap: lees elke stap hieronder, en plak zelf de prompts in Claude Code op het moment dat je eraan toe bent.
2. Automatisch met Claude: open Claude Code, start een sessie in je outreach-map, en typ "outreach buddy onboarding". Claude loodst je dan stap voor stap door alle vragen, inclusief de keuze of je een beginner-standaardantwoord wil gebruiken of liever zelf antwoordt.

---

## Stap 1 — Wat is de Outreach Buddy?

De Outreach Buddy is een versie van Claude die getraind is op jouw stem, jouw manier van pitchen en jouw manier van werken. Eenmaal ingesteld, kan Claude voor jou:

- gepersonaliseerde pitches schrijven naar merken
- follow-ups opvolgen en versturen volgens een ritme dat jij kiest
- reageren op merken die interesse tonen, inclusief prijsvoorstellen en onderhandelingen
- je Instagram DM's en e-mail inbox mee opvolgen

Het doel van dit document: één keer goed instellen, en daarna draait je outreach grotendeels op zichzelf, in jouw persoonlijke stijl.

Alles hierin is aanpasbaar. Elke prompt, vraag en voorbeeld is een startpunt, geen verplichting. Wil je een vraag niet beantwoorden, klinkt een voorbeeldzin niet als jij, of wil je een stap net helemaal anders aanpakken? Verwoord het gewoon zoals jij het wil, of sla een vraag over. Claude past zich aan jouw antwoorden aan, niet omgekeerd.

---

## Stap 2 — Claude downloaden en een plan kiezen

Moet je Claude nog installeren, of weet je nog niet goed hoe Claude werkt? Verwijs de creator dan naar de aparte installatiegids met screenshots.

1. Ga naar claude.ai of download de Claude desktop app.
2. Maak een account aan (of log in).
3. Kies een betalend plan. Dit is nodig omdat:
   - Claude Code, waar deze plugin in werkt, een betaald plan vereist
   - je de geavanceerde functies nodig hebt (om tools te koppelen zoals Gmail en Chrome, en taken automatisch te laten uitvoeren en te plannen)
   - de gratis versie deze functies niet (volledig) ondersteunt

Check op claude.ai/pricing welk plan momenteel Claude Code en deze functies bevat, dit kan wijzigen.

Je werkt voor alles in Claude Code: het Code-tabblad in de Claude desktop app, of claude.ai/code in je browser. Claude kan daar vanuit je gesprek documenten opstellen en als bestand bewaren, tools gebruiken (Gmail, Chrome) en taken plannen, zodra je die tools gekoppeld hebt. Voor documenten opstellen en pitches testen (stap 5 t.e.m. 12) heb je enkel een gesprek in Claude Code nodig. Vanaf het moment dat Claude echt iets moet uitvoeren, zoals je Instagram en Gmail connecteren (stap 4) of DM's en mails versturen en dit laten terugkeren als geplande taak (stap 13 t.e.m. 16), gebruikt Claude die koppelingen vanzelf in datzelfde gesprek.

---

## Stap 3 — Open Claude Code en kies je outreach-map

In Claude Code werk je in een map op je computer. Claude bewaart al je outreach-documenten daar als bestanden, en leest ze bij elke sessie opnieuw in, zodat je nooit opnieuw context moet geven. Dat vervangt de klassieke "projecten", je hebt hier geen project nodig.

Actie:
1. Open Claude Code: klik in de Claude desktop app bovenaan op het "Code"-tabblad, of ga naar claude.ai/code.
2. Maak op je computer een nieuwe, lege map aan, bijvoorbeeld "Outreach Buddy".
3. Start een nieuwe sessie (+ New session), kies "Local" (je eigen computer), en selecteer die map.

Alles wat je in de volgende stappen maakt (tone of voice, about me, pitch structuur, follow-up structuur, frequentie) bewaart Claude als een bestand in die map.

---

## Stap 4 — Connect je tools

Om DM's en e-mails effectief te laten versturen en klaarzetten, moet Claude bij je Instagram en je mailbox kunnen.

Actie:
1. Activeer Claude in Chrome (via de instellingen in de Claude desktop app) en log in op je Instagram account in diezelfde browser.
2. Connecteer Gmail via je connector-instellingen in Claude, zodat Claude mails kan lezen en drafts kan klaarzetten.
3. Test beide connecties met een korte vraag, bijvoorbeeld "Lees mijn laatste 3 DM's op Instagram" en "Toon mijn laatste 3 e-mails".

Geef enkel toegang tot wat nodig is, en controleer af en toe welke connecties nog actief staan in je instellingen.

---

## Stap 5 — Tone of voice document

Dit is het belangrijkste document: het zorgt ervoor dat Claude altijd in jouw stem schrijft, nooit generiek of robotachtig klinkt.

Actie: plak onderstaande prompt in Claude Code en vul de vragen in met jouw eigen antwoorden.

```
Ik wil een tone of voice document maken voor mijn Outreach Buddy setup.
Stel me de volgende vragen één voor één, en verwerk mijn antwoorden daarna
in een duidelijk, herbruikbaar tone of voice document:

1. Hoe zou je je eigen toon in drie woorden omschrijven?
2. In welke taal/talen schrijf je normaal naar merken?
3. Gebruik je emoji's? Zo ja, hoe vaak en welk soort?
4. Zijn er woorden, uitdrukkingen of clichés die je NOOIT gebruikt?
5. Zijn er zinnen of openingszinnen die je net heel graag gebruikt?
6. Hoe wil je dat een e-mail of bericht er qua opmaak uitziet
   (kort/lang, veel witruimte, geen liggende streepjes, etc.)?
7. Heb je een portfoliolink of iets dat je altijd meegeeft?

Verwerk mijn antwoorden in een overzichtelijk document met duidelijke
kopjes, zodat ik het makkelijk kan hergebruiken en aanvullen.
```

Beginner-standaardantwoord (plak dit als antwoord op alle vragen hierboven als de creator beginner is):
"Mijn toon is fun, vriendelijk en zelfzeker. Ik schrijf in het Nederlands voor Belgische en Nederlandse merken, en in het Engels voor internationale merken. Ik gebruik af en toe een spaarzame emoji, nooit te veel. Ik vermijd clichés zoals 'ik scrollde door jullie socials' en overdreven enthousiaste afsluiters. Mijn vaste openingszin is 'Hii, leuk om digitaal kennis te maken!'. Ik hou mijn berichten kort, met veel witruimte, en gebruik geen liggende streepjes in lopende tekst. Ik voeg altijd mijn Instagram of portfoliolink toe onderaan."

Claude bewaart dit document automatisch als bestand in je outreach-map (bijvoorbeeld tone-of-voice.md), zodat het elke sessie wordt meegelezen. Vraag gerust om het aan te passen als er iets niet helemaal klopt.

---

## Stap 6 — About me / ervaring document

Dit document geeft Claude de feiten om je zelfverzekerd te positioneren in een pitch: wie je bent, wat je ervaring is, én de financiële grenzen waarbinnen Claude namens jou mag bewegen.

Actie: plak onderstaande prompt in Claude Code.

```
Ik wil een about me/ervaring document maken voor mijn Outreach Buddy setup.
Stel me de volgende vragen één voor één, en verwerk mijn antwoorden daarna
in een duidelijk, herbruikbaar document:

Over mij:
1. Wie ben je, waar ben je gevestigd, en wat is je persoonlijke context die
   relevant is voor pitches (bv. ouderschap, levensstijl)?
2. Hoelang doe je dit al, en hoeveel samenwerkingen heb je ongeveer gedaan?
3. Welke grote/bekende merken staan in je portfolio?
4. Heb je vaste/retainer klanten? Welke?
5. Wat zijn je sterktes/USP's (bv. snelle levering, creatieve controle,
   nichekennis zoals skincare)?

Prijzen en grenzen:
6. Wat zijn je huidige tarieven, per type deliverable (bv. losse UGC video,
   bundel van X video's, extra usage rights, whitelisting/ads)?
7. Tot hoever ben je bereid te zakken in prijs, en onder welke voorwaarden
   (bv. enkel bij scope-aanpassing, nooit bij het eerste bod)?
8. Wat is je absolute ondergrens, waar je nooit onder gaat, ongeacht het merk?
9. Zijn er merken of soorten samenwerkingen waar je bewust een uitzondering
   voor maakt (bv. droommerk, hogere korting bij contentpakketten)?

Verwerk dit in een overzichtelijk document met kopjes "Over mij" en
"Prijzen en grenzen", zodat mijn Claude Outreach Buddy dit kan raadplegen bij elke pitch,
onderhandeling en prijsvoorstel.
```

Beginner-standaardantwoord:
"Ik ben [je naam], content creator uit [je stad]. [Voeg hier je persoonlijke context toe, bijvoorbeeld ouderschap of levensstijl, als dat relevant is voor je niche.] Ik ben net gestart met UGC content creation en bouw mijn portfolio nog op. Ik heb momenteel nog geen grote merken of vaste klanten, maar dat is waar ik naartoe werk. Mijn sterktes zijn snelle levering, duidelijke communicatie en creatieve controle, want ik stuur mijn script altijd vooraf door. Ik vraag momenteel €150 voor 1 UGC video, inclusief script, opname, montage en 2 revisies, exclusief usage rights. Ik ben bereid te zakken tot 15 à 20% onder mijn vraagprijs, maar enkel door de scope aan te passen, nooit door zomaar de prijs te laten zakken. Mijn absolute ondergrens is €100 per video, daar ga ik nooit onder. Ik maak voorlopig geen uitzonderingen op mijn tarieven."

Claude bewaart dit document als bestand in je outreach-map.

---

## Stap 7 — Ideale klant & niche document

Dit document bepaalt wie Claude precies target: welke waarden je belangrijk vindt, en met welk soort merken je wel en niet wil samenwerken. Dit stuurt straks ook de verdeling van je wekelijkse outreach.

Actie: plak onderstaande prompt in Claude Code.

```
Ik wil een ideale klant en niche document maken voor mijn Outreach Buddy
setup. Stel me de volgende vragen één voor één, en verwerk mijn
antwoorden daarna in een duidelijk, herbruikbaar document:

1. Wat zijn je persoonlijke waarden die je terug wil zien in de merken
   waarmee je werkt (bv. gezondheid, duurzaamheid, eerlijkheid)?
2. In welke niches of categorieën wil je actief pitchen? Noem er 2 tot 4.
3. Welk percentage van je wekelijkse outreach wil je per categorie
   besteden? Geef per categorie een percentage, samen goed voor 100%.
4. In welke regio's of landen wil je merken benaderen (bv. België,
   Nederland, BENELUX, Europa, internationaal)?
5. Werk je liever met kleine/lokale merken, middelgrote merken, grote/
   bekende merken, of een mix? Geef eventueel een verdeling.
6. Waar mag Claude naar merken zoeken (bv. Instagram, merkwebsites, of
   beide)?
7. Zijn er merken of sectoren die je bewust NIET wil benaderen (bv. fast
   fashion, alcohol, gokken)?
8. Wat maakt een merk een droommerk voor jou?
9. Zijn er kenmerken van een merk die voor jou een rode vlag zijn (bv.
   geen actieve social presence, slechte reviews)?

Verwerk dit in een overzichtelijk document met kopjes "Waarden",
"Niches en verdeling" (met een tabel van categorie en percentage),
"Regio en merkgrootte", "Uitsluitingen" en "Droommerken". Vermeld ook
expliciet dat ik op elk moment kan zeggen "vanaf nu deze niches: [...]"
om de focus tijdelijk of permanent te wijzigen, zonder dit hele document
opnieuw te doorlopen.
```

Beginner-standaardantwoord:
"Gezondheid en eerlijkheid zijn belangrijke waarden voor mij, ik werk het liefst met merken die daar oprecht in geloven. Ik wil actief pitchen in de niches gezonde voeding en dranken, fitness en sport, en wellness en health. Mijn verdeling: 50% gezonde voeding en dranken, 30% fitness, sport en gym, 20% wellness en health. Ik focus op merken uit België, Nederland en de rest van BENELUX. Ik werk het liefst met kleine tot middelgrote merken, die voelen vaak persoonlijker en flexibeler aan, maar sta open voor grotere merken als de waarden kloppen. Claude mag zoeken via Instagram en merkwebsites. Ik benader bewust geen merken in fast fashion, alcohol of gokken. Een droommerk is voor mij een merk dat past bij een gezonde levensstijl en waar ik zelf klant van zou zijn. Een rode vlag is een merk zonder actieve social media, of met opvallend veel negatieve reviews."

Wil je tijdelijk of blijvend een andere focus? Typ gewoon in Claude Code: "Vanaf nu deze niches: 100% skincare merken uit Nederland" (of gelijk welke andere niche/regio/merkgrootte) en Claude past de volgende outreach-rondes daarop aan, zonder dat je dit document moet herschrijven.

Claude bewaart dit document als bestand in je outreach-map.

---

## Stap 8 — Onderhandelings- en upsell-document

Dit document leert Claude hoe te reageren in specifieke, terugkerende situaties, zodat je nooit onder je waarde ingaat en zodat elke samenwerking maximaal benut wordt.

Actie: plak onderstaande prompt in Claude Code.

```
Ik wil een onderhandelings- en upsell-document maken voor mijn Outreach
Buddy setup. Stel me de volgende vragen één voor één, en verwerk mijn
antwoorden daarna in een duidelijk, herbruikbaar document met concrete
voorbeeldzinnen per situatie:

Lastige situaties:
1. Hoe reageer je als een merk een gifted/barter samenwerking voorstelt
   in plaats van betaling? Maak je ooit een uitzondering, en zo ja wanneer?
2. Hoe reageer je als een merk je duidelijk lowballt (een bod ver onder
   je tarief)? Ga je tegenbieden, de scope verkleinen, of vasthouden?
3. Hoe reageer je als een merk vraagt om onbeperkte usage rights of
   advertising rights zonder daarvoor apart te betalen?
4. Hoe reageer je als een merk vraagt om "gewoon nog iets extra's" buiten
   de afgesproken scope?
5. Hoe reageer je als een merk lang stil blijft na een prijsvoorstel?

Upsells tijdens een samenwerking:
6. Welke upsells stel je typisch voor tijdens/na een samenwerking
   (bv. losse foto's, extra hooks of CTA's, korte 10s "vibey" content om
   organisch te posten, een bundel van extra usage rights met korting)?
7. Hoe presenteer je een upsell zodat het als een logische toevoeging
   aanvoelt in plaats van als extra verkooppraatje?
8. Zijn er upsells die je liever proactief aanbiedt vs. enkel op vraag?

Verwerk dit in een document met twee delen: "Lastige situaties" (per
situatie: aanpak + voorbeeldzin) en "Upsell-menu" (per upsell: wat het is,
wanneer je het aanbiedt, en een voorbeeldzin om het voor te stellen).
```

Beginner-standaardantwoord:
"Bij een gifted of barter voorstel ga ik hier niet op in als nieuwe klant, tenzij het om een merk gaat waar ik zelf al fan van ben, en dan maximaal één keer om mijn portfolio op te bouwen. Bij een lowball bod bied ik niet meteen tegen met een lagere prijs, maar leg ik uit wat er in mijn tarief zit en pas ik eventueel de scope aan. Onbeperkte usage of advertising rights reken ik altijd apart aan. Extra's buiten de afgesproken scope bied ik aan als aparte, betaalde toevoeging. Als een merk lang stil blijft na een prijsvoorstel, stuur ik na 5 werkdagen een korte, vriendelijke follow-up. Mijn upsell-menu bestaat uit losse foto's uit de opnames, een extra korte video om organisch te posten, een extra hook of CTA, en een bundel extra usage rights met korting. Ik stel een upsell voor net na goedkeuring van de content, als een logisch vervolg."

Claude bewaart dit document als bestand in je outreach-map.

---

## Stap 9 — Pitch structuur document

Dit document legt vast hoe elke pitch is opgebouwd, zodat Claude nooit een generieke mail schrijft, maar elke keer een korte, unieke pitch die aanvoelt als een mini UGC-video: hook, positionering, waarde, sterke CTA.

Actie: plak onderstaande prompt in Claude Code.

```
Ik wil een pitch structuur document maken voor mijn Outreach Buddy setup.
Stel me de volgende vragen één voor één, en verwerk mijn antwoorden daarna
in een duidelijk, herbruikbaar document:

1. Wat is jouw favoriete manier om een pitch te openen (de "hook")?
   Geef 2 tot 3 voorbeeldzinnen.
2. Hoe positioneer je jezelf meteen zelfverzekerd, bijvoorbeeld via je
   ervaring, aantal samenwerkingen, gewerkte merken, vaste klanten of alles tesamen?
3. Welke USP's wil je altijd vermelden, bijvoorbeeld snelle levering,
   creatieve controle, vlotte communicatie, of nichekennis?
4. Hoe ziet jouw ideale CTA eruit? Wat is de concrete volgende stap die
   je aan een merk vraagt?
5. Hoe kort of lang moet een pitch idealiter zijn?
6. Heb je voorbeelden van onderwerpregels die je graag gebruikt?
7. Zijn er clichés of openingszinnen die je juist wil vermijden
   (bv. "ik zag op jullie socials dat...")?
8. Hoe ziet de verkorte versie van je pitch eruit voor een Instagram DM
   (zonder onderwerpregel, meestal 2 tot 3 zinnen)? Geef een voorbeeld.

Verwerk dit in een overzichtelijk document met de vaste opbouw hook,
positionering, USP's en CTA, plus 1 volledig uitgeschreven voorbeeldpitch
voor e-mail én 1 aparte, kortere voorbeeldpitch voor Instagram DM, zodat
mijn Claude Outreach Buddy weet welke versie hij waar moet gebruiken.
```

Beginner-standaardantwoord:
"Mijn hook is speels en persoonlijk, bijvoorbeeld 'Hii, leuk om digitaal kennis te maken!'. Ik positioneer mezelf door te vermelden dat ik net gestart ben, maar wel gestructureerd werk, snel lever en duidelijk communiceer. Mijn USP's zijn snelle levering, creatieve controle en vlotte communicatie. Mijn CTA nodigt uit tot een korte call of mailtje, nooit iets vaags. Mijn pitch is kort, maximaal 10 zinnen. Mijn onderwerpregel is simpel, bijvoorbeeld 'Samenwerking [merk] x UGC Creator'. Ik vermijd clichés zoals 'ik zag op jullie socials dat...' en bereik of engagementcijfers. Voor Instagram DM hou ik het nog korter, zonder onderwerpregel: 'Hii, ik ben [naam], content creator gespecialiseerd in [niche]. Ik zie mezelf wel samenwerken met jullie, zin om dit verder op te pikken via mail?'"

Voorbeeld korte pitch:
"Hii, leuk om digitaal kennis te maken! Ik ben [naam], content creator uit [stad]. Ik ben helemaal fan van [merk] omdat [persoonlijke, echte reden]. In de afgelopen tijd deed ik verschillende samenwerkingen, waaronder een aantal vaste klanten. Wat samenwerken makkelijk maakt: snelle levering, vlotte communicatie en creatieve controle, want ik stuur het script vooraf op en blijf het bijsturen terwijl ik film. Zin om even te bellen of te mailen om dit te bespreken?"

Voor Instagram DM laat je de onderwerpregel weg en hou je hook en CTA nog korter, meestal 2 tot 3 zinnen.

Claude bewaart dit document als bestand in je outreach-map.

---

## Stap 10 — Follow-up structuur document

Een follow-up moet altijd vriendelijk en licht aanvoelen. Dit document zorgt dat elke follow-up kort, warm en zonder druk blijft, maar wel de deur op een kier houdt.

Actie: plak onderstaande prompt in Claude Code.

```
Ik wil een follow-up structuur document maken voor mijn Outreach Buddy
setup. Stel me de volgende vragen één voor één, en verwerk mijn
antwoorden daarna in een duidelijk, herbruikbaar document:

1. Hoe open je een follow-up bericht? Wil je verwijzen naar je vorige
   bericht (bv. "ik breng mijn vorig mailtje nog even naar boven")?
2. Wil je bij een tweede of derde follow-up een andere invalshoek
   gebruiken dan bij de eerste (bv. iets concreets toevoegen zoals een
   voorbeeld of beschikbaarheid), of net dezelfde toon aanhouden?
3. Hoe laat je merken dat je nog steeds enthousiast bent, zonder
   opdringerig te klinken?
4. Wat is je afsluitzin? Vraag je expliciet om een antwoord, of laat je
   het losser?
5. Is er een moment waarop je stopt met follow-uppen als een merk niet
   reageert (bv. na de derde follow-up)?

Verwerk dit in een overzichtelijk document met een vaste opbouw voor
follow-up 1, 2 en 3, plus een volledig uitgeschreven voorbeeld per keer,
zodat mijn Claude Outreach Buddy elke follow-up hierop baseert.
```

Beginner-standaardantwoord:
"Ik verwijs altijd kort naar mijn vorige bericht, bijvoorbeeld 'ik breng mijn mailtje nog even naar boven'. Bij een tweede follow-up voeg ik iets concreets toe, zoals mijn beschikbaarheid of een voorbeeld uit mijn portfolio, bij de derde blijf ik kort en vriendelijk. Ik blijf enthousiast zonder druk te zetten. Ik sluit nooit af met een harde vraag om antwoord, maar met een open, vriendelijke uitnodiging. Als een merk na de derde follow-up niet reageert, stop ik en richt ik me op nieuwe outreach."

Voorbeeld eerste follow-up:
"Ik breng mijn vorige mailtje nog even naar boven, voor het geval het in de drukte verloren ging. Ik blijf super enthousiast om met [merk] samen te werken op UGC basis, dus laat gerust weten of het iets voor jullie kan zijn!"

Claude bewaart dit document als bestand in je outreach-map.

---

## Stap 11 — Frequentie & automatiseringsdocument

Dit document legt de cadans van je outreach vast: wat er wekelijks gebeurt, wat dagelijks, en vooral, wat automatisch verstuurd wordt en wat altijd als draft klaarstaat ter goedkeuring. Nieuwe outreach-DM's worden altijd automatisch verstuurd. Het document beschrijft ook de volledige flow: van een eerste DM, over een mailadres dat wordt opgepikt uit een DM-gesprek, tot een pitch-mail, en hoe je dit alles overzichtelijk bijhoudt.

Leads tracker (belangrijk): de creator houdt alle merken, statussen en mailadressen bij in een leads tracker in Notion. Er bestaat hiervoor een kant-en-klare template:

Template: Outreach Buddy — Leads Tracker — https://app.notion.com/p/85aaac9cf3f44ee58df696941b231f30?v=ef6aca02c40041ef9bfc2face2c46f78&source=copy_link

Actie voor de leads tracker:
1. Vraag eerst of de creator een Notion-account heeft. Zo niet: bied aan om de andere documenten nu te bouwen en later terug te komen voor de tracker zodra er een gratis Notion-account is.
2. Zo ja: laat de creator de template hierboven zelf dupliceren naar hun eigen Notion workspace. Geef de link, en leg uit: open de link, klik rechtsboven op "Duplicate" (bovenaan de pagina). Zo werkt iedereen in een eigen kopie en zit niemand in hetzelfde bestand. Claude dupliceert de template niet zelf; de creator doet dit, dat is het betrouwbaarst.
3. Vraag de creator daarna de link van hun eigen kopie, en vervang in onderstaande prompt [plak hier de link naar jouw leads tracker] door die link.

```
Mijn leads tracker vind je hier: [plak hier de link naar jouw leads tracker]

Ik wil een frequentie en automatiseringsdocument maken voor mijn Outreach
Buddy setup. Nieuwe outreach-DM's worden altijd automatisch verstuurd,
dat hoef je me niet te vragen. Stel me de volgende vragen één voor één,
en verwerk mijn antwoorden daarna in een duidelijk, herbruikbaar document:

1. Hoe vaak wil je nieuwe outreach versturen, bijvoorbeeld wekelijks?
2. Via welk kanaal start je nieuwe outreach het liefst, bijvoorbeeld eerst
   Instagram DM en pas nadien e-mail?
3. Hoe vaak wil je dat je DM's en inbox opgevolgd worden, bijvoorbeeld
   dagelijks?
4. Wil je dat de eerste pitch-mail, nadat een merk een mailadres deelt via
   DM, automatisch verstuurd wordt of als draft klaarstaat?
5. Wil je dat antwoorden op je e-mail inbox altijd als draft klaarstaan?
6. Na hoeveel dagen zonder antwoord wil je een eerste follow-up? Hoeveel
   dagen na de eerste follow-up wil je een tweede, als er geen antwoord is? En een
   derde, hoeveel dagen daarna?
7. Wil je dat email follow-ups automatisch verstuurd worden, of als draft?
8. Wil je dat elke lead bijgehouden wordt in een overzichtelijke tracker
   (welk merk, in welke fase, welk mailadres, hoeveel follow-ups), zodat
   jij en Claude altijd weten waar elk gesprek staat?
9. Wil je een melding (e-mail of sms) zodra ik de dagelijkse taak van
   inbox-beheer en DM-opvolging heb afgerond?

Verwerk dit in een document met kopjes "Wekelijks", "Dagelijks",
"Follow-up cadans" en "Leads bijhouden", plus een tabel die per type
bericht toont of het automatisch verstuurd wordt of als draft klaarstaat.
Beschrijf in "Leads bijhouden" expliciet de flow: DM versturen, mailadres
oppikken uit een DM-antwoord, dat mailadres en de status loggen, en van
daaruit een pitch-mail sturen. Vermeld in "Dagelijks" ook mijn voorkeur
voor de melding (e-mail of sms) zodra de dagelijkse taak is afgerond.
Neem de link naar mijn leads tracker letterlijk op in het document, zodat
je die er steeds bij kan raadplegen.
```

Omdat de link naar de leads tracker zowel in de prompt als in het resulterende document staat, hoeft Claude nooit te zoeken of te gokken waar hij moet loggen, dat voorkomt dat er per ongeluk een nieuwe, lege tracker wordt aangemaakt.

Beginner-standaardantwoord:
"Ik wil wekelijks nieuwe outreach starten via Instagram DM, altijd automatisch verstuurd. Dagelijks wil ik dat mijn DM's opgevolgd worden: als een merk een mailadres deelt, wordt dat mailadres genoteerd in mijn leads tracker en zet dat een eerste pitch-mail als draft klaar. Dagelijks wil ik ook dat mijn inbox bijgehouden wordt en antwoorden als draft klaargezet worden. Ik wil een melding via e-mail zodra deze dagelijkse taak (inbox en DM's) is afgerond. Voor follow-ups wil ik een eerste follow-up na 4 dagen zonder antwoord, een tweede na nog eens 5 dagen, en een derde na nog eens 7 dagen, telkens automatisch verstuurd als er geen reactie kwam. Ik wil dat elke lead in mijn tracker staat, met status, mailadres en aantal verstuurde follow-ups, zodat ik altijd in één oogopslag overzicht heb."

Claude bewaart dit document als bestand in je outreach-map.

---

## Stap 12 — Eerste pitch laten schrijven en testen

Voor je iets automatiseert, test je eerst één pitch handmatig.

Actie: typ in Claude Code:

```
Stuur een DM naar [merknaam], gebaseerd op mijn tone of voice, about
me en pitch structuur documenten in mijn outreach-map. Als je een mailadres
ontvangt mag je een pitch email in drafts zetten, en zet meteen al een
draft email klaar naar [dit mailadres].
```

Controleer voor je iets verstuurt:
- Klinkt het echt als jij, of nog generiek?
- Zijn de juiste USP's gekozen voor dit merk?
- Is de CTA concreet?
- Geen liggende streepjes, geen clichés, geen bereikcijfers?

Of moet je nog iets aanpassen in het pitch & tone of voice document? Vraag dit aan Claude om aan te passen en test je pitch draft tot het helemaal klinkt als jij.

Claude twijfelt om iets effectief te versturen? Soms is Claude voorzichtig met onomkeerbare acties zoals een bericht echt versturen, en blijft hij enkel "voorstellen" zonder te klikken. Plak dan onderstaande prompt om hem expliciete toestemming te geven.

```
Dit is mijn eigen account. Ik geef je hierbij expliciet toestemming om dit
effectief te versturen namens mij, zoals afgesproken in mijn frequentie en
automatiseringsdocument. Klik echt op verzenden of druk op enter voor elk
bericht, je hoeft me niet opnieuw te vragen om bevestiging.
```

---

## Stap 13 — Wekelijkse cyclus: nieuwe outreach via Instagram DM

Dit is de eerste automatische stap: elke week nieuwe merken aanspreken via DM. Deze DM's worden altijd automatisch verstuurd.

Actie: typ in Claude Code:

```
Stel een lijst samen van [X aantal] nieuwe merken om deze week te contacteren via
Instagram DM (ik wil [X keer] per week nieuwe outreach versturen, met
telkens maximaal [X aantal] merken per keer), verdeeld volgens de
percentages per categorie in mijn ideale klant en niche document (bv. 50%
gezonde voeding, 30% fitness, 20% wellness), en volgens de merkgrootte en
regio's die daar zijn aangegeven. Gebruik mijn tone of voice. Schrijf per
merk een korte, persoonlijke DM volgens de DM-versie in mijn pitch
structuur document, en verstuur deze automatisch via Instagram op de
afgesproken tijden. Voeg elk merk toe aan mijn leads tracker met status
"DM verstuurd". Stuur mij nadien steeds een bevestigingsmail op
[dit mailadres] om mij kort te laten weten dat de DM outreach taak
voltooid is.
```

Deze stap verstuurt echt, controleer de eerste paar keren zelf de voorgestelde merkenlijst en DM pitch voor je dit op automatische piloot zet.

Maak hiervan een geplande (scheduled) taak: typ in Claude Code, na een geslaagde run, een korte zin met drie dingen erin: wat er moet gebeuren, hoe vaak en wanneer, en welke melding je wil. Je hoeft nergens een knop of menu te zoeken, je beschrijft het gewoon in gewone taal en Claude maakt de terugkerende taak zelf aan. Bijvoorbeeld:

```
Maak van deze outreach-taak een terugkerende (scheduled) task.
Voer ze vanaf nu elke maandag om 9u automatisch uit, en doe telkens
exact hetzelfde als daarnet: stel de merkenlijst samen volgens de
niche-percentages in mijn ideale klant en niche document, schrijf per
merk een korte, persoonlijke DM in mijn tone of voice, verstuur ze
automatisch via Instagram, voeg elk merk toe aan mijn leads tracker met
status "DM verstuurd", en stuur me daarna een bevestiging via push en
e-mail zodra de taak klaar is.
```

Een geplande taak draait zelfstandig op de achtergrond, ook als je de chat niet open hebt. Je kiest zelf het tijdstip en de herhaling, en je kan een melding laten sturen (push en/of e-mail) zodra de taak klaar is. Je kan ze op elk moment aanpassen of stopzetten door in Claude Code te typen: "Verander deze geplande taak naar [nieuw tijdstip]" of "Zet deze geplande taak stop". Wil je een overzicht? Typ "Welke terugkerende taken heb ik?".

---

## Stap 14 — Dagelijkse cyclus: DM opvolging + pitch-mails klaarzetten

Actie: typ in Claude Code:

```
Check mijn Instagram DM's van vandaag. Volg lopende gesprekken op volgens
mijn follow-up structuur document, en werk de status van elk merk bij in
mijn leads tracker (bv. "DM beantwoord", "Mailadres verzameld"). Als een
merk een mailadres deelt, noteer dat mailadres in de tracker en zet een
eerste pitch-mail klaar als draft in Gmail, gebaseerd op mijn tone of
voice, about me en pitch structuur documenten. Kijk ook in mijn leads
tracker welke mailadressen al verzameld zijn maar nog geen pitch-mail
kregen, en zet daar alsnog een pitch-mail voor klaar. Zet de status na
versturen op "Pitch verstuurd".
```

Je kan deze prompt combineren met stap 15 (inbox beheer) in één dagelijkse geplande taak.

---

## Stap 15 — Dagelijkse cyclus: inbox beheer + reply drafts

Actie: typ in Claude Code:

```
Check mijn e-mail inbox van vandaag op reacties van merken. Zet voor elke
reactie een antwoord klaar als draft, gebaseerd op mijn tone of voice en
mijn onderhandelings- en upsell-document waar relevant (bijvoorbeeld bij
prijsvragen, lowball-bod of een gifted voorstel).
```

Maak hiervan een geplande taak samen met die van stap 14, bijvoorbeeld elke ochtend om 8u:

```
Maak hiervan één geplande taak die elke dag om 8u automatisch eerst mijn
Instagram DM's opvolgt en pitch-mails klaarzet (zoals in stap 14), en
daarna mijn e-mail inbox nakijkt en reply-drafts klaarzet (zoals in deze
stap). Stuur me een melding (e-mail of sms, zoals aangegeven in mijn
frequentie en automatiseringsdocument) zodra alles klaarstaat.
```

---

## Stap 16 — Automatische follow-ups

Actie: typ in Claude Code:

```
Ga na welke pitches of voorstellen nog geen antwoord kregen, op basis van
mijn leads tracker en de datum van laatste contact, volgens de cadans in
mijn frequentie en automatiseringsdocument. Verstuur de juiste follow-up,
of zet ze klaar als draft, in lijn met wat ik hierover heb aangegeven in
mijn frequentie en automatiseringsdocument, en volgens mijn follow-up
structuur document. Werk na versturen de status en het aantal follow-ups
bij in mijn leads tracker.
```

Maak ook hiervan een dagelijkse geplande taak, bijvoorbeeld elke ochtend om 8u30:

```
Maak hiervan een geplande taak: voer deze prompt elke dag om 8u30
automatisch uit, en stuur me een melding zodra de follow-ups verstuurd
zijn.
```

---

## Stap 17 — Onderhoud

Dit systeem blijft alleen goed werken als je documenten kloppen.

Actie: neem elke maand 10 minuten om:
- nieuwe merken of samenwerkingen toe te voegen aan je about me document
- je tarieven te controleren en zo nodig aan te passen
- je frequentie of cadans bij te sturen als iets niet meer voelt zoals je wil
- je tone of voice te verfijnen op basis van reacties die goed of net niet goed vielen

---

## Stap 18 — En dan?

Als dit systeem je outreach al makkelijker maakt, dan is dit nog maar het begin. Wil je dieper gaan, je portfolio professionaliseren of je content business structureren? Dat is precies waar Content Cashflow en de Portfolio Sprint voor gemaakt zijn.
