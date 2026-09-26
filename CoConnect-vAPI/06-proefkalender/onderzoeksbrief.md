# vAPI Network: LinkedIn-onderzoeksbrief voor een tweeweekse proefkalender

Dit document bundelt het onderzoek naar wat in 2026 werkt op LinkedIn voor een pre-launch B2B tech/web3-startup. Gebruik het als bron en opdracht om een **tweeweekse test-contentkalender** te maken.

Onderzoek uitgevoerd op 26 september 2026. De bronnen zijn vooral van maart tot augustus 2026, met enkele van eind 2025.

---

## 1. Opdracht voor Claude Code

Maak een tweeweekse proefkalender voor vAPI Network met:

- **Accounts:** de persoonlijke LinkedIn-profielen van de founders (hoofdkanaal) en de bedrijfspagina van vAPI (ondersteunend).
- **Doelgroepen:** B2B-content én B2C-content. Dat is de wens van het bureau; de hoofdnadruk ligt op B2B.
- **Posttekst:** volledig uitgeschreven, direct te plakken, in het **Engels**.
- **Onderbouwing:** per post een korte regel "waarom deze post" die verwijst naar de principes in dit document, zodat Lotte het aan het bureau kan uitleggen.

### Gewenste output

1. `kalender.md`: een overzichtstabel met de kolommen **Datum | Dag | Account | Doelgroep (B2B/B2C) | Pijler | Format | Hook | Status**.
2. `posts.md`: per post de volledige tekst, het format, de visuele instructie (bij een carrousel: de tekst per slide) en de onderbouwing in één regel.
3. `kalender.csv`: dezelfde data als de tabel, om te importeren in een planner of spreadsheet.

### Randvoorwaarden

- **Startdatum:** eerstvolgende maandag, tenzij Lotte iets anders opgeeft.
- **Ritme per founderprofiel:** 3 posts per week (zie §4).
- **Bedrijfspagina:** 2 posts per week, vooral het delen van founderposts met eigen commentaar, plus een aankondiging of mijlpaal.
- **Onderwerpen:** houd het bij de 3 vaste pijlers (§3). Geen posts daarbuiten.
- **Taal rond crypto:** volg §8 strikt.
- **Geen verzonnen feiten:** geen cijfers over vAPI (gebruikers, volume, klanten) die niet in dit document staan. Gebruik anders een zichtbare placeholder zoals `[CIJFER INVULLEN]`.
- **Placeholders voor ontbrekende gegevens,** zoals een tweede founder als die er is: `[FOUNDER 2: NAAM]`.

---

## 2. Wat we weten over vAPI (context)

- **Wat het is:** vAPI Network laat AI-agents diensten vinden, betalen in stablecoins, gespecialiseerde agents of mensen inhuren en resultaten ontvangen, zonder accounts, dashboards of handmatige workflows.
- **Techniek:** gebouwd op x402 (betaalstandaard van agent naar dienst) op Base (Coinbase L2). Betaling in USDC.
- **Producten:** **Call** is live (agents betalen voor losse API-/MCP-diensten). **Tasks** en **Compute** komen nog.
- **Het pre-launchproduct** (zoals Lotte het beschreef): een platform waar bedrijven AI-agents of mensen inhuren voor afgebakende klussen, met betaling via escrow in USDC.
  - *Aanname, niet bevestigd:* dit is vermoedelijk **Tasks**. Laat dit bevestigen door het bureau (contactpersoon: Rik) voordat posts het product bij naam noemen.
- **Open source:** een non-custodial TypeScript-toolkit (CLI, MCP-server). De sleutel blijft versleuteld op de eigen machine en er gaat standaard geen telemetrie de deur uit.
- **Founder:** Mark (X: @MarkTbuilds). Andere founders zijn nog onbekend.
- **X-account:** @vAPI_Network, sinds januari 2026, ongeveer 1.155 volgers (peildatum september 2026).
- **Doel van de opdracht:** pre-launch publiek en vertrouwen opbouwen, en binnen 3 maanden organische B2B-leads. Podcastbeheer hoort erbij.

### Doelgroepen (werkhypothese)

- **B2B:** AI-agentbouwers en devteams; API-aanbieders die diensten willen aanbieden en laten betalen; bedrijven die klussen willen uitbesteden aan agents of mensen; fintech- en payments-mensen die geïnteresseerd zijn in stablecoin-infrastructuur.
- **B2C:** freelancers en zzp'ers die via het platform betaald willen worden voor klussen (de "mensen" in agents-of-mensen), en tech-nieuwsgierige early adopters.

