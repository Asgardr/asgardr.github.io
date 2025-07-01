---
layout: page
title: Lilith Rise of the Fallen
subtitle: A Bullet Heaven where you'll try to survive while you corrupt the map
cover-img: "/assets/Lilith_wallpaper.png"
---

### Summary

**Lilith: Rise of the Fallen** is my Master's Thesis for my Master's Degree in Video Game Porgramming at the UCM, where I worked with a group of programmers, desingers, artists and producers to create this game in Unreal Engine 5.

Lilith takes inspiration in games like Vampire Survivors, Death Must Die and 20 Minutes Till Dawn, where the player has to survive hordes of enemies while it upgrades his abilities and unlockes new ones that attack the enemies automatically. In Lilith we decided to amplify the gameplay of this types of games, adding a new mecanic of corruption similar to Splatoon, where the player has to "paint" as much of the map as possible to win.

### Contribution

I was able to work in many parts of the game, but my main work was in:

  - **Corruption System**
    - **Map Corruption:** Main mecanic, giving the ability to the player to corrupt the map. Implemented using an **Hexagonal Grid**.
    - **Corruption Effects:** Applied debuff (p.e. slow, vulnerable, charm) to the enemies while on top of the corruption.
      ![](assets/Lilith_corruption.gif)
  - **Waves System**
    - **Waves Spawn**: Spawn of waves in a timer, with each waves having a cost to be spawn, seconds added or substracted to said timer and conditions to be spawn dependant of other variables like Enemies in Play or Time Played
    - **Waves Creation Tool:** Tool for desingers to create custom waves of enemies with different conditions to spawn, types of enemies and all that was necessary on our wave system 
      ![](assets/Wave_tool.png)
  - AI
    - Boss
    - Cleaner
    - Charm
  - Player Abilities
    - Sloth
    - Lust
  - Logging
  - UI
