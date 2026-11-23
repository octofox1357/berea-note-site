---
layout: default
title: "BereaNoten tietosuojakäytäntö"
lang: fi
---

# BereaNoten tietosuojakäytäntö

> Tämä käännös on tarkoitettu vain avuksi. Jos sisällöissä on eroja, [englanninkielinen versio](privacy.en.html) on ensisijainen.

Voimaantulopäivä: 1. joulukuuta 2026

BereaNote on muistiinpanosovellus henkilökohtaiseen Raamatun tutkimiseen Macilla, iPadilla ja iPhonella. Tällä sivulla kerrotaan, mitä tiedoillesi tapahtuu, kun käytät sitä.

## Yhteenveto

- BereaNote ei kerää sinusta mitään tietoja.
- Sovelluksessa ei ole tiliä, mainontaa, analytiikkaa eikä kolmannen osapuolen koodia.
- Kirjoittamasi tallennetaan laitteellesi, eikä sovellus lähetä sitä minnekään. Jos otat iCloud-synkronoinnin käyttöön, se tallennetaan myös omaan yksityiseen iCloud-tietokantaasi, jota kehittäjä ei voi lukea.

## Mitä sovellus tallentaa ja minne

| Tiedot | Missä niitä säilytetään |
| --- | --- |
| Muistiinpanot, kansiot, aikajanat, ominaisuudet, asetukset | Laitteellasi, sovelluksen omassa tallennustilassa |
| Äänitallenteet | Laitteellasi. iCloud-synkronointi ei lähetä itse ääntä |
| Tuomasi Raamattu | Sovellus lukee valitsemasi EPUB-tiedoston ja luo siitä hakuhakemiston laitteellesi. Sitä ei koskaan lähetetä minnekään |
| Varmuuskopiot | ZIP-tiedosto, joka kirjoitetaan valitsemaasi paikkaan. Se, mitä tiedostolle sen jälkeen tapahtuu, on sinun päätettävissäsi |

Sovellus itse ei koskaan lähetä tallenteitasi tai Raamattuasi minnekään. Laitteesi omat varmuuskopiot — iCloud-varmuuskopio, iPhonen tai iPadin varmuuskopio tietokoneelle, Time Machine Macilla — sisältävät sovelluksen tiedot tallenteineen, kuten minkä tahansa sovelluksen kohdalla. Nämä varmuuskopiot tekee järjestelmä asetustesi mukaisesti, ei BereaNote.

## iCloud-synkronointi

iCloud-synkronointi on valinnainen, ja se on pois päältä, kunnes otat sen käyttöön Asetuksissa.

Kun se on käytössä, seuraavat kohteet tallennetaan oman iCloud-tilisi yksityiseen tietokantaan Applen CloudKitin kautta, jotta muut samalla Apple-tilillä kirjautuneet laitteesi voivat lukea ne: muistiinpanot, kansiot, aikajanan linjat ja tapahtumat, henkilöt, ominaisuuksien määritelmät sekä sivulukituksen salasanatietue (suolattu tiiviste, ei koskaan itse salasana).

Kehittäjällä ei ole pääsyä näihin tietoihin. Apple säilyttää ne Applen oman tietosuojakäytännön mukaisesti.

Lukitut sivut synkronoidaan kuten mikä tahansa muu muistiinpano. Sivulukitus piilottaa sivun sovelluksen sisällä; se ei salaa sitä.

iCloud-synkronointia tarjotaan automaattisesti uusiutuvana kuukausitilauksena. Apple hoitaa tilauksen ja maksun; sovellus ei koskaan vastaanota eikä tallenna maksutietoja (korttia, nimeä tai osoitetta). Jos tilaus päättyy, vain synkronointi keskeytyy, ja laitteillasi olevat tiedot säilyvät.

Kun synkronointi poistetaan käytöstä, tiedot jäävät sekä laitteelle että iCloudiin, ja iCloudissa oleva kopio säilyy siellä, kunnes poistat sen. Voit poistaa sovelluksen tiedot iCloudista kohdasta **Asetukset → Vaaralliset toiminnot → iCloud-tiedot → Poista…** (tämä poistaa synkronoinnin käytöstä myös muilla laitteillasi; kunkin laitteen tiedot säilyvät) tai laitteesi iCloud-tallennustilan asetuksista.

## Mikrofoni

Sovellus pyytää lupaa käyttää mikrofonia, kun aloitat tallennuksen ensimmäisen kerran. Mikrofonia käytetään vain sellaisen äänen tallentamiseen, jonka liität muistiinpanoon, ja vain tallennuksen aikana. iPhonessa ja iPadissa aloittamasi tallennus jatkuu, kun näyttö lukittuu tai siirryt toiseen sovellukseen, kunnes lopetat sen. Sovellus ei lähetä tallenteita minnekään.

## Sivulukitus

Sivulukituksen salasana piilottaa lukittujen sivujen sisällön sovelluksen sisällä. Se ei salaa laitteellasi olevia tiedostoja. Salasana tallennetaan vain suolattuna tiivisteenä.

## Mitä kehittäjä saa

Sovelluksesta ei mitään. Jos kirjoitat tukiosoitteeseen, kehittäjä saa sen, mitä lähetät. Jos olet laitteesi asetuksissa valinnut jakaa analyysitietoja sovelluskehittäjien kanssa, Apple voi välittää nimettömiä kaatumisraportteja.

## Tietojesi poistaminen

- Poista muistiinpanot sovelluksessa. Roskakorissa olevat muistiinpanot poistetaan lopullisesti 30 päivän kuluttua tai heti, jos niin valitset.
- Poista sovelluksen iCloud-tiedot yllä kuvatulla tavalla.
- iPhonessa ja iPadissa sovelluksen poistaminen poistaa kaiken, mitä se on tallentanut kyseiselle laitteelle.
- Macilla sovelluksen siirtäminen roskakoriin jättää sen tietokansion paikalleen. Jos haluat poistaa senkin, avaa ennen sovelluksen poistamista **Asetukset → Tietoja → Tallennussijainti → Näytä Finderissa** ja siirrä kyseinen kansio roskakoriin (se on kansiossa `~/Library/Containers/com.chan.BereaNote`).
- Mikään edellä mainituista ei poista luomiasi varmuuskopiotiedostoja eikä laitteesi omien varmuuskopioiden sisältämiä kopioita.

## Lapset

BereaNotea ei ole suunnattu lapsille, eikä se kerää henkilötietoja keneltäkään.

## Muutokset tähän käytäntöön

Jos tämä käytäntö muuttuu, uusi versio julkaistaan tällä sivulla uuden voimaantulopäivän kera.

## Yhteystiedot

Chan Jung — john1913@naver.com
