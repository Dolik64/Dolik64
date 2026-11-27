# Jiří Doležal

I build Android, desktop and web applications, with an interest in visual interfaces, maps and tools that turn data into something useful.

Student of Open Informatics at the **Faculty of Electrical Engineering, Czech Technical University in Prague**. Based in Prague; also working with photography and video.

## Open-source contributions

### Linux hardware monitoring: yogafan

Diagnosed and fixed both fans reporting **0 RPM** on the **Lenovo Legion Slim 5 14APH8 (82Y5)**. By analysing the ACPI DSDT and reading the embedded controller (EC) fields, I identified that the 8-bit `FANS` and `FA2S` values require a **×100** multiplier. I implemented a model-specific configuration and DMI match, then compiled and tested the driver on my laptop: both channels reported plausible nonzero readings (2100 and 2200 RPM). These readings have not been independently calibrated.

**Status:** The maintainer accepted the contribution into the upcoming `yogafan` patch series targeting `hwmon-next` (Linux 7.5) and reported crediting me in `Documentation/hwmon/yogafan.rst`. **An upstream merge has not yet been confirmed.**

[Investigation, patch & test results](https://github.com/sergiomelas/lenovo-linux-drivers/issues/23) · [Maintainer's confirmation](https://github.com/sergiomelas/lenovo-linux-drivers/issues/23#issuecomment-7210229504)

## Selected projects

Each project below opens a public presentation with screenshots, a walkthrough or sample data. Application source code is not included in these showcase repositories.

| Project | What I built | Explore |
| --- | --- | --- |
| **[České traily](https://github.com/Dolik64/ceske-traily-showcase)** | Interactive MTB trail map with a searchable catalogue, offline mode, trailheads and GPX export. | [Live map](https://ceske-traily.github.io/) · [Walkthrough](https://github.com/Dolik64/ceske-traily-showcase/blob/main/docs/demo.md) |
| **[AI Cluster / LLM Inference](https://github.com/Dolik64/ai-cluster-showcase)** | Hermes-4-70B deployment on a university GPU cluster: Slurm, vLLM, multi-GPU setup and SSH access. | [Architecture & results](https://github.com/Dolik64/ai-cluster-showcase/blob/main/docs/demo.md) |
| **[BookCreator](https://github.com/Dolik64/bookcreator-showcase)** | Android multimedia albums with a library, page editor, playback and sharing. Bachelor project at CTU. | [Interface gallery](https://github.com/Dolik64/bookcreator-showcase/blob/main/docs/demo.md) |
| **[The Last Human](https://github.com/Dolik64/the-last-human-showcase)** | Unity 2D action platformer built in a team. My focus: enemy AI, combat, boss behaviour, lighting and input integration. | [Game & implementation gallery](https://github.com/Dolik64/the-last-human-showcase/blob/main/docs/demo.md) |
| **[Price Offer Builder](https://github.com/Dolik64/price-offer-builder-showcase)** | JavaFX desktop workflow for assembling component-based offers, reading Excel prices and exporting PDF. | [Sample scenario](https://github.com/Dolik64/price-offer-builder-showcase/blob/main/docs/demo.md) |
| **[MacDiskLens](https://github.com/Dolik64/macdisklens-showcase)** | Read-only macOS disk usage analysis with a tree, table, treemap and explicit scan issues. | [Sample report](https://github.com/Dolik64/macdisklens-showcase/blob/main/docs/demo.md) |
| **[OCR / OMR Reader](https://github.com/Dolik64/ocr-showcase)** | Python computer vision prototype for detecting marked A–D answers in fixed-layout response sheets. | [Input and result](https://github.com/Dolik64/ocr-showcase/blob/main/docs/demo.md) |
| **[BlockWorld A*](https://github.com/Dolik64/blockworld-astar-showcase)** | AI coursework: heuristic search for a sequence of legal block moves, with a verified four-move example. | [Visual walkthrough](https://github.com/Dolik64/blockworld-astar-showcase/blob/main/docs/demo.md) |
| **[Combinatorial Optimization](https://github.com/Dolik64/combinatorial-optimization-showcase)** | Python/Gurobi integer programming for cyclic weekly shift scheduling, with verified optima and shortage-limit analysis. | [Schedules & results](https://github.com/Dolik64/combinatorial-optimization-showcase/blob/main/docs/demo.md) |
| **[Doležal Photo](https://github.com/Dolik64/dolezal-photo-showcase)** | Photography portfolio connecting thematic galleries, visual storytelling and a contact journey. | [Live website](https://dolezal-photo.github.io/) |
| **[Doležal Drone](https://github.com/Dolik64/dolezal-drone-showcase)** | Aerial photography website with an image viewer, service pages and responsive image delivery. | [Live website](https://dolezal-drone.github.io/) |

## A closer look

[![České traily: live map and catalogue](https://raw.githubusercontent.com/Dolik64/ceske-traily-showcase/main/assets/overview.png)](https://github.com/Dolik64/ceske-traily-showcase)

[![The Last Human: robot carrying a plant beneath a flying enemy](https://raw.githubusercontent.com/Dolik64/the-last-human-showcase/main/assets/gameplay.webp)](https://github.com/Dolik64/the-last-human-showcase)

## Technologies used in these projects

Kotlin / Jetpack Compose · Java / JavaFX / Swing · C# / Unity 6 / URP 2D · JavaScript · Python / OpenCV / NumPy / Gurobi · Hugo · MapLibre · Git / GitHub Pages · Slurm / vLLM / CUDA

For project details, start with the showcases above. For photography collaboration, use the [contact page](https://dolezal-photo.github.io/kontakt/).
