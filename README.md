# LW Planner — WoW Forever

Interaktywny planer zestawów z **Leatherworkingu** dla WoW: Forever — najlepszy item na każdy slot i każdy level.

**Live:** https://rgx78.github.io/lw-planner/
**Lokalnie:** uruchom `START.bat` (albo otwórz `index.html`) — działa offline, ikony są w `icons/`.

## Co robi
- Suwak levelu **1–60** → pokazuje najlepszy zestaw na 8 slotów (hełm, ramiona, chest, bransolety, rękawice, pas, nogi, buty).
- Ranking: **agility ×2 + intellect** (+ sta i armor z małą wagą). Przełącznik „tylko itemy z agi/int".
- Filtr typu zbroi: **Auto** (skóra 1–39, mail od 40 — i skóra, jeśli wypada lepiej), **Skóra**, **Mail**.
- Uwzględnia **limit skilla LW na level**: 1–9 → 75, 10–19 → 150, 20–34 → 225, 35+ → 300.
- Badge **BoP/BoE**, wymagany level itemu i wymagany skill craftu.
- Tabela „wszystkie itemy" z wyszukiwarką (456 pozycji) i ikonami.
- Zakładka **Guns**: 74 guny z bazy (DPS, speed, staty, bind, craft) + suwak levelu pokazujący top 3 dostępne na danym levelu.
- Zakładka **Buffy**: 43 consumable'y z agility/intellect (13 elixirów + 30 dań z gotowania) — efekt, czas trwania, wymagany level; filtr Wszystkie/Agi/Int/Elixiry/Jedzenie. Uwaga: elixir i jedzenie działają równolegle (1 battle + 1 guardian + 1 food).
- Zakładka **Enchanty**: 162 enchanty (chest, gloves, bracers, boots, cloak, necklace, weapon, 2H) z efektem, wymaganym skillem i źródłem (trener/wzór); ★ = wybór dla huntera (agi/int).

## Dane
- Receptury i skille: [sktools.gg](https://sktools.gg/forever/professions/leatherworking) — build **1.60.1.70630**.
- Statystyki i ikony itemów: baza [warcraftforever.games](https://warcraftforever.games/) (build 1.60.1.70009).
- Stan: **27.10.2026**. Ranking nie uwzględnia bonusów „Equip:" (crit/hit) ani enchantów.

## Struktura
```
index.html   — cała aplikacja (dane wbudowane w <script>)
icons/       — 456 ikon itemów (jpg, ~2 MB)
START.bat    — otwiera aplikację w domyślnej przeglądarce
```
