---
layout: post
title: "Balancing DND, Game Dev, and Family"
date: 2025-01-26
---

## DND as a Source of Inspiration

This week, I didn't spend much time on game development. Instead, I focused on preparing some DND games, which has become a key part of shaping the story for *Corrupted Virtues*. 

For a few months now, I've been running *Corrupted Virtues* as a DND campaign with my work friends. As the Dungeon Master (DM), I get to immerse them in the world of *Corrupted Virtues* every other Friday evening. It's been a fantastic way to explore the story and refine the setting for the eventual video game.

In addition to this, I also play DND with my cousins every other Saturday. Currently, I'm a player character in that campaign, but this week, I ran a prequel one-shot to set up a new *Corrupted Virtues* campaign for them. Once our current campaign wraps up, I'll take over as DM, running a campaign in the same world as the one with my work friends.

Although these DND games pull me away from game development, I believe strongly that being a DM is a form of game dev. It's incredibly valuable for building a fun and engaging world and story for my players!

---

## Progress on the Game: Map Improvements and Pathfinding

Despite limited time this week, I did make some progress on the game. I expanded the map to test pathfinding by adding winding paths for units to navigate. This has been great for stress-testing my system and ensuring it works in more complex layouts.

I also made significant changes to how maps are handled in the game. The battle map is now a variable in the `BattleManager`, and I've moved maps into their own scenes. This setup allows me to create multiple maps for the different regions of Areti and pass them into the battle system based on the player's location in the overworld. In the future, I'll also be able to create variations of battle maps for each region, though for now, I'm sticking with one map as a template.

Another exciting improvement was adding spawn points to the maps. Eventually, I want players to choose where their units spawn before a battle starts, adding a tactical element. I'm drawing inspiration from *LucasArts' Gladius* for this mechanic and hope it integrates well with my combat system.

---

## Reference Material for Unit Selection

I stumbled upon an amazing video that perfectly showcases how I want my unit selection to work during battles. It's going to serve as a key reference as I continue developing the system. You can check it out here: [Unit Selection Reference Video](https://www.youtube.com/watch-v=h483cOwz_mw&t=6s).

---

## Reflecting on Scope and Priorities

Looking back on my previous posts, I think I was a bit too ambitious with my goals. I felt a lot of pressure to find time to work on the game and accomplish everything I had planned, which was overwhelming. Thankfully, my incredibly understanding wife has been helping me prioritize. With a 6-month-old son, finding balance is crucial. I want to make sure everyone in my family gets the time and attention they need while still pursuing my passion.

---

## Plans for Next Week: Vacation Mode

Next week, I'll be on vacation, so I don't expect to get much done. However, I'll aim to post another devlog by Sunday to stay accountable. If I do find some time, I plan to research more about how I want my turn-based system to work. Right now, I'm leaning towards using a state machine-it's familiar and sounds fun to implement!

---

Thanks for reading, and see you in the next update!

