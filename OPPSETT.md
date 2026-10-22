# HRS Sambandsøving: oppsett

**Detaljert steg-for-steg-guide for iPhone/iPad, med lenker og skjermbilder:** https://claude.ai/artifact/8kGKSJVCso62jXFF7t6Gtg

Siden: https://hilstan-web.github.io/hrs-bot/

## 1. Test nå, uten noe oppsett
Åpne artifact-lenken i claude.ai: https://claude.ai/artifact/RaGrih7rSKD2QopEne8KB3
- Claude svarer via claude.ai-kontoen din. Ingen nøkkel trengs.
- HRS snakker med norsk stemme, men claude.ai sperrer mikrofonen. Du skriver det du ville sagt på radio.
- Første gang spør siden om lov til å bruke Claude. Svar ja.

## 2. Full tale (snakk og få svar), på PC
1. Last ned `hrs-sambandsoving.html` fra prosjektet.
2. Åpne den i **Microsoft Edge** (høyreklikk, Åpne med, Edge). Edge har norsk talegjenkjenning og naturlige norske stemmer gratis.
3. Lag en Claude API-nøkkel:
   1. Gå til https://platform.claude.com og lag konto (e-post).
   2. På https://platform.claude.com/settings/billing legger du inn kort og kjøper kreditt, f.eks. 5 USD.
   3. På https://platform.claude.com/settings/keys trykker du **Create key**, gir den navnet «HRS-bot» og kopierer nøkkelen (starter med `sk-ant-`).
4. I HRS-siden: åpne **Innstillinger**, lim inn nøkkelen. Den lagres bare i din nettleser.
5. Velg stemme (anbefalt: Finn eller Pernille «Online (Natural)»), velg case og trykk **Start oppdrag**.
6. Hold **SNAKK** (eller mellomrom, eller en fotpedal som sender mellomrom) mens du snakker. Edge spør om mikrofon første gang: tillat.

Kostnad (anslag, ikke målt): ca. 0,2 kr per HRS-svar, ca. 10 kr for en øving på 50 sendinger.

Ikke del fila videre med nøkkelen lagret, og ikke legg nøkkelen inn på delte maskiner. Nøkkelen kan slettes i Console når som helst.

## Hvis mikrofonen ikke virker fra fila
Noen nettlesere sperrer mikrofon for filer som åpnes lokalt. Da kan siden legges på en privat nettadresse (f.eks. GitHub Pages). Si fra, så setter Claude det opp.

## iPhone og iPad

### Rask test i dag: Claude-appen med stemmemodus
1. Åpne `claude-app-HRS-prompt.txt`, kopier alt og lim det inn i en ny samtale i Claude-appen. Send.
2. Trykk på stemmeknappen og si «start case 1».
3. Si «øving slutt» for å få debrief.
Ingen nøkkel eller oppsett. Instruktørpanel og skjult fasit finnes ikke her, og Claude gir nye opplysninger selv underveis.

### Full øving: HRS-siden i Safari
Siden må ligge på en sikker nettadresse (https) for at iPhone skal slippe til mikrofonen. Anbefalt: GitHub Pages, gratis.
1. Gå til https://github.com/new, kall repoet `hrs-bot`, velg **Public**, huk av **Add a README** og trykk **Create repository**. Siden inneholder bare fiktive øvingsdata, ingen nøkler.
2. Gi Claude tilgang: https://github.com/apps/claude/installations/select_target, velg kontoen din og repoet `hrs-bot`.
3. Si fra i tråden. Claude legger inn siden.
4. I repoet: **Settings → Pages → Branch: main → Save**. Etter et minutt er siden på `https://hilstan-web.github.io/hrs-bot/`.
5. Åpne adressen i Safari på iPhone/iPad, trykk Del → **Legg til på Hjem-skjerm**.
6. Lim inn Claude API-nøkkelen under Innstillinger (se steg 3 i PC-delen over). Nøkkelen lagres bare på den enheten.
7. Last ned forbedret norsk stemme: Innstillinger → Tilgjengelighet → Opplest innhold → Stemmer → Norsk.
