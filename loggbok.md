# Individuell sprintloggbok - Agil utveckling
Aslihan Taskin

### Notis
FE-46 Dokumentera backend med Javadoc: Detta har vi gjort kontinuerligt under projektets gång

## Sprint 1 – Vecka 38, 14 September – 18 September
### Vad jag arbetade med
- Strukturerade trello tavlan och skapade automatiseringar för ett tydligare arbetsflöde
- Planerade sprinten och satte upp sprintmål
- Uppdaterade auth service på Render och skapade en ny PostgreSQL databas
- Konfigurerade den lokala utvecklingsmiljön för auth service
- Konfigurerade lokala properties filer för email service och order service

### Eventuella problem och hur jag löste dem
De ansvariga för email service och order service hann inte konfigurera sina lokala miljöer enligt plan. Jag tog därför initiativ till att göra detta för att undvika att arbetet stannade upp.

### Samarbete och agilt arbete
Jag var scrum master under denna sprint och ansvarade för sprintmål, mötespåminnelser och uppföljning av gruppens arbete. Jag stämde regelbundet av uppgifternas status och eventuella blockerare samt såg till att vi genomförde muntlig planning poker för att uppskatta arbetsuppgifternas omfattning.

Jag tog även ansvar för att hålla trello tavlan uppdaterad med gruppens uppgifter och statusar när detta inte gjordes löpande.

## Sprint 2 – Vecka 39, 21 September – 25 September
### Vad jag arbetade med
- FE-04: Hjälpte Ellinor att få igång frontend lokalt
- FE-05: Konfigurerade CORS i auth service för att tillåta anrop från frontend
- FE-08: Returnerade inloggningsdata genom en DTO
- Hjälpte till med lokala utvecklingsmiljöer för email service och order service

### Eventuella problem och hur jag löste dem
Ellinor hade fortfarande problem med att få igång sin tjänst lokalt, så jag gick igenom konfigurationen stegvis tillsammans med henne. Gruppen behövde även uppdatera main i frontend med React Router för att kunna fortsätta utvecklingen och detta löste jag genom en simpel react router install i en PR.

### Samarbete och agilt arbete
Johan var scrum master denna sprint, men jag fortsatte bidra till planeringen genom att hjälpa till att uppdatera vår backlogg med nya uppgifter. Jag tog även ansvar för att hålla trello tavlan uppdaterad med gruppens arbetsuppgifter och statusar. Johan och jag satte även poäng för veckans sprintmål.

En hel del av min tid gick åt till att hjälpa andra gruppmedlemmar med tekniska hinder vilket gjorde att jag behövde anpassa mina egna prioriteringar efter gruppens behov.

## Sprint 3 - Vecka 40, 28 September - 2 Oktober
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

## Sprint 4 - Vecka 41, 5 Oktober - 9 Oktober
### Vad jag arbetade med
- FE-22: Möjlighet att logga ut
- FE-28: Sökfält med realtid filtrering för produkter på produktsidan
- FE-29: 404 sida vid icke existerande endpoints
- FE-Extra: Implementerade registrering i frontend på eget initiativ
- FE-Extra: Implementerade CSS och Typescript för att förbättra layout och utseende till hemsidan på eget initiativ

### Eventuella problem och hur jag löste dem
Ellinor hade svårt att komma igång med sitt ansvar som scrum master, vilket påverkade sprintplaneringen. Jag och Johan tog därför initiativ till att genomföra planeringen, sätta sprintmål och fördela arbetsuppgifterna så att arbetet kunde fortsätta.

### Samarbete och agilt arbete
Ellinor var formellt scrum master denna vecka men johan och jag ansvarade i praktiken för stora delar av planeringen och uppföljning. Vi gick igenom agila punkterna under mötena och fördelade arbetsuppgifterna. Jag fortsatte även att komplettera backlog med nya uppgifter och uppdatera alla trello kort.

## Sprint 5 - Vecka 42, 12 Oktober - 16 Oktober
### Vad jag arbetade med
- FE-Extra: Omstrukturerade koden för kundvagnens funktionalitet
- FE-Extra: Ändrade kundvagnens layout till en dropdown i navigeringsmenyn
- FE-Extra: Lade till notifikationer när produkter läggs till i kundvagnen
- FE-Extra: Implementerade lagerkontroll så att användaren inte kan beställa fler produkter än vad som finns i lager
- FE-Extra: Lade till visuell återkoppling genom att gråa ut produkter och köpknappar när varor är slut i lager
- FE-Extra: Implementerade responsiv design
- FE-27: Felsökte order service och email service för att ta reda på varför mejlutskick inte fungerade
- Undersökte och dokumenterade betallösningar inför en eventuell prototyp med Stripe Checkout