---

## 3. Contentpijlers (vast, kies er per post één)

1. **De agent-economie:** wat verandert er als software zelf diensten inkoopt en uitbesteedt? Wie is aansprakelijk, hoe werkt vertrouwen?
2. **Betalen en escrow voor agents:** waarom agents een betaallaag nodig hebben, waarom escrow (geld vasthouden tot het werk af is), en waarom stablecoins/USDC als praktische betaalrail.
3. **Build in public:** pre-launchupdates, keuzes, fouten en lessen van de founders.

Waarom maar drie: het algoritme beoordeelt of een account geloofwaardig is op een onderwerp (§4). Wie te breed post, kan het model niet goed indelen.

---

## 4. Hoe het LinkedIn-algoritme nu werkt (2026)

### Het systeem

- LinkedIn rankt posts met één AI-model, **360Brew**. Het leest een post samen met het profiel van de auteur, diens eerdere posts en de geloofwaardigheid van wie reageert. In feite stelt het de vraag: heeft dit account het recht om over dit onderwerp te praten?
- De verspreiding gaat op interesse in plaats van netwerk. Content die niet aansluit bij de specifieke interesses van lezers verschijnt niet in hun feed, ook niet als ze je volgen.

### Wat bereik geeft

- **Een vast onderwerp:** regelmatig posten over 3 à 4 specifieke onderwerpen.
- **Originaliteit:** een eigen invalshoek, eigen data of eigen ervaring. Gerecycled advies presteert slechter.
- **Echte gesprekken:** drie inhoudelijke reacties wegen zwaarder dan dertig likes.
- **Saves** gelden als het sterkste engagementsignaal.
- **Het eerste uur:** een nieuwe post wordt eerst getest bij 2 à 5% van het netwerk. Maar ongeveer 5% van de posts die in het eerste uur slecht presteren herstelt nog.
- **Snel reageren:** binnen 15 minuten, in 2 à 3 zinnen, minstens het eerste uur.

### Wat onderdrukt wordt

- Engagement-bait, woede-posts en lege motivatiequotes. LinkedIn stelde dat 60% van de posts met veel engagement in 2025 trucs gebruikte die gebruikers niet tevredener maakten.
- **Engagement pods** (groepjes die elkaars posts liken) worden actief opgespoord en afgestraft.
- **Pure AI-tekst** wordt volgens één bron afgestraft. Elke post heeft een eigen stem en specifieke details nodig.

### Omstreden: externe links

- Eén bron (Dataslayer): ongeveer 60% minder bereik met een externe link, en de link in de eerste reactie wordt ook afgestraft.
- Een andere analyse (ContentIn, 513 accounts): geen meetbare straf, het verschil was een muntworp.
- **Beslissing voor de kalender:** geen links als hoofdzaak van een post. De inhoud staat volledig in de post zelf; een link mag hooguit ondersteunend zijn.

### Persoonlijk profiel versus bedrijfspagina

- Een grote studie uit 2026: gemiddeld **2,6% engagement voor persoonlijke profielen tegenover 1,6% voor bedrijfspagina's**, en 237% meer reacties per post.
- Losse claims van 3x of 8x meer engagement zijn niet breed bevestigd; gebruik ze niet als feit.
- **Beslissing:** de founderprofielen zijn het hoofdkanaal. De bedrijfspagina versterkt hun posts.

---

## 5. Postfrequentie en ritme

- "Elke dag posten" is achterhaald. **3 per week is het minimum, 5 is optimaal voor groei**, en boven de 7 nemen de opbrengsten af.
- Kwaliteit gaat boven volume: liever 3 diepgaande posts dan dagelijks iets oppervlakkigs.
- **Dagelijks naast het posten:** 15 à 20 minuten inhoudelijk reageren bij een vaste lijst van 30 à 50 doelaccounts (ideaal klantprofiel plus accounts met overlappend publiek). Dit geldt als de tactiek met de meeste hefboom, en bijna niemand doet het systematisch.
- Geen tijdschema in de kalender opnemen dat niet haalbaar is. Voeg per postdag een regel toe: "reactieblok 15 min na posten".

### Aanpak voor de eerste 30 dagen (de proefkalender beslaat week 1 en 2)

