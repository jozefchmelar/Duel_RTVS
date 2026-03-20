# Duel Companion

Osobná bodovacia karta pre reláciu Duel na RTVS. Jeden HTML súbor, žiadny server.

## Ako to funguje

1. Vyber si hráča — **Hráč č. 1** (vľavo, tyrkysový neón) alebo **Hráč č. 2** (vpravo, zlatý neón)
2. Zapisuj si skóre počas sledovania relácie
3. Po skončení hry uvidíš súhrn s počtom správnych/nesprávnych odpovedí a celkovou sumou

## Kolá

| Kolo | Otázok | Mechanika |
|------|--------|-----------|
| 1. kolo | 10 | **Viem** (+30 €) alebo **Neviem** (0 €) |
| 2. kolo | 10 | Najprv stav sumu (20–100 €), potom označ správne/nesprávne |
| 3. kolo | 5 | Najprv stav sumu (20–350 €), potom označ správne/nesprávne |

## Funkcie

- neónový dizajn vo farbe zvoleného hráča
- dvojkrokové stávky v 2. a 3. kole (vyber sumu → správne/nesprávne)
- automatický prechod medzi kolami
- progress bar s počítadlom otázok
- tlačidlo Späť na opravu chýb
- súhrn na konci hry (správne, nesprávne, celková nahraná suma)
- ukladanie stavu do localStorage
- blokácia double-tap zoom na iPhone
- offline, žiadne prihlasovanie, žiadna databáza

## Spustenie

Otvor `index.html` v prehliadači alebo nasaď cez GitHub Pages.

---

*vibe coded by [jozefchmelar.com](https://jozefchmelar.com)*
