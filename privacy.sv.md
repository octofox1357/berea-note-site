---
layout: default
title: "Integritetspolicy för BereaNote"
lang: sv
---

# Integritetspolicy för BereaNote

> Den här översättningen tillhandahålls endast för att underlätta. Vid skillnader i innebörd gäller den [engelska versionen](privacy.en.html).

Gäller från: 1 december 2026

BereaNote är en anteckningsapp för personligt bibelstudium på Mac, iPad och iPhone. Den här sidan förklarar vad som händer med dina data när du använder appen.

## Sammanfattning

- BereaNote samlar inte in några data om dig.
- Det finns inget konto, ingen reklam, ingen analys och ingen kod från tredje part i appen.
- Det du skriver sparas på din enhet, och appen skickar det ingenstans. Om du aktiverar iCloud-synkronisering sparas det även i din egen privata iCloud-databas, som utvecklaren inte kan läsa.

## Vad appen sparar, och var

| Data | Var det sparas |
| --- | --- |
| Anteckningar, mappar, tidslinjer, egenskaper, inställningar | På din enhet, i appens egen lagring |
| Ljudinspelningar | På din enhet. iCloud-synkronisering laddar inte upp själva ljudet |
| Bibeln du importerar | Appen läser den EPUB-fil du väljer och bygger ett sökindex på din enhet. Den laddas aldrig upp |
| Säkerhetskopior | En ZIP-fil som skrivs till den plats du väljer. Vad som sedan händer med filen bestämmer du |

Appen själv laddar aldrig upp dina inspelningar eller din Bibel. Din enhets egna säkerhetskopior – iCloud-säkerhetskopiering, en datorsäkerhetskopia av en iPhone eller iPad, Time Machine på en Mac – innehåller appens data, inspelningar inräknade, precis som för alla appar. Dessa säkerhetskopior görs av systemet enligt dina inställningar, inte av BereaNote.

## iCloud-synkronisering

iCloud-synkronisering är valfri och avstängd tills du aktiverar den i Inställningar.

När den är aktiverad sparas följande i den privata databasen i ditt eget iCloud-konto, via Apples CloudKit, så att dina andra enheter som är inloggade med samma Apple-konto kan läsa dem: anteckningar, mappar, tidslinjelinjer och händelser, personer, egenskapsdefinitioner och posten för sidlåsets lösenord (en saltad hash, aldrig själva lösenordet).

Utvecklaren har ingen åtkomst till dessa data. Apple lagrar dem enligt Apples egen integritetspolicy.

Låsta sidor synkroniseras som alla andra anteckningar. Sidlåset döljer en sida i appen; det krypterar den inte.

iCloud-synkronisering erbjuds som en månadsprenumeration som förnyas automatiskt. Apple hanterar prenumerationen och betalningen; appen tar aldrig emot eller sparar betalningsuppgifter (kort, namn eller adress). Om en prenumeration upphör pausas bara synkroniseringen, och data på dina enheter finns kvar.

Om du stänger av synkroniseringen finns dina data kvar både på enheten och i iCloud, och kopian i iCloud ligger kvar där tills du raderar den. För att ta bort appens data från iCloud använder du **Inställningar → Riskzon → iCloud-data → Radera…** (detta stänger även av synkroniseringen på dina andra enheter; data på varje enhet behålls), eller tar bort dem i enhetens inställningar för iCloud-lagring.

## Mikrofon

Appen ber om åtkomst till mikrofonen första gången du startar en inspelning. Mikrofonen används bara för att spela in ljud som du kopplar till en anteckning, och bara medan du spelar in. På iPhone och iPad fortsätter en inspelning som du har startat när skärmen låses eller du byter till en annan app, tills du stoppar den. Appen laddar inte upp inspelningar.

## Sidlås

Ett lösenord för sidlås döljer innehållet i låsta sidor i appen. Det krypterar inte filerna på din enhet. Lösenordet sparas bara som en saltad hash.

## Vad utvecklaren tar emot

Ingenting från appen. Om du skriver till supportadressen tar utvecklaren emot det du skickar. Om du i enhetens inställningar har valt att dela diagnostik med apputvecklare kan Apple vidarebefordra anonyma kraschrapporter.

## Radera dina data

- Radera anteckningar i appen. Anteckningar i Papperskorgen tas bort permanent efter 30 dagar, eller direkt om du väljer det.
- Radera appens iCloud-data enligt beskrivningen ovan.
- På iPhone och iPad tas allt som appen har sparat på enheten bort när du raderar appen.
- På en Mac ligger appens datamapp kvar när du flyttar appen till papperskorgen. För att ta bort även den öppnar du **Inställningar → Info → Sparplats → Visa i Finder** innan du raderar appen och flyttar den mappen till papperskorgen (den ligger i `~/Library/Containers/com.chan.BereaNote`).
- Säkerhetskopior som du har skapat, och kopior som finns i enhetens egna säkerhetskopior, tas inte bort av något av ovanstående.

## Barn

BereaNote riktar sig inte till barn och samlar inte in personuppgifter från någon.

## Ändringar i denna policy

Om den här policyn ändras publiceras den nya versionen på den här sidan med ett nytt datum för ikraftträdande.

## Kontakt

Chan Jung — john1913@naver.com
