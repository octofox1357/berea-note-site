---
layout: default
title: "BereaNote – pravila privatnosti"
lang: hr
---

# BereaNote – pravila privatnosti

> Ovaj prijevod služi samo radi lakšeg snalaženja. U slučaju razlika mjerodavna je [engleska verzija](privacy.en.html).

Datum stupanja na snagu: 1. prosinca 2026.

BereaNote je aplikacija za bilješke za osobno proučavanje Biblije na Macu, iPadu i iPhoneu. Ova stranica objašnjava što se događa s vašim podacima kada je koristite.

## Sažetak

- BereaNote ne prikuplja nikakve podatke o vama.
- U aplikaciji nema računa, oglasa, analitike ni koda trećih strana.
- Ono što napišete sprema se na vašem uređaju i aplikacija to nikamo ne šalje. Ako uključite iCloud sinkronizaciju, to se sprema i u vašu vlastitu privatnu iCloud bazu podataka, koju razvojni programer ne može čitati.

## Što aplikacija sprema i gdje

| Podaci | Gdje se čuvaju |
| --- | --- |
| Bilješke, mape, vremenske crte, svojstva, postavke | Na vašem uređaju, u vlastitoj pohrani aplikacije |
| Audiosnimke | Na vašem uređaju. iCloud sinkronizacija ne prenosi sam zvuk |
| Biblija koju uvezete | Aplikacija čita EPUB datoteku koju odaberete i na vašem uređaju izrađuje indeks za pretraživanje. Nikada se ne prenosi |
| Sigurnosne kopije | ZIP datoteka zapisana na mjesto koje odaberete. Što se s tom datotekom poslije događa, ovisi o vama |

Sama aplikacija nikada ne prenosi vaše snimke ni vašu Bibliju. Vlastite sigurnosne kopije vašeg uređaja — iCloud sigurnosna kopija, sigurnosna kopija iPhonea ili iPada na računalu, Time Machine na Macu — uključuju podatke aplikacije, zajedno sa snimkama, kao i za svaku drugu aplikaciju. Te sigurnosne kopije izrađuje sustav prema vašim postavkama, a ne BereaNote.

## iCloud sinkronizacija

iCloud sinkronizacija nije obavezna i isključena je dok je ne uključite u Postavkama.

Kada je uključena, sljedeće se stavke spremaju u privatnu bazu podataka vašeg vlastitog iCloud računa putem Appleova CloudKita, kako bi ih mogli čitati vaši drugi uređaji prijavljeni na isti Apple račun: bilješke, mape, linije i događaji vremenske crte, osobe, definicije svojstava te zapis lozinke za zaključavanje stranica (hash sa „solju”, nikada sama lozinka).

Razvojni programer nema pristup tim podacima. Apple ih pohranjuje u skladu s vlastitim Appleovim pravilima privatnosti.

Zaključane stranice sinkroniziraju se kao i svaka druga bilješka. Zaključavanje stranice skriva stranicu unutar aplikacije; ne šifrira je.

iCloud sinkronizacija nudi se kao mjesečna pretplata koja se automatski obnavlja. Pretplatu i plaćanje obrađuje Apple; aplikacija nikada ne prima niti sprema podatke o plaćanju (karticu, ime ili adresu). Ako pretplata završi, pauzira se samo sinkronizacija, a podaci na vašim uređajima ostaju.

Isključivanjem sinkronizacije vaši podaci ostaju i na uređaju i u iCloudu, a kopija u iCloudu ostaje ondje dok je ne izbrišete. Da biste uklonili podatke aplikacije iz iClouda, upotrijebite **Postavke → Opasna zona → iCloud podaci → Izbriši…** (time se sinkronizacija isključuje i na vašim drugim uređajima; podaci na svakom uređaju se zadržavaju) ili ih uklonite u postavkama iCloud pohrane na svojem uređaju.

## Mikrofon

Aplikacija traži pristup mikrofonu kada prvi put pokrenete snimanje. Mikrofon se koristi samo za snimanje zvuka koji prilažete bilješci i samo dok snimate. Na iPhoneu i iPadu snimanje koje ste pokrenuli nastavlja se kada se zaslon zaključa ili prijeđete u drugu aplikaciju, sve dok ga ne zaustavite. Aplikacija ne prenosi snimke.

## Zaključavanje stranica

Lozinka za zaključavanje stranica skriva sadržaj zaključanih stranica unutar aplikacije. Ne šifrira datoteke na vašem uređaju. Lozinka se sprema samo kao hash sa „solju”.

## Što prima razvojni programer

Iz aplikacije ništa. Ako pišete na adresu za podršku, razvojni programer prima ono što pošaljete. Ako ste u postavkama uređaja odabrali dijeljenje dijagnostičkih podataka s razvojnim programerima aplikacija, Apple može proslijediti anonimna izvješća o rušenju.

## Brisanje vaših podataka

- Bilješke brišite u aplikaciji. Bilješke u Košu trajno se uklanjaju nakon 30 dana ili odmah ako to odaberete.
- Podatke aplikacije u iCloudu izbrišite kako je opisano gore.
- Na iPhoneu i iPadu brisanjem aplikacije uklanja se sve što je spremila na tom uređaju.
- Na Macu premještanje aplikacije u Smeće ostavlja njezinu mapu s podacima na mjestu. Da biste uklonili i nju, prije brisanja aplikacije otvorite **Postavke → Informacije → Lokacija spremanja → Prikaži u Finderu** i premjestite tu mapu u Smeće (nalazi se unutar `~/Library/Containers/com.chan.BereaNote`).
- Ništa od navedenog ne uklanja sigurnosne kopije koje ste sami izradili ni kopije koje sadrže vlastite sigurnosne kopije vašeg uređaja.

## Djeca

BereaNote nije namijenjen djeci i ni od koga ne prikuplja osobne podatke.

## Izmjene ovih pravila

Ako se ova pravila promijene, nova se verzija objavljuje na ovoj stranici s novim datumom stupanja na snagu.

## Kontakt

Chan Jung — john1913@naver.com
