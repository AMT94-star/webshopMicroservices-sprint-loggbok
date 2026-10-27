# Individuell sprintloggbok - Agil utveckling
Aslihan Taskin

## Inledande sammanfattning

## Sprint 1 – Vecka 38, 14–20 september
### Vad jag arbetade med
- Strukturerade trello tavlan och skapade automatiseringar för ett tydligare arbetsflöde
- Planerade sprinten och satte upp sprintmål
- Uppdaterade auth service på Render och skapade en ny PostgreSQL databas
- Konfigurerade den lokala utvecklingsmiljön för auth service
- Konfigurerade lokala properties filer för email service och order service

### Eventuella problem och hur jag löste dem
De ansvariga för email service och order service hann inte konfigurera sina lokala miljöer enligt plan. Jag tog därför initiativ till att göra detta för att undvika att arbetet stannade upp.

### Samarbete och agilt arbete
Jag var Scrum Master under denna sprint och ansvarade för sprintmål, mötespåminnelser och uppföljning av gruppens arbete. Jag stämde regelbundet av uppgifternas status och eventuella blockerare samt såg till att vi genomförde muntlig planning poker för att uppskatta arbetsuppgifternas omfattning.

Jag tog även ansvar för att hålla trello tavlan uppdaterad med gruppens uppgifter och statusar när detta inte gjordes löpande.

## Sprint 2 – Vecka 39, 21–27 september
### Vad jag arbetade med
- FE-01: Skapade frontend repot tillsammans med Johan.
- FE-04: Hjälpte Ellinor att få igång frontend lokalt.
- FE-05: Konfigurerade CORS i auth service för att tillåta anrop från frontend.
- FE-08: Returnerade inloggningsdata genom en DTO.
- Hjälpte till med lokala utvecklingsmiljöer för email service och order service.

### Eventuella problem och hur jag löste dem
Ellinor hade fortfarande problem med att få igång sin tjänst lokalt, så jag gick igenom konfigurationen stegvis tillsammans med henne. Gruppen behövde även uppdatera main i frontend med React Router för att kunna fortsätta utvecklingen.

### Samarbete och agilt arbete
Johan var Scrum Master denna sprint, men jag fortsatte bidra till planeringen genom att hjälpa till att uppdatera vår backlogg med nya uppgifter. Jag tog även ansvar för att hålla trello tavlan uppdaterad med gruppens arbetsuppgifter och statusar.

En hel del av min tid gick åt till att hjälpa andra gruppmedlemmar med tekniska hinder, vilket gjorde att jag behövde anpassa mina egna prioriteringar efter gruppens behov.

## Sprint 3 - Vecka 40, 28 September - 4 Oktober
### beskriv arbetet
Denna vecka var Erik Scrum Master. Jag uppdaterade backloggen på trello med nya uppgifter samt uppdaterade allas uppgifter återigen.
FE-09 Logga in från frontend
FE-10 Visa välkomstsida efter inloggning
FE-12 Skydda privata sidor
FE-15 Grundläggande kundvagn
FE-14 Undersökte betallösning

## Sprint 4 - Vecka 41, 5 Oktober - 11 Oktober
###
Denna vecka var Ellinor Scrum Master dock så blev det så att jag och Johan planerade för veckan, satte sprintmål och gick igenom agila punkter under våra möten. Jag satte upp backlog, tilldelade uppgifterna med Johan och uppdaterade trello korten.
FE-22 Möjlighet att logga ut
FE-28 Sökfält med realtid filtrering för produkter på produktsidan
FE-29 404 sida vid icke existerande endpoints
FE-Extra La till registrering i frontend
FE-Extra CSS och Typescript för att skapa en ordentlig layout till hela hemsidan

## Sprint 5 - Vecka 42, 12 Oktober - 18 Oktober
###
Denna vecka var jag Scrum Master. Jag satte upp backlog samt tilldelning av uppgifterna.
Denna vecka var lite spretig. 
Omstrukturerade koden för Cart funktionaliteten
Ordnade cart layout så att det istället blir en dropdown från nav
La till notifikation för när man lägger till en vara i kundvagnen
La till så att användaren inte kan överskrida lagerstatus i sin order
La till mindre funktionalitet som gråar ut produkt och knapp för att lägga i varukorg om produkten inte finns i lager
FE-27 felsökte igenom order-service samt email-service då riktig mejl inte skickades. Löstes genom uppdatering av app-lösen samt små properties ändringar i spring-messenger. Tog hjälp av Johan för att ordna med spring-messenger då han är ägaren till det GitHub packaget.
Undersökte om betallösning för att kunna påbörja implemenation av Stripe Checkout

## Sprint 6 - Vecka 43, 19 Oktober - 25 Oktober
###
Denna vecka har jag hittills:
Fått upp repot för payment-service samt ett simpelt upplägg, bjudit in collaborators