### Eventuella problem och hur jag löste dem
FE-27: Orderbekräftelser skickades inte via mejl. Jag löste problemet genom att uppdatera applösenordet och justera properties konfigurationen i spring messenger. Jag tog hjälp av Johan när det visade sig att spring messenger behövde korrigeras eftersom han ansvarade för github paketet. Vi arbetade därefter tillsammans för att lösa problemet.

### Samarbete och agilt arbete
Jag var scrum master under sprinten och ansvarade för att planera backloggen och fördela arbetsuppgifterna. Under sprintplaneringen genomförde vi poker planning för att uppskatta uppgifternas omfattning. Jag följde även upp arbetet med gruppmedlemmarna under veckans gång och samarbetade med Johan vid felsökningen av spring messenger.

## Sprint 6 - Vecka 43, 19 Oktober - 23 Oktober
### Vad jag arbetade med
- FE-31: Skapade repository för payment service med en grundläggande projektstruktur och bjöd in gruppmedlemmarna som collaborators
- FE-33: Arbetade tillsammans med gruppen för att åtgärda problem med driftsättningen av gateway på Render
- FE-34: Implementerade hantering av JWT via httponly cookie i gateway vid inloggning och skyddade anrop. Gateway läser JWT från cookien och vidarebefordrar den till mikrotjänsterna. Testade funktionaliteten. Ellinor ansvarade för utloggningsmetoderna för FE-34

### Eventuella problem och hur jag löste dem
Vi hade problem med driftsättningen av gateway vilket tog en stor del av sprinten. Vi felsökte tillsammans, testade olika lösningar och omvärderade kontinuerligt vårt tillvägagångssätt för att komma vidare.

### Samarbete och agilt arbete
Erik var scrum master under denna sprint. Vi arbetade mycket tillsammans eftersom problemen med gateway påverkade hela gruppen. Genom kontinuerliga avstämningar och gemensam felsökning kunde vi utvärdera våra lösningar och anpassa arbetet efter resultaten.

## Sprint 7 - Vecka 44, 26 Oktober - 30 Oktober
### Vad jag arbetade med
- FE-43: Uppdaterade README.md för auth-service med dokumentation om projektet, konfiguration och API-endpoints
- FE-36: Uppdaterade JwtDecoder och securityfilterchain i auth service, implementerade /auth/me i controllern och skapade tillhörande DTO. Testade funktionaliteten i swagger
- FE-38: integrationstestning, Vitest, React Testing Library och MSW

Under denna sprint låg mitt fokus framför allt på att färdigställa och förbättra befintlig funktionalitet i auth service, uppdatera dokumentation i auth service och undersöka möjligheterna till automatiserad testning av frontend.
Arbetet med JWT och /auth/me gav mig en djupare förståelse för autentisering och hur användarens session kan hanteras mellan frontend, API gateway och auth service. Jag fick också en bättre inblick i hur frontendtester kan struktureras och hur externa API anrop kan mockas för att testa komponenter mer isolerat.

### Eventuella problem och hur jag löste dem
Vi stötte på problem med att få mockningen av API anrop att fungera korrekt i våra tester. Felet verkade vara kopplat till konfigurationen av testmiljön, framför allt setup filen. Vi undersökte därför hur testverktygen samverkar och hur konfigurationen behöver se ut för att mockningen ska fungera som tänkt.

### Samarbete och agilt arbete
Vi arbetade gemensamt med FE-38 genom att först undersöka testverktygen individuellt och sedan samlas i ett teams möte för att gå igenom våra upptäckter och försöka förstå hur testflödet fungerar med Vitest, React Testing Library och MSW. Genom att felsöka och diskutera tillsammans kunde vi dela kunskap och få en bättre gemensam förståelse för hur testerna kan struktureras och hur de olika biblioteken samverkar.

## Sprint 8 - Vecka 45, Redovisningsvecka
Avstämningen med gruppen över vår presentation samt arbete tillsammans för att skapa vår powerpoint

