# Collabjam prejam trader

A collaborative Godot trading game built around physical goods, a balance scale, and NPC customers.

Arrange goods and coins on the trading surface, respond to customers, and use artifacts that change how trades work. The project includes dialogue, day progression, customer variations, and animated menus.

## Run locally

The project declares **Godot 4.4** with the **Forward Plus** renderer in `project.godot`.

1. Clone this repository.
2. Import `project.godot` in Godot 4.4 and let the editor finish importing assets.
3. Run the project with **F6** for the current scene or **F5** for the configured main scene. Use **F5** to start the complete project.

The Dialogue Manager plugin is included under `addons/dialogue_manager/` and enabled in the project configuration.

## Interaction

- Use the mouse to interact with the menus and trading controls.
- Pick up draggable objects with the left mouse button and release it to drop them.
- Place goods on the scale and use the **Deal** control when the trade conditions are satisfied.
- Hover over artifacts to read their descriptions.

## Where things live

| Location | Purpose |
| --- | --- |
| `src/scenes/trade_scene/` | Trading flow, goods, artifacts, and scale behavior |
| `src/scenes/npc_scene/` | Customer scenes and behavior |
| `src/scenes/start_menu_scene/` | Start menu and team credits |
| `src/singletons/` | Scene transitions and sound |
| `assets/` | Game art, audio, and NPC resources |
| `NPCs/` | Name-generation resources and supporting extraction code |
| `CurrencyMaps/` | Currency configuration |
| `addons/dialogue_manager/` | Bundled dialogue plugin |

## Team

The in-game credits name **Berke Özdemir, Morgan, Jktulord, AmberMechanic, Henry, and Sunset**. The scene's detailed credit panel lists code by Berke, Morgan, and Jktulord; visuals by AmberMechanic and Henry; and sound by SunSet.

This is a team project. Repository ownership does not imply sole authorship of its code or assets.

## Project status and reuse

This repository preserves the jam project. The instructions and controls above were checked against the committed configuration and scripts; the game was not playtested during this documentation update.

There is no project-wide license file in the repository. The bundled Dialogue Manager has its own [license](addons/dialogue_manager/LICENSE); that license does not cover the rest of the project or its assets.

[Berke Özdemir — projects and other work](https://github.com/berke-ozdemir)
