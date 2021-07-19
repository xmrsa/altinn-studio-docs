---
title: Design
description: De ulike komponentene er laget for at de skal passe sammen i en større helhet. Det er derfor viktig å følge retningslinjene for hvordan disse brukes for å oppnå et konsistent og gjenkjennbart uttrykk. 
weight: 10
---

Målet vårt er å skape konsistens på tvers av tjenester som lages i Altinn Studio. Når brukere møter en ny tjeneste, har de med seg forventninger fra tidligere opplevelser. Når disse forventningene møtes, kreves det mindre av brukeren for å samhandle med komponentene, og det bygges selvtillit. Ved å ikke trenge å lære nye interaksjoner, vil brukerens fokus i større grad være på innholdet.

Vi anbefaler **ikke** å endre CSS for individuelle tjenester som bruker Altinn-designet. Dersom vi åpner opp for designendringer og fargeendringer, vil dette skade konsistensen mellom tjenestene. Konsekvent design mellom tjenesteeiere er noe vi bør strekke oss mot. For å få det til kreves et godt samarbeid mellom fagmiljøet i Altinn og hos de ulike tjenesteeierene. **Vi ønsker oss en god felles løsning som kan brukes og forbedres av alle, fremfor mange forskjellige løsninger gjennom ulike CSS-endringer.** Dette vil også gjøre det lettere å kontrollere tilgjengeligheten på tvers av apper på plattformen vår. Velger du likevel å gå bort fra designet, ligger ansvaret for å følge WCAG-krav på deg. 
<br><br>

{{% panel %}}**Har du laget en ny komponent som bør tas inn i Altinns bibliotek?**<p>Vi ønsker at alle er med på å videreutvikle biblioteket av komponenter med både design og kode. I praksis vil dette si at Altinn ønsker å ta imot forslag til nye komponenter etter hvert som tjenesteeierne ser behovet for det. </p>

<div class="a-btn-group" id="btnGroup">

  <a href="https://github.com/Altinn/altinn-studio/issues/new/choose" class="a-btn mt-1 ">
    Opprett en sak i github
  </a>
  <a href="http://altinnstudio.slack.com" class=" ">
    Skriv til oss på Slack
  </a>
</div>

{{% /panel %}}

## Inngang til skjema
Brukertester har vist at når brukerne starter på etaten/kommunens sider for å fylle ut et skjema og så blir sendt videre til Altinn, får de ofte opplevelsen av at «plutselig var jeg i altinn». Innganger til skjema bør derfor presenteres slik at det er tydelig at man går til Altinn, men samtidig slipper å gå innom unødvendige mellomledd. "Start innsending" bør lenke direkte til skjemaet. Opplevelsen til bruker vil da også i større grad bli at man får løst oppgaven i konteksten man er i, men at Altinn er brukt som løsning for innsending og historikk. 

![Inngang til et skjema i Altinn bør presenteres tydelig](lenketilaltinn.png "Inngang til et skjema i Altinn bør presenteres tydelig")

<br>
{{% panel %}}
<i class="ai ai-info-circle"></i> **Integrerte komponenter** <br><br> I tett samarbeid med sentrale tjenesteeiere planlegger vi på sikt å kunne tilby komponenter som kan benyttes på etatens nettsider, slik at brukerne kan løse oppgaven i den konteksten de er i. Vi kaller det en brukerreise med **distribuert modell**, som for brukeren vil si at kontaktpunktene blir på etatens løsning. 
<br>

Altinns brukere ønsker både løsning der de er og en samlet oversikt. Og de bør få begge deler. Men behovene dekkes best på litt forskjellige måter.

{{% /panel %}}

## Retningslinjer for UI-komponenter

