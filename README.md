# Ragdoll Range

Soukromý fyzikální playground: first-person střelba, aktivní ragdolly, fyzikální předměty a výbušné sudy. Zatím prototyp pro hraní a testování s přáteli.

Tento repozitář obsahuje jen popis hry. Hotové buildy jsou v sekci **Releases**; zdrojový projekt zde není zveřejněný.

## Stažení a spuštění

Otevři **Releases** a stáhni přílohu pro svůj systém:

- **Windows x64:** `RagdollRange.exe`. Stačí spustit jediný soubor, bez instalace Godotu.
- **macOS:** `RagdollRange-macOS.zip`. Rozbal a otevři `Ragdoll Range.app`. Obsahuje Intel i Apple Silicon variantu; vyžaduje macOS 11 na Intelu, macOS 13 na Apple Silicon. Build má ad-hoc podpis, není notarizovaný Applem a jeho spuštění zatím nebylo ověřeno na Macu. macOS může požadovat povolení v nastavení Soukromí a zabezpečení.

Ke stažení ze soukromého repozitáře musíš být přihlášený na pozvaném GitHub účtu a přijmout pozvánku.

## Ovládání

| Akce | Ovládání |
| --- | --- |
| Pohyb / běh | WASD / Shift |
| Skok | Mezerník |
| Míření / střelba | Myš / levé tlačítko |
| Pistole / brokovnice / minigun | 1 / 2 / 3 |
| Přidání NPC pod zaměřovač | Pravé tlačítko |
| Nabídka NPC a všech předmětů | Stisk kolečka |
| Nastavení parametrů | F2 |
| Obnovení arény | R |
| Pixelový filtr | P |
| Uvolnění kurzoru / zavření nabídky | Esc |
| Ukončení | Zavření okna |

## Co vyzkoušet

- NPC reagují na zásahy podle zasažené části těla, vyrovnávají rovnováhu a po přežitém pádu se mohou zvednout.
- Sílu, poškození a kadenci zbraní změníš ve F2. Silné zásahy odhazují těla do vzduchu.
- Bedny, běžné sudy a koule jsou nezničitelné, ale reagují fyzikou na střelbu, NPC i exploze.
- Červené sudy TNT mají zdraví a mohou spustit řetězový výbuch. Ve F2 nastavíš jejich zdraví, poloměr, poškození, sílu i zdvih exploze.
- Výbuchy odhazují a roztáčejí předměty. Zasahují i hráče; po vyčerpání HP se vrátíš na start.
- R obnoví i vybuchlé sudy. Nastavení F2 platí pro aktuální běh, některé změny zdraví pro nové objekty nebo po resetu.

Prototyp se průběžně mění. Když narazíš na problém, napiš do Issues, co jsi udělal, jaké jsi měl nastavení a jaký systém používáš.
