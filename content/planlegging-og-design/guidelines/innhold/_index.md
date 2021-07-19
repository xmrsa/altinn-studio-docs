---
title: Innhold
description: Retningslinjene skal sørge for at vi får et ensrettet språk og forståelig innhold i tjenestene som lages i Altinn. 
weight: 20
---

Som hovedregel bør du bruke retningslinjene fra [Språkrådet](https://www.sprakradet.no/klarsprak/om-skriving/generelle-skriverad-bokmal/) når du skriver. I tillegg har vi definert noen mer spesifikke regler for Altinn som vi anbefaler at du følger. 

## Målform
Har vi noen krav til at tjenestene skal eksistere på ulike målformer? 

## Innhold i skjema
Brukeren skal ikke trenge å få feilmelding for å forstå hva som skal til for å fylle ut skjemaet riktig. Dette bør tydelig komme frem i informasjonstekst i begynnelsen av skjemaet og i labels som tilhører hvert enkelt skjemafelt. 

Som hovedregel bør man kun spørre om informasjon som er helt nødvendig å innhente. Du kan derfor opplyse i starten av skjemaet om at alle felt er påkrevde og må fylles ut (for å slippe å markere alle som påkrevde). Frivillige felt kan eventuelt markeres med "frivillig" i selve labelen til feltet.

### Formulering av feilmeldinger
Vær kort og tydelig i formuleringen av feilmeldingene og sørg for at brukeren vet hva som må gjøres for å komme videre. Å skrive "Feltet er påkrevd" gir ikke brukeren en forklaring på hva som er feil. 

Eksempel på forklarende feilmeldinger: 
- "Postnummer må ha 4 siffer"
- "Du må velge minst ett leveringsalternativ"
- "For å sende inn skjemaet må du bekrefte at navnet er korrekt ved å huke av i avkrysningsboksen"

Les mer om å formidle feil i skjema på [UU-tilsynets nettsider](https://www.uutilsynet.no/wcag-standarden/skjema/38#formidle_feil_i_skjema).

### Fordel innholdet i flere steg og bruk sporvalg
Dersom du har mye innhold må skjemaet deles opp i flere sider. Hver side bør kun inneholde én informasjonsdel. Brukeren skal ikke trenge å ta mer en en avgjørelse per side. Se eksempel: [Starte enkeltpersonforetak](dsf).

Brukeren skal slippe å svare på mer enn nødvendig. Dersom brukeren har svart nei på et spørsmål og du dermed kan skjule flere av stegene for ham, kan du gjøre dette med [dynamisk sporvalg](https://altinn.github.io/docs/altinn-studio/app-creation/ux/sporvalg/).

### Hjelpetekster
Hjelpetekster er små tekstsnutter som kan brukes når brukeren kan trenge mer informasjon, men hvor det ikke er naturlig å bruke plass på det i grensesnittet. Bruk hjelpetekst for å gi veiledning i utfylling av skjema-felter, utdype bakgrunn for et regelverk eller når du skal forklare vanskelige begreper.

### Disabled
Ved å vise skjemafelt som disabled forventer man at brukeren skal vite hvorfor de ikke kan bruke elementet, men dette er ikke alltid tilfellet. Noen brukerer forstår heller ikke at feltet er deaktivert, som igjen kan føre til forvirring. Bruk av disabled bør derfor unngås. Dersom en handlingen av en eller annen grunn ikke er tillatt, kan dette i stedet forklares i en informasjonstekst.

## Oppdeling av tall
Riktig og konsekvent oppdeling av tallene hjelper brukeren å lese og skille forskjellige typer nummer. Ingen av nummerne skal skilles med punktum, kun mellomrom. I felt hvor brukeren skal skrive inn lengre nummer er det hjelpsomt å indikere antall siffer.

- Organisasjonsnummer deles opp i tre og tre: 123 456 789
- Bankkonto deles opp i fire, to og fem: 1234 56 78901
- Personnummer deles opp i seks og fem: 123456 78901
- Mobilnummer deles opp i tre, to og tre: 987 65 432
- Fasttelefon og faks deles opp i to og to: 98 76 54 32

### Tid og dato
- Klokkeslett skriver vi kun med timer og minutter, aldri sekunder. Klokkeslett skrives slik: 13:45
- Dato skal som hovedregel skrives slik: 05.06.2017
- Unntaksvis kan datoer skrives slik i løpende tekst: 5. juni 2017

## Generelle anbefalinger
- Bruk et muntlig og lett språk
- Skriv direkte til brukeren (bruk «du») 
- Forklar hva som er neste steg 
- Skriv kort, klart og klikkbart 
- Skriv tekster som kan skummes 
- Vær spesifikk om innholdet, men sørg samtidig for å bruke ord som alle kan forstå 

### Unngå:
- lange ord 
- lange setninger  
- kryptiske eller lyriske overskrifter  
- flere poenger i samme setning 
- flere poenger i samme avsnitt 
- VERSALER (store bokstaver) 

### Lengde på tekst:
- overskrifter: maks. 8 ord 
- setninger: 15-20 ord
- avsnitt: 40-80 ord 

## Skriv rett frem
Formelt språk er ofte skrudd sammen slik at utsagnet (verbet) kommer sent i setningen. Det gjør at man må lese mange ord før man får verbet. Det krever mer av leseren som må huske hva som stod tidlig i setningen. Verbet bør stå så tidlig som mulig i setningen og bør stå så nært subjektet som mulig. 

**Eksempel:**  
Arbeidstaker har en del plikter som må oppfylles →
<br>Arbeidstaker må oppfylle en del plikter

### Unngå verbalsubstantiver
Verbalsubstantiver gjør teksten unødvendig tung å lese.
Et verbalsubstantiv er et substantiv dannet av et verb, for eksempel at «å utrede» blir til «å foreta en utredning»,
der utredning er selve verbalsubstantivet. De fleste verbalsubstantiv slutter på «-ing» og «-else».  

En tekst med mange verbalsubstantiver blir abstrakt fordi den fjerner seg fra de konkrete handlingene den egentlig beskriver.
Teksten blir mer konkret når vi bruker verbene i stedet.  

**Eksempler:**  
- Ved avtaleinngå**elsen** → Da avtalen ble inngått
- Ny henvend**else** → Kontakt oss
- Innmeld**ing** av feil → Meld inn feil

### Skriv aktivt, ikke passivt: 
I lovspråk blir det ofte skrevet at noe skal gjøres og det er ikke ønskelig å si noe om hvem som skal gjøre det.
I Altinn sine løsninger vil det gjerne være flere enn en person som skal gjøre noe, men vi kan skrive direkte til brukeren likevel.

**Eksempel:**  
Forberedelser og planleggingsaktiviteter må gjennomføres før utviklingen av tjenesten(e) kan og bør starte → <br>Gjør forberedelser og planlegg godt før du utvikler tjenesten. 