UI-komponenter som foreløpig inngår i Altinns bibliotek:
- [Tittel og avsnitt](/planlegging-og-design/guidelines/design/#-tittel-og-avsnitt)
- [Logo og kontaktinfo](/planlegging-og-design/guidelines/design/#-logo-og-kontaktinformasjon) *(⚠️ Kommer snart til Altinn Studio)*
- [Inputfelt](/planlegging-og-design/guidelines/design/#-inputfelt)
- [Avkrysningsbokser og radioknapper](/planlegging-og-design/guidelines/design/#-avkrysningsbokser-og-radioknapper)
- [Knapp og lenke](/planlegging-og-design/guidelines/design/#-knapp-og-lenke)
- [Filopplasting](/planlegging-og-design/guidelines/design/#-filopplasting)


<hr>

### ❖ Tittel og avsnitt
Det bør som hovedregel alltid være en header (H2) og et avsnitt i starten på en skjamaside for å oppsummere brukerens oppgave.


**Retningslinjer:**
- Tekstlengde på avsnitt strekkes ikke ut 100% i modalboksen, ettersom lange linjer tekst forstyrrer flyten i lesingen. Avsnitt er derfor begrenset til maks 696px i bredden, selv om modalen fyller ut 1056px. 

- Teksten skal alltid være venstrestilt. 

<br>

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D2815%253A680" allowfullscreen></iframe>

<hr>

### ❖ Logo og kontaktinfo
Hensikten med komponenten er at brukeren tydelig skal kunne se hvem eieren av tjenesten er, og hvem som kan kontaktes dersom brukeren trenger hjelp med utfylling av skjemaet. Svært mange av henvendelsene til Altinn Brukerstøtte er knyttet til feil kontaktpunkt.


{{% panel theme="warning" %}} ⚠️ Denne komponenten er ikke tilgjengelig i Altinn Studio enda. 
{{% /panel %}}

**Retningslinjer:**
- Logoen bør lastes opp i breddeformat dersom mulig. 
- Bakgrunnsfarge kan tilpasses etatens logo og profil.

<br>

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D2816%253A2290" allowfullscreen></iframe>

<hr>

### ❖ Knapp og lenke
Hovedknapp (blå) brukes for å sende brukeren til neste steg. 

**Retningslinjer:**
- Det skal kun være en hovedknapp per side. Sekundærvalg kan legges til som knapper stylet som lenker.
- Teksten på knappen skal være tydelig. Som regel fungerer "Neste" bra, men knappen kan også formuleres som svar på et spørsmål (se eksempel under).
- På siste steg i skjemaet (innsending) skal hovedknappen være grønn.

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D3495%253A809" allowfullscreen></iframe>

<hr>

### ❖ Inputfelt
Inputfelt brukes når brukeren skal føre inn tekst eller tall. 

**Retningslinjer:**
- Et inputfelt skal alltid ha en tilhørende label med forklarende tekst.
- Ta en vurdering på om ekstra beskrivelser og hjelpetekster må kobles til input elementet.
- To inputfelt kan plasseres ved siden av hverandre dersom de på et eller annet vis hører sammen. Se eksempel under.
- Deaktivert felt bør unngås. Dersom et felt ikke kan redigeres bør informasjonen heller presenteres i tekst. 

<br>

**Eksempel på bruk:**
<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D2816%253A1332" allowfullscreen></iframe>
<br><br>

<hr>

#### ❖ Stort tekstfelt
Stort tekstfelt benyttes når brukeren skal fylle inn en lengre beskrivelse. De samme retningslinjene som inputfelt gjelder. 

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D3495%253A656" allowfullscreen></iframe>
<br><br>

<hr>

#### ❖ Adresse
For adresse finnes det et fast oppsett der postnr og poststed er sidestilt under datofeltet. Postfelt fylles ut automatisk basert på postnr-input. 

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D2911%253A652" allowfullscreen></iframe>
<br><br>

<hr>

#### ❖ Datovelger
I forbindelse med planlegging, eller for datoer i nærliggende tid kan du bruke datovelgeren.

**Retningslinjer:**
-  Dersom du skal hente inn en fødselsdato eller andre datoer lengre tilbake i tid, er ikke datovelgeren et anbefalt alternativ, se studier fra [gov.uk](https://design-system.service.gov.uk/patterns/dates/#asking-for-memorable-dates) I disse tilfellene kan du heller bruke [datofeltet](/planlegging-og-design/guidelines/design/#-datofelt).
-  Legg til korrekt validering og gi brukeren informasjon om hva som er gyldige datoer å velge. Skal brukeren kunne velge datoer tilbake i tid? Innenfor en gitt periode?

<br>

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D4833%253A961" allowfullscreen></iframe>

<hr>

#### ❖ Datofelt
For datoer lengre tilbake i tid, eller datoer brukeren kjenner godt, bør datofelt benyttes. Tre tekstfelt er i disse tilfellene den enkleste måten for brukeren å fylle ut datoen. Dersom det er noe som skal planlegges eller tilfeller der en spesifikk dag er viktig, bruk [datovelgeren](/planlegging-og-design/guidelines/design/#-datovelger) i stedet. 
<br>

{{% panel theme="warning" %}} ⚠️ Denne komponenten er ikke tilgjengelig i Altinn Studio enda. 
{{% /panel %}}

**Retningslinjer:**
- Bruk alltid label på hver av de tre boksene (dag, måned, år), og legend for hele input-gruppen. 
- Om datagrunnlaget finnes, kan en spesifikk dato være foreslått i feltet. Ellers kan eksempelinnholdet være dagen i dag. 

<br>

**Eksempel på bruk:**
<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D5139%253A832" allowfullscreen></iframe>
<br><br>

<hr>

### ❖ Avkrysningsbokser
Avkrysningsbokser brukes i tilfeller der brukeren kan huke av ett eller flere alternativer fra en liste. Dersom brukeren kun kan velge et av alternativene, bruk [radioknapper](/planlegging-og-design/guidelines/design/#-radioknapper) i stedet. 

**Retningslinjer:**
- Avkrysningsboksene skal stå foran tilhørende tekst, og skal aldri stå alene.
- Deaktiverte avkrysningsbokser bør unngås. Dersom et valg ikke er tilgjengelig bør det heller fjernes og forklares i tekst hvorfor det mangler. 

<br>

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D5295%253A1181" allowfullscreen></iframe>

<hr>

### ❖ Radioknapper
Radioknapper brukes i tilfeller der brukeren skal velge et alternativ blant flere. Det samme gjelder nedtrekksliste, så vær bevisst på når du bruker hvilken.  

Radioknapper velges når:
- Du ikke har for mange valgalternativer (Maks 7) 
- Det ikke er et tydelig anbefalt valg
- Når brukeren enkelt skal kunne sammenligne alternativene 
- Du ønsker at brukeren skal lese alle alternativene
- Valgalternativene er ukjent for brukeren


**Retningslinjer:**
- Radioknapper skal stå foran tilhørende tekst, og skal aldri stå alene.
- Deaktiverte radioknapper bør unngås. Dersom et valg ikke er tilgjengelig bør det heller fjernes og forklares i tekst hvorfor det mangler. 

**Eksempel på bruk:**


<hr>

### ❖ Nedtrekksliste
Nedtrekksliste brukes i tilfeller der brukeren skal velge et alternativ blant flere. Det samme gjelder radioknapper, så vær bevisst på når du bruker hvilken.  

Nedtrekksliste velges når:
- Du har mange alternativer (mer enn 5)
- Du har et anbefalt valg som vises som forhåndsvalgt
- Det ikke er så viktig for brukeren å kunne sammlenligne alternativene
- Du ønsker ikke at brukeren skal trenge å lese alle alternativene
- Valgalternativene er kjent for brukeren

<br>

**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="250" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D1746%253A7662" allowfullscreen></iframe>

<br>
 
<hr>



### ❖ Valideringsmeldinger


**Eksempel på bruk:**

<iframe style="border: 3px solid rgb(0 0 0 / 90%);border-radius: 9px;" width="100%" height="250" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FwnBveAG2ikUspFsQwM3GNE%2FPrototyping-av-skjematjenester%3Fnode-id%3D1746%253A6099" allowfullscreen></iframe>

<hr>


### ❖ Filopplasting

<hr>


#### ❖ Liste over vedlegg