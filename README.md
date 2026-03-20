# Duel Companion

Jednoduchá mobilná webová aplikácia na zapisovanie skóre pri sledovaní relácie Duel.

## O čom je táto appka

Táto appka funguje ako osobná bodovacia karta pre jedného hráča.
Každý si na svojom mobile zapisuje vlastné skóre podľa toho, čo vidí v televízii.

Nepotrebuje žiadny server, databázu ani prihlasovanie.
Celá aplikácia je len jeden statický HTML súbor, takže je vhodná aj na nasadenie cez GitHub Pages.

## Hlavné funkcie

- výber identity hráča: Modrý alebo Žltý
- neónový vzhľad vo farbe zvoleného hráča
- jedno veľké skóre pre osobné sledovanie bodov
- prepínanie medzi kolami hry
- 1. kolo s 10 otázkami po `30 €`, teda tlačidlá `+30` a `-30`
- 2. kolo s 20 otázkami a hodnotami `20 €`, `40 €`, `60 €`, `80 €` a `100 €`
- 3. kolo s hodnotami `150 €`, `200 €`, `250 €`, `300 €` a `350 €`
- 4. kolo Finále s rovnakým princípom vlastnej stávky
- história posledných akcií pre rýchlu kontrolu
- ukladanie stavu do LocalStorage, takže skóre ostane zachované aj po obnovení stránky

## Technológie

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage

## Spustenie

Stačí otvoriť súbor `index.html` v prehliadači.

Pre nasadenie na GitHub Pages stačí tento repozitár publikovať ako statický web bez ďalších úprav.

## Poznámka

Aplikácia je offline a nezdieľa dáta medzi zariadeniami.
Je navrhnutá zámerne jednoducho, aby bola rýchla, súkromná a bez nastavovania.# Duel_RTVS
