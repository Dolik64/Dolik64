# Jiří Doležal

Vytvářím aplikace pro Android, desktop a web. Zajímají mě vizuální rozhraní, mapy a nástroje, které převádějí data do použitelné podoby.

Studuji **Otevřenou informatiku na FEL ČVUT v Praze**. Věnuji se také fotografii a videu.

## Příspěvky do open source

### Monitorování hardwaru v Linuxu: yogafan

Diagnostikoval a opravil jsem chybu, kvůli které oba ventilátory notebooku **Lenovo Legion Slim 5 14APH8 (82Y5)** hlásily **0 RPM**. Analýzou ACPI DSDT a čtením polí vestavěného řadiče (EC) jsem zjistil, že 8bitové hodnoty `FANS` a `FA2S` vyžadují násobení **×100**. Doplnil jsem konfiguraci a DMI shodu pro konkrétní model, ovladač zkompiloval a otestoval na svém notebooku: oba kanály hlásily věrohodné nenulové otáčky (2100 a 2200 RPM). Přesnost těchto hodnot zatím nebyla nezávisle kalibrována.

**Stav:** Správce přijal příspěvek do připravované série patchů `yogafan` pro `hwmon-next` (Linux 7.5) a potvrdil uvedení mého příspěvku v `Documentation/hwmon/yogafan.rst`. **Začlenění do upstream Linuxu zatím není potvrzené.**

[Diagnostika, patch a výsledky testování](https://github.com/sergiomelas/lenovo-linux-drivers/issues/23) · [Potvrzení správce](https://github.com/sergiomelas/lenovo-linux-drivers/issues/23#issuecomment-7210229504)

## Vybrané projekty

Veřejné prezentace níže obsahují screenshoty, průvodce nebo demonstrační data. Zdrojový kód aplikací v těchto prezentačních repozitářích není.

| Projekt | Co jsem vytvořil | Ukázka |
| --- | --- | --- |
| **[České traily](https://github.com/Dolik64/ceske-traily-showcase/blob/main/README.cs.md)** | Interaktivní mapa MTB trailů s hledáním, offline režimem, nástupy a GPX. | [Živá mapa](https://ceske-traily.github.io/) |
| **[AI cluster / LLM inference](https://github.com/Dolik64/ai-cluster-showcase)** | Nasazení Hermes-4-70B na univerzitním GPU clusteru: Slurm, vLLM, více GPU a SSH přístup. | [Architektura a výsledky](https://github.com/Dolik64/ai-cluster-showcase/blob/main/docs/demo.md) |
| **[BookCreator](https://github.com/Dolik64/bookcreator-showcase/blob/main/README.cs.md)** | Androidová multimediální alba s knihovnou, editorem, přehrávačem a sdílením. Bakalářský projekt na ČVUT. | [Obrazový průchod](https://github.com/Dolik64/bookcreator-showcase/blob/main/docs/demo.md) |
| **[The Last Human](https://github.com/Dolik64/the-last-human-showcase/blob/main/README.cs.md)** | Týmová akční 2D plošinovka v Unity. Můj podíl: AI nepřátel, souboje, boss, osvětlení a integrace ovládání. | [Galerie hry a implementace](https://github.com/Dolik64/the-last-human-showcase/blob/main/docs/demo.md) |
| **[Generátor nabídek](https://github.com/Dolik64/price-offer-builder-showcase/blob/main/README.cs.md)** | Desktopový postup od komponent a excelového ceníku po nabídku v PDF. | [Modelová nabídka](https://github.com/Dolik64/price-offer-builder-showcase/blob/main/demo/sample-offer.md) |
| **[MacDiskLens](https://github.com/Dolik64/macdisklens-showcase/blob/main/README.cs.md)** | Analýza disku v macOS se stromem, tabulkou, treemapou a viditelnými problémy skenu. | [Demonstrační report](https://github.com/Dolik64/macdisklens-showcase/blob/main/demo/sample-scan.csv) |
| **[OCR / OMR čtečka](https://github.com/Dolik64/ocr-showcase/blob/main/README.cs.md)** | Prototyp v Pythonu pro rozpoznání označených políček A–D v odpovědních arších. | [Vstup a výsledek](https://github.com/Dolik64/ocr-showcase/blob/main/docs/demo.md) |
| **[BlockWorld A*](https://github.com/Dolik64/blockworld-astar-showcase/blob/main/README.cs.md)** | Studijní projekt: heuristické hledání přesunů kostek s ověřenou čtyřtahovou ukázkou. | [Obrazový průchod](https://github.com/Dolik64/blockworld-astar-showcase/blob/main/docs/demo.md) |
| **[Kombinatorická optimalizace](https://github.com/Dolik64/combinatorial-optimization-showcase/blob/main/README.cs.md)** | Celočíselné programování v Pythonu a Gurobi: cyklické plánování směn, ověřená optima a vliv limitu podstavu. | [Rozvrhy a výsledky](https://github.com/Dolik64/combinatorial-optimization-showcase/blob/main/docs/demo.md) |
| **[Doležal Photo](https://github.com/Dolik64/dolezal-photo-showcase/blob/main/README.cs.md)** | Fotografické portfolio s tematickými galeriemi a cestou ke kontaktu. | [Živý web](https://dolezal-photo.github.io/) |
| **[Doležal Drone](https://github.com/Dolik64/dolezal-drone-showcase/blob/main/README.cs.md)** | Web letecké fotografie s prohlížečem snímků a stránkami služeb. | [Živý web](https://dolezal-drone.github.io/) |

## Technologie projektů

Kotlin / Jetpack Compose · Java / JavaFX / Swing · C# / Unity 6 / URP 2D · JavaScript · Python / OpenCV / NumPy / Gurobi · Hugo · MapLibre · Git / GitHub Pages · Slurm / vLLM / CUDA

Podrobnosti najdeš v jednotlivých prezentacích. Pro spolupráci na focení použij [kontaktní stránku](https://dolezal-photo.github.io/kontakt/).