- **Week 1:** profielen scherpstellen, 3 pijlers vastleggen, doelaccountlijst maken, 2 à 3 posts per founder.
- **Week 2 tot 4:** 3 posts per week per founder (1 carrousel, 1 tekstpost met standpunt, 1 build-in-public-update of podcastclip), dagelijks reactieblok.

---

## 6. Formats en lengte

| Format | Wat de data zegt | Gebruik in kalender |
|---|---|---|
| Document/PDF-carrousel | Topformat in elke dataset. Socialinsider: 7,00% (gemiddelde over alles: 5,20%). Buffer meet een mediaan van 21,77%; het verschil komt door de rekenmethode. | 1× per week per founder, 8 à 12 slides |
| Tekstpost | Engagementpercentage stijgt tot 2,77% bij 2.200 tekens of meer; absolute interacties pieken bij 900 à 1.299 tekens | 1.000 à 2.000 tekens |
| Multi-image | Tweede na documenten (circa 6,45%) | Optioneel |
| Video | Videoweergaven op bedrijfspagina's met 36% gedaald op jaarbasis | Alleen als podcastclip, 30 à 90 sec, met ondertiteling |
| Poll | Een van de zwakste formats; werkt vooral bij pagina's met meer dan 50.000 volgers | **Niet gebruiken** |

**Carrouselopbouw:** een stapsgewijze uitleg van een proces waar de doelgroep om geeft, in 8 à 12 slides.

---

## 7. Hooks

Een goede hook noemt een specifiek publiek, raakt een pijnpunt en belooft iets concreets. De eerste regels moeten lezers laten doorklikken op "meer weergeven".

Voorbeelden om te gebruiken of als model te nemen:

1. *"AI agents can write your code, research your market and draft your contracts. They still can't get paid. That's the gap we're building for."*
2. *"Paying a contractor abroad in 2026: 2–5 days and $25–50 in fees. Paying them in USDC: under a minute. Here's why we built escrow on the second one."* (Cijfers: Request Finance, 2026.)
3. *"If an AI agent does the job wrong, who gives the money back? We spent three weeks on that one question. Here's where we landed."* (Let op: de "drie weken" is illustratief. Vervang door het echte verhaal of maak het `[PERIODE INVULLEN]`.)
4. *"Pre-launch week [X]: 3 things we assumed about hiring AI agents that turned out wrong."*
5. *"Hot take: most 'AI agent marketplaces' are directories. A marketplace needs one thing directories don't: a way to hold the money until the work is done."*

**Vermijden:** "Agree?", "Thoughts?" als enige afsluiter, clickbait zonder inhoud, en claims die de founders niet kunnen onderbouwen.

---

## 8. Crypto/web3 brengen aan een sceptisch zakelijk publiek

- Bedrijven geven niet om ideologie, maar om **snelheid, kosten en betrouwbaarheid**. Succesvolle boodschappen zijn verschoven van decentralisatie naar bruikbaarheid, transparantie en toegankelijkheid.
- Voor nieuwe gebruikers moet crypto **onzichtbaar** voelen: gewoon een betere manier om geld te verplaatsen.
- **Begin bij stablecoins.** Die halen de volatiliteit uit het gesprek.
- **Brengen als bedrijfsbeslissing,** niet als aanbeveling van crypto.
- **Regelgevend kader om naar te verwijzen:** de GENIUS Act (eerste federale kader voor betaal-stablecoins in de VS) en MiCA in de EU.
- **Kostenvergelijking die je mag gebruiken** (Request Finance, 2026): een internationale overboeking kost $25–50 aan verzendkosten, eventueel $10–30 aan ontvangstkosten, 1,5–3% FX-spread buiten USD, en 2–5 werkdagen. Een USDC-transfer kost ongeveer $0,01–0,10, is binnen een minuut rond en heeft geen FX-spread.

### Woordkeuze

- **Gebruik:** "payments in digital dollars (USDC)", "escrow", "settlement", "stablecoin rails", "pay per task".
- **Vermijd:** token, koers, "to the moon", "WAGMI", "web3" als verkoopargument, speculatie, rendement.

---

## 9. Van podcast naar LinkedIn-content

- **Per aflevering van 30 à 45 minuten:** 5 à 10 LinkedIn-stukken (3 à 5 videoclips, quotekaarten, een carrousel, tekstposts). Genoeg voor ongeveer twee weken posten.
- **Opname:** op video. Knip clips van 30 à 90 seconden, met ondertiteling.
- **Volgorde na publicatie:**
  - Dag 1: de sterkste clip.
  - Daarna: een carrousel met het kernframework uit de aflevering.
  - Dan: een quotekaart.
  - Dan: een tekstpost over het pijnpunt dat de gast benoemde.
