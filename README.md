# HogwartsMini: An Unfinished Harry Potter Sandbox

## **✨ Project In Development**

This project is an open-sandbox RPG inspired by the Harry Potter universe, built in Unity.

---

## **📌 Overview**

HogwartsMini is an open-sandbox role-playing game set in the Harry Potter universe, implemented in Unity. It features a dynamic multiplayer environment where players can explore Hogwarts, engage in spell combat, interact with NPCs, and embark on quests.

---

## **🧠 Theme & Concept**

Immerse yourself in a magical world where you can create a new character, explore Hogwarts, and experience life as a wizard or witch. The game aims to provide an open-world experience with elements of combat, social interaction, and questing.

---

## **⚙️ Game Features**

- **Multiplayer**: Interact with other players in the game world.
- **Chat**: Communicate with other players in real-time.
- **Inventory**: Manage your items and equipment.
- **NPCs**: Encounter aggressive, selling, quest-giving, and talking non-player characters, some with patrol routes.
- **Spells Combat**: Engage in magical duels and use various spells.
- **Flying Broomstick**: Traverse the world on your broomstick.
- **Quests**: Undertake tasks and missions within the game.

---

## **🎮 Controls**

- WASD: Player control (basic movement and broomstick control).
- ESC: Open configuration menu.
- F1: Enable Developer options in the ESC menu.
- F2: Take a screenshot.
- Z: Hide UI.
- E: Broomstick spell.
- Q: Lumos spell.
- T: Open chat.
- B: Open inventory bag.
- C: Open character sheet.
- Left Mouse: Select target.
- 1, 2, 3... keys: Cast spells.
- Right Mouse (Broomstick): 3D Direction control for broomstick.

---

## **👥 Development Team**

| Name                     | Contributions                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **Alexandru Rudoi**      | Made the UI, Made the spell system, Crafting system: you can hit multiple buttons at once and spells combine, Multiplayer system  |
| **Artur Țugui**          | Implemented directional vectors, NPC always turn to you, Made the flying, Report  |
| **Nicolae Marga**        | Made enemy range, visiosn and pathfinding, Made enemies to oscillate while the player is far, Made target sellection  |
| **Timur Cravțov**        | Found the textures on Kenney, Made initial controls , Made neutral NPCs sellers, questers, talkers and the shop system  |
| **Vladimir Vitcovschii** | Made NPC quest generation using Grok, Made the enemy heath system and appearing healthbars about enemies/npc |

---

## **🧱 Technologies**

- **Engine**: Unity
- **Language**: C#
- **Graphics**: Custom-designed models, textures, and UI elements.
- **Audio**: Music and ambient sounds.
- **Logic**: RPG mechanics, multiplayer networking, AI for NPCs, and spell systems.

---

## **🗂️ File Structure**
```
Assets/
├── Resources/
│   ├── Backgrounds/
│   ├── Buttons/
│   ├── Cells/
│   └── Prefabs/
├── Scenes/
├── Scripts/
├── Settings/
├── TextMesh Pro/
Resources/: Visual assets, cell textures, UI buttons
Prefabs/: Dumbledore, Voldemort, and house-specific cell prefabs
Scripts/: All gameplay, zone, and simulation logic
Scenes/: Title screen and main simulation scene
```

--- 

## **🚀 How to Run**

Open the project in Unity 2022.3 or later.
Open the MainMenu scene located in Assets/Scenes/MainMenu.
Click Play in the Unity Editor.
Inside the game, click "Create a New Character", set the name, and click "Enter".