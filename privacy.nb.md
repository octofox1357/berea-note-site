---
layout: default
title: "Personvernerklæring for BereaNote"
lang: nb
---

# Personvernerklæring for BereaNote

> Denne oversettelsen er bare ment som en hjelp. Ved avvik gjelder den [engelske versjonen](privacy.en.html).

Gjelder fra: 1. desember 2026

BereaNote er en notatapp for personlig bibelstudium på Mac, iPad og iPhone. Denne siden forklarer hva som skjer med dataene dine når du bruker den.

## Sammendrag

- BereaNote samler ikke inn noen data om deg.
- Det finnes ingen konto, ingen reklame, ingen analyse og ingen tredjepartskode i appen.
- Det du skriver, lagres på enheten din, og appen sender det ingen steder. Hvis du slår på iCloud-synkronisering, lagres det også i din egen private iCloud-database, som utvikleren ikke kan lese.

## Hva appen lagrer, og hvor

| Data | Hvor de oppbevares |
| --- | --- |
| Notater, mapper, tidslinjer, egenskaper, innstillinger | På enheten din, i appens egen lagring |
| Lydopptak | På enheten din. iCloud-synkronisering laster ikke opp selve lyden |
| Bibelen du importerer | Appen leser EPUB-filen du velger, og bygger en søkeindeks på enheten din. Den lastes aldri opp |
| Sikkerhetskopier | En ZIP-fil som skrives til stedet du velger. Hva som skjer med filen etterpå, bestemmer du selv |

Appen selv laster aldri opp opptakene dine eller Bibelen din. Enhetens egne sikkerhetskopier – iCloud-sikkerhetskopi, en sikkerhetskopi av en iPhone eller iPad på en datamaskin, Time Machine på en Mac – inkluderer appens data, også opptakene, slik de gjør for alle apper. Disse sikkerhetskopiene lages av systemet etter dine innstillinger, ikke av BereaNote.

## iCloud-synkronisering

iCloud-synkronisering er valgfritt og er av til du slår det på i Innstillinger.

Når det er på, lagres disse elementene i den private databasen i din egen iCloud-konto, gjennom Apples CloudKit, slik at de andre enhetene dine som er logget på den samme Apple-kontoen, kan lese dem: notater, mapper, tidslinjelinjer og hendelser, personer, egenskapsdefinisjoner og oppføringen for sidelåsens passord (en saltet hash, aldri selve passordet).

Utvikleren har ingen tilgang til disse dataene. Apple lagrer dem under Apples egen personvernerklæring.

Låste sider synkroniseres som alle andre notater. Sidelåsen skjuler en side inne i appen; den krypterer den ikke.

iCloud-synkronisering tilbys som et automatisk fornyet månedsabonnement. Apple håndterer abonnementet og betalingen; appen mottar eller lagrer aldri betalingsopplysninger (kort, navn eller adresse). Hvis et abonnement avsluttes, settes bare synkroniseringen på pause, og dataene på enhetene dine blir værende.

Når du slår av synkronisering, blir dataene dine liggende både på enheten og i iCloud, og kopien i iCloud blir liggende der til du sletter den. For å fjerne appens data fra iCloud bruker du **Innstillinger → Faresone → iCloud-data → Slett…** (dette slår også av synkronisering på de andre enhetene dine; dataene på hver enhet beholdes), eller du fjerner dem i iCloud-lagringsinnstillingene på enheten.

## Mikrofon

Appen ber om tilgang til mikrofonen første gang du starter et opptak. Mikrofonen brukes bare til å ta opp lyd som du legger til et notat, og bare mens du tar opp. På iPhone og iPad fortsetter et opptak du har startet når skjermen låses eller du bytter til en annen app, helt til du stopper det. Appen laster ikke opp opptak.

## Sidelås

Et passord for sidelåsen skjuler innholdet på låste sider inne i appen. Det krypterer ikke filene på enheten din. Passordet lagres bare som en saltet hash.

## Hva utvikleren mottar

Ingenting fra appen. Hvis du skriver til støtteadressen, mottar utvikleren det du sender. Hvis du i enhetsinnstillingene har valgt å dele diagnostikk med apputviklere, kan Apple videreformidle anonyme krasjrapporter.

## Slette dataene dine

- Slett notater i appen. Notater i papirkurven fjernes for godt etter 30 dager, eller med en gang hvis du velger det.
- Slett appens iCloud-data som beskrevet ovenfor.
- På iPhone og iPad fjerner sletting av appen alt den har lagret på den enheten.
- På en Mac blir appens datamappe liggende igjen når du flytter appen til papirkurven. For å fjerne den også åpner du **Innstillinger → Info → Lagringssted → Vis i Finder** før du sletter appen, og flytter den mappen til papirkurven (den ligger i `~/Library/Containers/com.chan.BereaNote`).
- Sikkerhetskopifiler du har laget, og kopier som enhetens egne sikkerhetskopier inneholder, fjernes ikke av noe av det ovenstående.

## Barn

BereaNote er ikke rettet mot barn og samler ikke inn personopplysninger fra noen.

## Endringer i denne erklæringen

Hvis denne erklæringen endres, publiseres den nye versjonen på denne siden med en ny ikrafttredelsesdato.

## Kontakt

Chan Jung — john1913@naver.com
