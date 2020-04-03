# regc19

An idea for a simple app for people to register Covid-19 symptoms in the absence of proper medical tests

# Description (Swedish)

En sajt där vem som helst kan gå in och registrera:

 * Jag är testad positiv med Corona och är sjuk.
 * Jag har testats positiv med Corona men mår bra nu.
 * Jag är väldigt säker på att jag har Corona. Bedömer att jag är på dag X
 * Jag är hyfsat säker på att jag har Corona. Bedömer att jag är på dag X
 * Jag har inte varit sjuk sedan 1 januari eller 1 februari eller 1 mars eller 1 april. Typ.
 * Sitt postnummer.

Man registrerar inget mer och det krävs inget registreringsförfarande eller inloggning.

Det som matas in hamnar i en backend-databas som har ett öppet publikt API som vem som helst kan anropa. Då kan vem som helst ladda hem data och göra kartor och grafer för att visualisera data och ta fram siffror. Får man bara in grunddatat kan man göra massor sen.

Ett steg bättre är att appen också har en "Corona self-assesment test" **där man svarar på typ 5-10 frågor om ens symptom som sedan resulterar i en klassning, typ det är 90%, 60%, 30% eller liten chans att du har eller har haft Corona.**

Då skulle man snabbt kunna få en rimlig uppskattning av antalet smittade och var de befinner sig. Självklart risk för brus och fel i rapporteringen, men i brist på riktiga tester skulle man - om många reggade sin "Coronahälsa" - kunna få en hyfsad bild på spridningen. Åtminstone bättre än man har nu! Man ska givetvis kunna gå in och fylla i igen en dag senare. Alla registreringar ska tidsstämplas.

Det som behövs är:

 * En frontend för registreringen. Troligen bäst med en webbapp. Lägg på en CAPTCHA så slipper man skript- och botsabotörer.
 * Ett backend API där man kan spara registreringen.
 * Ett backend API där man kan hämta ut data.

Några key success faktorer är:

 * Enkelt som tusan att registera!
 * Minimera integritetsproblematiken!
 * Få tag på någon medicinskt kompetent som kan säga om detta skulle ge något och som kan vara med och utforma ett bra "Corona self-assesment test" för detta ändamål.
