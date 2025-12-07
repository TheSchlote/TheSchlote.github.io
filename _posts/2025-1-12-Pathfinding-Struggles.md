---
layout: post
title: "Pathfinding Struggles and Small Wins"
date: 2025-01-12
---

I spent a lot of time feeling discouraged about my pathfinding. I ran into several problems and tried using ChatGPT to help, but it only made things worse. It actually made me consider scrapping the AStar3D + GridMap combination, because ChatGPT clearly couldn't handle what I was trying to do. My goal is pretty simple: I want to make a `GridMap` that has walkable and non-walkable cells, and allows a unit to pathfind up or down one level, such as stepping onto or jumping off a small ledge (or stairs, ramps, etc.). However, Noone on the internet really has any tutorials or videos on how to do this.

ChatGPT even suggested switching to a custom pathfinding script instead of using Godot's built-in `AStar3D`, or switching to a 2D TileMap with elevation as a tile property. This was extremely disheartening and caused me to go to bed stressed a few nights in a row. 

Luckily, I revisited one of my old repositories:  
[GitHub - 3D AStar Godot 4 C#](https://github.com/TheSchlote/3D-Astar-Godot-4-CSharp/blob/main/BattleArena/SimpleAStarPathfinding.cs#L53). 

This had a script that had exactly what I needed. I updated it to work with a scalable cell size and refactored the `GridMap` to be more agnostic to the pathfinding logic. Now, the `GridMap` functions more like an API that unit references during movement. I'm not sure if this structure will stick around by next week, but for now, it's working!

### What's Next for Pathfinding-

I still need to add logic to avoid other units, but I think that's a problem for next week. Progress wasn't as much as I'd hoped this week, but it's critical that the pathfinding has a strong foundation since it's the key to the game's entire gameplay.

---

## TDD Progress and Challenges

I also struggled a lot with Test-Driven Development (TDD) this week. Unit testing is an extremely new skill for me, and I've been trying to learn it for a few years now. The concept is still pretty foreign, but it's starting to click more and more.

This week, I had so many issues figuring out how I wanted the core pathfinding logic to work that I stepped away from a even trying a TDD approach. However, I did write some tests after the fact. These tests will definitely need to be expanded more to ensure I don't break this functionality in the future, but I'm making progress toward my goal of using unit tests and learning TDD!

---

## Plans for Next Week

Here's what I'm planning to focus on next week:

1. **Add Unit Avoidance**  
   I want to add another unit to the game and implement logic to pathfind around it. I experimented with this earlier in the week, but it was scrapped during the pathfinding rework.

2. **Turn Management**  
   I need to decide exactly how turn management will work. In the past, I've used state machines to manage turns, and I'd like to continue with that approach. However, I'll also explore other methods to see if there's a better fit for this project.

3. **Test Unit Improvements**  
   While I know I shouldn't prioritize visuals right now, I really want to add some animations to my test unit. I'd also like it to look in the direction it's moving instead of just lifelessly sliding across the screen.

4. **Overworld Scene**  
   I also need to create a simple overworld scene and implement transitions between the overworld and the combat scene, ensuring data transfers correctly. I also need to update my GitHub Project to include this.

---

## Final Thoughts

Although this week was mostly pretty discouraging, I made some important progress on the pathfinding system and continued learning TDD by the end! Soon hopefully I can figure out how to post pictures on here along with my words.

