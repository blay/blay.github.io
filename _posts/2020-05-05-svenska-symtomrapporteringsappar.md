---
title: Svenska symtomrapporteringsappar
excerpt: 'Kommentar till Svenska försök till appar för rapportering av symtom'
tags: swedish 
header:
  image: /assets/images/fever_narrow.jpg
toc: true
toc_sticky: true
---

# Försök i Sverige

Hittills har två försök gjorts att lansera appar för frivillig symtomrapportering av Covid i Sverige men syfte att undersöka hur utbredd smittan är bland de som bara stannar hemma med symtom och inte kommer i kontakt med sjukvården.

Jag kan hinta om att det också är på gång med en Svensk pilot för ett projekt som baseras på en internationell lösning på öppen källkod som gör att det går att granska och förbättra den innan den används skarpt.

## MSB

MSB tog på uppdrag från Folkhälsomyndigheten fram någon slags lösning som jag tror var webb-baserad och där tanken var att [skicka ut ett mass-sms och köra reklamkampanjer](https://www.svt.se/nyheter/inrikes/msb-planerade-superkampanj-med-mass-sms-bromsades-av-andra-myndigheter) för att få folk att registrera sina symtom. Tydligen skulle man också svara på frågor om var man fått information om pandemin så det verkar ha rört sig mer om en heltäckande enkätundersökning och kanske mer som ett sätt att få en ögonblicksbild av läget än något som skulle användas dagligen för att följa sjukdomsförlopp. Men jag har inte sett vad det var så här spekulerar jag bara efter den information som finns offentligt. Inlogg skulle ske med bank-id.

I SVTs artikel nämns att FHM vill köra en pilotstudie för att testa upplägget men mer information om så finns inte. Överlag verkar det finnas en motvilja mot att lufta eventuella lösningar offentligt vilket jag tror bara spär på gissningslekar och får ansvariga att få kalla fötter inför eventuell lansering. Jämför återigen med hur [DP-3T lanseras öppet och granskas innan tillämpning](/2020-04-30-contact-tracing-apps.html#dp3t-som-den-decentraliserade-anonyma-och-granskade-lösningen).

## Lunds Universitet

Nyligen lanserades en app av forskare vid Lunds Universitet som är en svensk översättning av en app utvecklad av det Brittiska företaget [Zoe Global ltd.](https://joinzoe.com/) och som tidigare använts i UK. 

Lanseringen fick en [hel](https://piratpartiet.se/nyheter/ny-svensk-corona-app/) [del](https://www.facebook.com/groups/sakerhetsbubblan/permalink/981651738938948/) [kritik](https://www.facebook.com/dekaminski/posts/10163448399085142) för hur de behandlar data baserat på vad de beskriver i [sitt integritetsmedelande](https://www.covid19app.lu.se/integritetsmeddelande-zoe-ltd). Oavsett om de behandlar datan bra eller ej i praktiken ringer det varningsklockor med Amazon, Google, massa tredjepartstjänster, brittiska företag, forskare i USA och controlleransvar i Storbritannien. I den här appen identifierar man sig bara med email och inte med BankID som jag förstått var tanken i MSB:s lösning, så man undviker en del identitetsproblem men öppnar samtidigt upp för missbruk genom att massregistrering och rapportering av användare.

Ett annat problem är att man gör två saker samtidigt. Det huvudsakliga syftet (sägs det) är att göra kartläggning av smittspridning genom självrapportering av symtom. Det enda som behövs för det är att användare ger en grov platsidentifiering, ex postnummer och sedan beskriver symtom. Symtomen är generella för alla drabbade och är därför inte personligt identifierbara. Men sedan verkar det också som att man vill få in forskningsdata och som många som gör forskning vet är det frestande att vilja få in så mycket data som möjligt genom enkätundersökningar för att täcka upp alla potentiella frågeställningar man kan vilja ställa till datan. Därför ska man i appen uppge längd och vikt, om man har käpp, om man behöver assistans, om man har underliggande sjukdomar och om man tar vissa mediciner. Detta behövs inte för att kartlägga symtomspridning, men kan vara användbart för att förstå vilka det är som är drabbade av covid. Problemet är att dessa data och framförallt kombinationen av dem är identifierbara, även om direkt data som plats och email tas bort. Det finns kanske bara en person i hela Sverige som är 198 lång, väger 82 kg och har käpp. Nu har den personen också avslöjat i en enkätundersökning att denne har cancer.

Som jag skrev i [tidigare inlägg](2020-04-30-contact-tracing-apps.html) så tror jag på att processen för hur digitala lösningar tas fram och diskuteras i den här situationen är oerhört viktig. Publicera white papers som beskriver idén, bjud in till och välkomna extern granskning och låt frågeställningar och kritik komma fram när projektet är på idé- och prototypstadiet. Anpassa efter rimlig kritik och bemötandet och lansera sedan en lösning som redan byggt upp förtroende genom den här processen. Var glad om det visar sig vara en dålig idé i tidigt stadium snarare än vid lansering efter enbart interna diskussioner. Det räcker inte att hänvisa till etikprövningsnämnder och interna, slutna processer.

Fail early -- before harm is done -- and often.
