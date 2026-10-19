# Individuell sprintloggbok - Agil utveckling
Aslihan Taskin

## Inledande sammanfattning

## Sprint 1 - Vecka 38, 14 September - 20 September
Satte upp trello tavlan samt skapande av automations- regler och listor som förbättrade och förtydligade arbetsflödet.
Som Scrum master satte jag upp sprintmål för denna vecka vilket var att driftsätta våra servrar på Render igen, uppdatera våra databaser samt att varje gruppmedlem skulle skapa ett upplägg så att varje mikrotjänst skulle kunna köras lokalt. Tanken var att varje medlem hade ansvar för sitt repo från i våras och skulle då få igång det lokalt och uppdatera sitt repo därefter.
Denna vecka satte jag igång min Render server igen, skapade en ny databas på Render samt skapade ett lokalt upplägg så att varje gruppmedlem skulle kunna köra auth-server lokalt. Jag satte även upp det lokala upplägget för email-service samt order-service då det inte blev gjort av respektive repo-ägare.

Som Scrum master satte jag sprintmål, påminde om möten, återkopplade med gruppmedlemmarna om vilken stadie dem befann sig i, vilka blockerare som fanns i deras väg samt såg till att vi körde muntlig poker planning. Jag uppdaterade även trello tavlan åt alla, d.v.s. alla kort osv.

## Sprint 2 - vecka 39, 21 September - 30 September
### Denna vecka gick åt att försöka få till det så att Ellinor och Erik fick igång sina tjänster lokalt då dem inte fick till det under föregående vecka. Jag gick igenom det stegvis med Ellinor då hon hade det väldigt svårt. Erik var mer självständig så hjälp behövdes inte på den fronten.

Denna vecka var Johan Scrum Master och jag hjälpte honom då att uppdatera vår backlog i trello. 
Denna vecka 
FE-01 Skapade repot för frontend tillsammans med Johan
FE-04 ordnade så att Ellinor också kunde köra det lokalt
FE-05 tillät jag frontend mot auth-service, CORS-config
FE-08 returnerade inloggningsdata som DTO
FE-09 Logga in från frontend
FE-10 Visa välkomstsida efter inloggning
FE-12 Skydda privata sidor

mini-blockerare: behövde uppdatera main så att vi fick react-router installerat, allokera tid för att göra setup åt Ellinor

## Sprint 3 - Vecka 40, 28 September - 4 Oktober
### beskriv arbetet
Denna vecka var Erik Scrum Master
FE-15 Grundläggande kundvagn
FE-14 Undersökte betallösning

## Sprint 4 - Vecka 41, 5 Oktober - 11 Oktober
###
Denna vecka var Ellinor Scrum Master dock så blev det så att jag och Johan planerade för veckan, satte sprintmål och gick igenom agila punkter under våra möten.

## Sprint 5 - Vecka 42, 12 Oktober - 18 Oktober
###
Denna vecka var jag Scrum Master
Denna vecka var lite spretig. 
Omstrukturerade koden för Cart funktionaliteten
Ornade cart layout så att det istället blir en dropdown från nav
FE-27 felsökte igenom order-service samt email-service då riktig mejl inte skickades. Löstes genom uppdatering av app-lösen samt små properties ändringar i spring-messenger. Tog hjälp av Johan för att ordna med spring-messenger då han är ägaren till det GitHub packaget.
Undersökte om betallösning för att kunna påbörja implemenation av Stripe Checkout

## Sprint 6 - Vecka 43, 19 Oktober - 25 Oktober
###
Denna vecka har jag hittills:
Fått upp repot för payment-service samt ett simpelt upplägg, bjudit in collaborators
