---
layout: default
title: "Privatlivspolitik for BereaNote"
lang: da
---

# Privatlivspolitik for BereaNote

> Denne oversættelse er kun til din bekvemmelighed. Hvis den afviger i betydning, gælder den [engelske version](privacy.en.html).

Gælder fra: 1. december 2026

BereaNote er en noteapp til personligt bibelstudium på Mac, iPad og iPhone. Denne side forklarer, hvad der sker med dine data, når du bruger den.

## Sammenfatning

- BereaNote indsamler ingen data om dig.
- Der er ingen konto, ingen reklamer, ingen analyse og ingen kode fra tredjeparter i appen.
- Det, du skriver, gemmes på din enhed, og appen sender det ingen steder hen. Hvis du slår iCloud-synkronisering til, gemmes det også i din egen private iCloud-database, som udvikleren ikke kan læse.

## Hvad appen gemmer, og hvor

| Data | Hvor de opbevares |
| --- | --- |
| Noter, mapper, tidslinjer, egenskaber, indstillinger | På din enhed, i appens eget lager |
| Lydoptagelser | På din enhed. iCloud-synkronisering uploader ikke selve lyden |
| Den Bibel, du importerer | Appen læser den EPUB-fil, du vælger, og opbygger et søgeindeks på din enhed. Den uploades aldrig |
| Sikkerhedskopier | En ZIP-fil, der skrives til det sted, du vælger. Hvad der derefter sker med filen, er op til dig |

Appen selv uploader aldrig dine optagelser eller din Bibel. Din enheds egne sikkerhedskopier — iCloud-sikkerhedskopi, en computersikkerhedskopi af en iPhone eller iPad, Time Machine på en Mac — omfatter appens data, også optagelserne, som de gør for enhver app. Disse sikkerhedskopier laves af systemet efter dine indstillinger, ikke af BereaNote.

## iCloud-synkronisering

iCloud-synkronisering er valgfri og slået fra, indtil du slår den til i Indstillinger.

Når den er slået til, gemmes disse elementer i den private database på din egen iCloud-konto via Apples CloudKit, så dine andre enheder, der er logget ind med den samme Apple-konto, kan læse dem: noter, mapper, tidslinjelinjer og begivenheder, personer, definitioner af egenskaber og posten med adgangskoden til sidelås (en saltet hash, aldrig selve adgangskoden).

Udvikleren har ikke adgang til disse data. Apple opbevarer dem under Apples egen privatlivspolitik.

Låste sider synkroniseres som enhver anden note. Sidelåsen skjuler en side inde i appen; den krypterer den ikke.

iCloud-synkronisering tilbydes som et automatisk fornyet månedsabonnement. Apple håndterer abonnementet og betalingen; appen modtager eller gemmer aldrig betalingsoplysninger (kort, navn eller adresse). Hvis et abonnement ophører, sættes kun synkroniseringen på pause, og dataene på dine enheder bliver.

Hvis du slår synkronisering fra, bliver dine data både på enheden og i iCloud, og kopien i iCloud bliver der, indtil du sletter den. For at fjerne appens data fra iCloud skal du bruge **Indstillinger → Farezone → iCloud-data → Slet…** (det slår også synkronisering fra på dine andre enheder; dataene på hver enhed bevares) eller fjerne dem i din enheds indstillinger for iCloud-lagerplads.

## Mikrofon

Appen beder om adgang til mikrofonen, første gang du starter en optagelse. Mikrofonen bruges kun til at optage lyd, som du knytter til en note, og kun mens du optager. På iPhone og iPad fortsætter en optagelse, du har startet, når skærmen låses, eller når du skifter til en anden app, indtil du stopper den. Appen uploader ikke optagelser.

## Sidelås

En adgangskode til sidelås skjuler indholdet af låste sider inde i appen. Den krypterer ikke filerne på din enhed. Adgangskoden gemmes kun som en saltet hash.

## Hvad udvikleren modtager

Intet fra appen. Hvis du skriver til supportadressen, modtager udvikleren det, du sender. Hvis du i din enheds indstillinger har valgt at dele diagnosticering med appudviklere, kan Apple videregive anonyme nedbrudsrapporter.

## Sletning af dine data

- Slet noter i appen. Noter i papirkurven fjernes endeligt efter 30 dage eller med det samme, hvis du vælger det.
- Slet appens iCloud-data som beskrevet ovenfor.
- På iPhone og iPad fjerner sletning af appen alt, hvad den har gemt på den enhed.
- På en Mac bliver appens datamappe liggende, når du flytter appen til papirkurven. For også at fjerne den skal du åbne **Indstillinger → Info → Gemmested → Vis i Finder**, før du sletter appen, og flytte den mappe til papirkurven (den ligger i `~/Library/Containers/com.chan.BereaNote`).
- Sikkerhedskopifiler, du selv har oprettet, og kopier i din enheds egne sikkerhedskopier fjernes ikke af noget af ovenstående.

## Børn

BereaNote er ikke rettet mod børn og indsamler ingen personoplysninger fra nogen.

## Ændringer af denne politik

Hvis denne politik ændres, offentliggøres den nye version på denne side med en ny ikrafttrædelsesdato.

## Kontakt

Chan Jung — john1913@naver.com