- **Gasten laten meeverspreiden:** maak het ze makkelijk (tag ze, lever de clip en tekst aan).
- **Ritme:** liever tweewekelijks en volhouden dan wekelijks en stoppen. Een gat van zes weken na drie maanden wekelijks doodt de vaart.

**Voor de kalender:** er is nog geen aflevering bekend. Reserveer 1 slot per week voor een podcastclip met de placeholder `[PODCAST: AFLEVERING/CLIP INVULLEN]`, of voor een teaser van de eerste aflevering.

---

## 10. Realistische benchmarks (om verwachtingen te managen)

- **Engagementpercentage** voor accounts onder de 10.000 volgers: mediaan 2,17% à 2,42%. De onderste 25% van kleine accounts zit onder 0,5%, de bovenste 25% boven 2,4%.
- **B2B-techpubliek** scrolt snel en reageert zelden. Lage aantallen reacties zijn normaal.
- **Volgersgroei:** 100 à 300 volgers in de eerste 30 dagen. Bij 3 à 5 posts per week 1.000 à 3.000 volgers in 6 maanden. Meestal pas vaart in maand 3 à 4.
- **Eerste organische lead:** 60 à 90 dagen. Het doel van leads binnen 3 maanden is haalbaar, maar krap.
- **Leaddefinitie pre-launch (voorstel):** wachtlijstaanmeldingen, design partners en DM-gesprekken met beslissers. Meet die vanaf week 1.

---

## 11. Fouten die de kalender moet vermijden

- Alleen vanaf de bedrijfspagina posten.
- Posts buiten de 3 pijlers.
- Pure AI-tekst zonder eigen stem of specifieke details.
- Engagement pods of gekochte interactie.
- Posts in het eerste uur bewerken (één bron zegt dat dit de testfase reset; niet breed bevestigd, maar controleer typfouten vooraf).
- Crypto-hype of speculatieve taal.
- Volgers als hoofdmaatstaf; meet gesprekken en wachtlijst.

---

## 12. Betrouwbaarheid van de bronnen

- **Breed bevestigd door meerdere bronnen:**
  - persoonlijke profielen presteren beter dan bedrijfspagina's;
  - vaste onderwerpen/topic-authority;
  - carrousels/documenten zijn het topformat;
  - het belang van het eerste uur en van reacties;
  - kwaliteit boven volume;
  - polls zwak voor kleine accounts.
- **Omstreden:** de straf op externe links.
- **Zwak onderbouwd (niet als feit gebruiken):** losse vermenigvuldigers zoals 3x of 8x, en "277% meer leads". Die komen vooral van tools en bureaus met een commercieel belang.
- **Weinig web3-specifieke data:** de meeste inzichten komen uit algemene B2B-LinkedIn-data en zijn vertaald naar web3.

---

## 13. Bronnen (selectie, met datum)

- Dataslayer, LinkedIn Algorithm 2026 (juli 2026)
- The Scott Partnership, 360Brew B2B guide (aug 2026)
- Falia, 360Brew explained (apr 2026)
- LinkedGrow, LinkedIn algorithm 2026 (aug 2026)
- Leaders.social, algorithm changes 2026 (aug 2026)
- Predis.ai, LinkedIn algorithm 2026 (mei 2026)
- Inspired Marketing B2B, engagement data 2026 (sep 2026)
- Socialinsider, LinkedIn Organic Benchmarks 2026 (jul 2026)
- ContentIn, Engagement Benchmarks, 100.000 posts (aug 2026)
- Extrovert, engagement rate benchmarks (aug 2026)
- Contentio (Buffer-data), engagement rate (mei 2026)
- Teract, groei in 30 dagen (mrt 2026)
- Windmill Growth, how to grow 2026
- Rethoric, founder growth strategy
- ConnectSafely, LinkedIn podcast strategy (aug 2026)
- Podmuse, podcast on LinkedIn (jun 2026)
- ContentBuck, podcast repurposing (jun 2026)
- GoodFirms, crypto marketing B2B (mei 2026)
- Blockchain App Factory, crypto marketing 2026 (jan 2026)
- Silence Laboratories, B2B stablecoin payments (jul 2026)
- Request Finance, stablecoin B2B guide (jun 2026)
- vAPI Network: GitHub-repo en Glama-pagina (MCP), X-account @vAPI_Network
