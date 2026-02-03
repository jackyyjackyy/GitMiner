# GitMiner

Minihra pro učení termínů (GitHub, Blender) a získávání surovin skrze odpovědi na kartičky.

## Popis
- Interaguj s objektem (těžit) a zobrazí se karta s termínem: název, stručné vysvětlení a kontrolní otázka Ano/Ne.
- Hra není na čas — odpovídej pečlivě. Správná odpověď dává "stupně_těžení" a suroviny; špatná odpověď snižuje kapacitu těžení (4 pokusy).
- Postup a suroviny se ukládají do localStorage.
- K dispozici jsou kategorie karet (GitHub, Blender), slovník a obchod (shop) s upgradami.

## Rychlý start
1. Klonuj repozitář:
   git clone https://github.com/jackyyjackyy/GitMiner
2. Otevři `index.html` ve svém prohlížeči (statická stránka).

## Struktura projektu
- `index.html` — hlavní stránka a UI
- `styles.css` — styly
- `script.js` — herní logika
- `README.md` — tento soubor

## Přizpůsobení a rozšíření
- Přidávání termínů: uprav funkce `generateTermsGitHub()` a `generateTermsBlender()` v `script.js` (js soubor obsahuje ukázková data a generování až do 500 termínů).
- Shop/Upgrady: pole `SHOP` v `script.js` (lze přidat nové položky a logiku `apply`).
- Slavný bug: došlo k dočasnému použití pole `dovedskill` vedle `dovednost` (kompatibilita). Kód obsahuje úpravy; můžeš sjednotit proměnné v `script.js`.

## Licence
Repo defaultně používá MIT licenci (můžeš změnit podle potřeby).

## Přispívání
- Vytvoř PR do větve `main` nebo pošli issue s návrhem.
- Přidej nové kategorie, termíny nebo vylepšení UX.
