# WEBUTVIKLING2023

Kilder til bilder 

# HTML og CSS bilde kilder
Hav
Bildet er tatt av a href="https://pixabay.com/no/users/the1willy-10879846/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8208314">the1willy</a> fra <a href="https://pixabay.com/no//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8208314">Pixabay</a>

Fugel 
Bildet er tatt av <a href="https://pixabay.com/no/users/erik_karits-15012370/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8071472">Erik Karits</a> fra <a href="https://pixabay.com/no//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8071472">Pixabay</a>

Katt
Bildet er tatt av <a href="https://pixabay.com/no/users/alllessandro_-21426823/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8197577">Alessandro Alle</a> fra <a href="https://pixabay.com/no//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8197577">Pixabay</a>

Skilpadde
https://cdn.pixabay.com/photo/2023/07/04/10/30/turtle-8105993_960_720.jpg

Bildet er tatt av <a href="https://pixabay.com/no/users/derweg-7520060/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8105993">DerWeg</a> fra <a href="https://pixabay.com/no//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8105993">Pixabay</a>

Skjell
Bildet er tatt av <a href="https://pixabay.com/no/users/mylene2401-10328767/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8080937">Myléne</a> fra <a href="https://pixabay.com/no//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8080937">Pixabay</a>

# Hvorfor article ble brukt 
article-taggen brukes til nyhetsartikler fordi den gir mening i forhold til semantisk HTML-struktur. Her er hvorfor article er en bedre passform enn section:

1. Semantisk korrekthet: article-elementet er beregnet på selvstendige, uavhengige innholdsbiter som kan gjenbrukes på tvers av forskjellige nettsteder eller som kan stå alene. Nyhetsartikler er typiske eksempler på slike uavhengige innholdsbiter. Hver nyhetsartikkel kan forstås som en egen enhet, og det gir mening å bruke article for å markere dem som slike.

2. Bedre for tilgjengelighet: Bruken av riktig semantisk HTML er viktig for tilgjengelighet og søkemotoroptimalisering. Skjermlesere og søkemotorer kan gjenkjenne article-elementer som selvstendige enheter, noe som gir bedre indeksering og forståelse av innholdet.

3. Klart definert struktur: article gir en klar og strukturert måte å gruppere relaterte elementer som overskrifter, brødtekst og lenker på. Dette hjelper både utviklere og maskiner med å forstå innholdet bedre.

4. Enkel CSS-styling: Ved å bruke article-elementer kan du enklere style hver nyhetsartikkel individuelt ved hjelp av CSS, fordi de er klart definerte og identifiserbare deler av innholdet.

section-elementet, derimot, er ment for å gruppere sammen beslektet innhold, men hver seksjon skal ikke nødvendigvis være en selvstendig enhet som kan stå alene. Det er mer egnet for å gruppere innhold i overordnede seksjoner på en side, som hovedmeny, sidekolonner eller lignende.

Så, for å oppsummere, bruk av article i denne sammenhengen gir en mer korrekt og meningsfull semantisk struktur for nyhetsartiklene dine sammenlignet med section.

# Hvorfor vi skal unngå å bruke div til å bygge nettsidestrykturen vår

I koden vår har vi brukt en div som vi har gitt id="pynt", vi bruker den kun til pynkt og ikke til å gi struktur til noe annet enn design. Til innhold og nettsidestruktur bruker vi de semantiske taggene. 

1. Mangel på Semantikk: div-elementet gir ingen semantisk betydning til innholdet det inneholder. Det er i utgangspunktet en generisk beholder. Når mer semantisk meningsfulle HTML-elementer er tilgjengelige (for eksempel header, article, nav), er det bedre å bruke dem for å forbedre tilgjengeligheten og søkemotoroptimaliseringen (SEO) av nettsiden din.

2. Tilgjengelighet: Bruk av semantisk meningsfulle HTML-elementer gjør det lettere for skjermlesere og annen hjelpeteknologi å tolke og presentere innholdet for brukere med nedsatt funksjonsevne. Overbruk av div-elementer uten riktig semantisk betydning kan gjøre nettsiden din mindre tilgjengelig.

3. SEO (Søkemotoroptimalisering): Søkemotorer som Google bruker semantisk HTML for å forstå innholdet og strukturen på nettsider. Bruk av passende semantiske elementer kan forbedre SEO ved å gjøre det enklere for søkemotorer å indeksere og rangere innholdet ditt.

4. Vedlikeholdbarhet: Overbruk av div-elementer kan føre til kode som er vanskeligere å vedlikeholde og forstå, spesielt i større prosjekter. Semantiske elementer bidrar til å gjøre HTML-koden din mer selvforklarende og enklere for andre utviklere å arbeide med.

5. HTML5 og Semantiske Elementer: Med innføringen av HTML5 er det mange nye semantiske elementer tilgjengelige, som header, nav, article, section, og mer. Disse elementene gir bedre måter å strukturere innholdet ditt basert på dets betydning.

6. Rotete Kode: Overdreven bruk av div-elementer kan gjøre HTML-koden din rotete og vanskeligere å lese og arbeide med. Semantiske elementer gir en mer konsis og meningsfull måte å strukturere innholdet på.

7. Fremtidssikring: HTML utvikler seg kontinuerlig. Med innføringen av nye semantiske elementer er det en god praksis å bruke dem, da de kan gi bedre støtte for nye teknologier og funksjoner.