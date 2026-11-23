---
layout: default
title: "Zásady ochrany osobních údajů BereaNote"
lang: cs
---

# Zásady ochrany osobních údajů BereaNote

> Tento překlad slouží pouze pro usnadnění. V případě rozdílů má přednost [anglická verze](privacy.en.html).

Datum účinnosti: 1. prosince 2026

BereaNote je aplikace na poznámky pro osobní studium Bible na Macu, iPadu a iPhonu. Tato stránka vysvětluje, co se při jejím používání děje s vašimi daty.

## Shrnutí

- BereaNote neshromažďuje o vás žádná data.
- V aplikaci není žádný účet, žádná reklama, žádná analytika ani žádný kód třetích stran.
- To, co napíšete, se ukládá ve vašem zařízení a aplikace to nikam neodesílá. Pokud zapnete synchronizaci s iCloudem, ukládá se to také ve vaší vlastní soukromé databázi na iCloudu, kterou vývojář nemůže číst.

## Co aplikace ukládá a kde

| Data | Kde jsou uložena |
| --- | --- |
| Poznámky, složky, časové osy, vlastnosti, nastavení | Ve vašem zařízení, ve vlastním úložišti aplikace |
| Zvukové nahrávky | Ve vašem zařízení. Synchronizace s iCloudem samotný zvuk nenahrává |
| Bible, kterou importujete | Aplikace přečte soubor EPUB, který vyberete, a ve vašem zařízení z něj vytvoří vyhledávací index. Nikdy se nikam nenahrává |
| Zálohy | Soubor ZIP zapsaný na místo, které zvolíte. Co se s tímto souborem stane potom, je na vás |

Aplikace sama nikdy nenahrává vaše nahrávky ani vaši Bibli. Vlastní zálohy vašeho zařízení — záloha na iCloudu, záloha iPhonu nebo iPadu v počítači, Time Machine na Macu — obsahují data aplikace včetně nahrávek, stejně jako u každé jiné aplikace. Tyto zálohy vytváří systém podle vašeho nastavení, nikoli BereaNote.

## Synchronizace s iCloudem

Synchronizace s iCloudem je volitelná a je vypnutá, dokud ji nezapnete v Nastavení.

Když je zapnutá, ukládají se následující položky prostřednictvím služby CloudKit od společnosti Apple do soukromé databáze vašeho vlastního účtu iCloud, aby je mohla číst vaše další zařízení přihlášená ke stejnému Apple účtu: poznámky, složky, linie a události časové osy, osoby, definice vlastností a záznam hesla zámku stránek (hash se solí, nikdy samotné heslo).

Vývojář k těmto datům nemá přístup. Apple je ukládá podle svých vlastních zásad ochrany osobních údajů.

Zamčené stránky se synchronizují stejně jako každá jiná poznámka. Zámek stránky skrývá stránku v aplikaci; nešifruje ji.

Synchronizace s iCloudem se nabízí jako automaticky obnovované měsíční předplatné. Předplatné a platbu zajišťuje Apple; aplikace nikdy nepřijímá ani neukládá platební údaje (kartu, jméno ani adresu). Pokud předplatné skončí, pozastaví se jen synchronizace a data ve vašich zařízeních zůstanou.

Vypnutím synchronizace zůstanou vaše data jak v zařízení, tak na iCloudu, a kopie na iCloudu tam zůstane, dokud ji nesmažete. Chcete-li data aplikace z iCloudu odstranit, použijte **Nastavení → Nebezpečná zóna → Data na iCloudu → Smazat…** (tím se synchronizace vypne i na vašich dalších zařízeních; data v každém zařízení zůstanou zachována), nebo je odstraňte v nastavení úložiště iCloud ve svém zařízení.

## Mikrofon

Aplikace požádá o přístup k mikrofonu, když poprvé spustíte nahrávání. Mikrofon se používá pouze k nahrávání zvuku, který připojíte k poznámce, a pouze během nahrávání. Na iPhonu a iPadu pokračuje spuštěné nahrávání i po zamknutí obrazovky nebo přepnutí do jiné aplikace, dokud ho nezastavíte. Aplikace nahrávky nikam nenahrává.

## Zámek stránek

Heslo zámku stránek skrývá obsah zamčených stránek v aplikaci. Nešifruje soubory ve vašem zařízení. Heslo se ukládá pouze jako hash se solí.

## Co vývojář dostává

Z aplikace nic. Pokud napíšete na adresu podpory, vývojář obdrží to, co pošlete. Pokud jste v nastavení zařízení zvolili sdílení diagnostiky s vývojáři aplikací, může Apple předávat anonymní hlášení o pádech.

## Mazání vašich dat

- Poznámky mažte v aplikaci. Poznámky v Koši se po 30 dnech trvale odstraní, nebo hned, pokud se tak rozhodnete.
- Data aplikace na iCloudu smažte podle popisu výše.
- Na iPhonu a iPadu se smazáním aplikace odstraní vše, co v tomto zařízení uložila.
- Na Macu zůstane po přesunutí aplikace do koše její složka s daty na místě. Chcete-li odstranit i ji, otevřete před smazáním aplikace **Nastavení → Informace → Umístění uložení → Zobrazit ve Finderu** a tuto složku přesuňte do koše (je uvnitř `~/Library/Containers/com.chan.BereaNote`).
- Soubory záloh, které jste vytvořili, a kopie uchovávané ve vlastních zálohách vašeho zařízení se žádným z výše uvedených kroků neodstraní.

## Děti

BereaNote není určena dětem a od nikoho neshromažďuje žádné osobní údaje.

## Změny těchto zásad

Pokud se tyto zásady změní, nová verze bude zveřejněna na této stránce s novým datem účinnosti.

## Kontakt

Chan Jung — john1913@naver.com
