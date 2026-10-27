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
- FE-01: Skapade frontend repot tillsammans med Johan
- FE-04: Hjälpte Ellinor att få igång frontend lokalt
- FE-05: Konfigurerade CORS i auth service för att tillåta anrop från frontend
- FE-08: Returnerade inloggningsdata genom en DTO
- Hjälpte till med lokala utvecklingsmiljöer för email service och order service

### Eventuella problem och hur jag löste dem
Ellinor hade fortfarande problem med att få igång sin tjänst lokalt, så jag gick igenom konfigurationen stegvis tillsammans med henne. Gruppen behövde även uppdatera main i frontend med React Router för att kunna fortsätta utvecklingen och detta löste jag genom en simpel react router install i en PR.

### Samarbete och agilt arbete
Johan var Scrum Master denna sprint, men jag fortsatte bidra till planeringen genom att hjälpa till att uppdatera vår backlogg med nya uppgifter. Jag tog även ansvar för att hålla trello tavlan uppdaterad med gruppens arbetsuppgifter och statusar.

En hel del av min tid gick åt till att hjälpa andra gruppmedlemmar med tekniska hinder, vilket gjorde att jag behövde anpassa mina egna prioriteringar efter gruppens behov.

## Sprint 3 - Vecka 40, 28 September - 4 Oktober
### Vad jag arbetade med
- FE-09: Logga in från frontend
- FE-10: Visa välkomstsida efter inloggning
- FE-12: Skydda privata sidor
- FE-15: Grundläggande kundvagn
- FE-14: Undersökte betallösning

### Eventuella problem och hur jag löste dem
Tidsplanen blev tajt för Erik eftersom han ansvarade för både FE-15 och FE-16. Jag tog därför initiativ till att ta över och implementera FE-15 för att avlasta honom och minska risken att uppgifterna inte blev färdiga i tid.

### Samarbete och agilt arbete
Erik var scrum master under denna sprint. Jag fortsatte även denna vecka med att komplettera backloggen i trello med nya uppgifter och fortsatte att hålla gruppmedlemmarnas uppgifter och statusar uppdaterade.

## Sprint 4 - Vecka 41, 5 Oktober - 11 Oktober
### Vad jag arbetade med
- FE-22: Möjlighet att logga ut
- FE-28: Sökfält med realtid filtrering för produkter på produktsidan
- FE-29: 404 sida vid icke existerande endpoints
- FE-Extra: Implementerade registrering i frontend på eget initiativ
- FE-Extra: Implementerade CSS och Typescript för att förbättra layout och utseende till hemsidan på eget initiativ

### Eventuella problem och hur jag löste dem
Ellinor hade svårt att komma igång med sitt ansvar som scrum master, vilket påverkade sprintplaneringen. Jag och Johan tog därför initiativ till att genomföra planeringen, sätta sprintmål och fördela arbetsuppgifterna så att arbetet kunde fortsätta.

### Samarbete och agilt arbete
Ellinor var formellt scrum master under men johan och jag ansvarade i praktiken för stora delar av planeringen och uppföljning. Vi gick igenom agila punkterna under mötena och fördelade arbetsuppgifterna. Jag fortsatte även att komplettera backlog med nya uppgifter och uppdatera alla trello kort.

## Sprint 5 - Vecka 42, 12 Oktober - 18 Oktober
### Vad jag arbetade med
- FE-Extra: Omstrukturerade koden för kundvagnens funktionalitet
- FE-Extra: Ändrade kundvagnens layout till en dropdown i navigeringsmenyn
- FE-Extra: Lade till notifikationer när produkter läggs till i kundvagnen
- FE-Extra: Implementerade lagerkontroll så att användaren inte kan beställa fler produkter än vad som finns i lager
- FE-Extra: Lade till visuell återkoppling genom att gråa ut produkter och köpknappar när varor är slut i lager
- FE-27: Felsökte order-service och email-service för att få mejlutskick att fungera.
- Undersökte och dokumenterade betallösningar inför en eventuell prototyp med Stripe Checkout

### Eventuella problem och hur jag löste dem
FE-27: Orderbekräftelser skickades inte via mejl. Jag löste problemet genom att uppdatera applösenordet och justera properties-konfigurationen i Spring Messenger. Jag tog hjälp av Johan med Spring Messenger eftersom han ansvarade för GitHub-paketet.

### Samarbete och agilt arbete
Jag var Scrum Master under sprinten och ansvarade för att planera backloggen och fördela arbetsuppgifterna. Jag samarbetade även med Johan vid felsökningen av Spring Messenger.

## Sprint 6 - Vecka 43, 19 Oktober - 25 Oktober
### Erik
Denna vecka har jag hittills:
FE-31 Fått upp repot för payment-service samt ett simpelt upplägg, bjudit in collaborators
Vi hade problem med driftsättning av gateway, veckan gick åt det
FE-34 httponly cookie för backend gateway, testning för att bekräfta funktionalitet
Sprint review presenterades av mig och johan, erik var ej på plats.

Sprint 7 - Vecka 44
uppdaterat readme.md för auth service repot
uppdaterat auth service samt testat i swagger för bekräftad funktionalitet - FE-36

