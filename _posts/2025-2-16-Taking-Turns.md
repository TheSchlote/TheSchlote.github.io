# TurnSystem and UI Struggles

Right now, I’m feeling frustrated, discouraged, and unmotivated. I didn’t really get to spend a lot of time on the project this week. 

I feel like I got to a really good spot with pathfinding and the UI for moving the unit where it should go. So, the next thing I’m working on is the turn-based system. I did spend a few hours researching the best way to handle turn-based combat, and I’m pretty happy with what I’ve come up with. Even though I’m trying to keep it simple, I landed on the following states:

- **Start**  
- **NextTurn**  
- **PlayerTurn**  
- **EnemyTurn**  
- **TurnEnd**  
- **EndBattle**  

I’m hoping this keeps the system scalable and modular enough that I won’t have to add more states. Ideally, the states shouldn’t have too much overlap either.

---

### The UI Struggle

The part I’m getting stuck on right now is that I really want to add some UI to show the current turn order... and I *suck* at anything UI-related. I think tonight has shown me that I’m going to need to go through some more tutorials before I can continue making progress.

---

### The Unit Test Dilemma

Also, all of my unit tests are broken. That has been incredibly discouraging because an integral part of this project is learning unit testing. I know I’m only two months in, and I keep telling myself that I’ll go back and add in unit tests once the foundation of the game is more stable. 

But at the same time, I feel like I’m selling myself short on learning unit testing. It’s hard to balance making progress on the game while also maintaining tests. The good thing is—I’m my own boss with this project. I get to make my own decisions. Right now, I’m choosing to leave them broken *for now*, but I *will* have them done before I move on to any Q2 functionality.

---

### Next Steps

I think I’m also going to check in a new branch tonight called **TurnSystem**. I’m hesitant to merge my **GridMovement** branch into **Main** until my unit testing is done, so I’ll be wrestling with this decision all week.

---

Not the best week, but I’m reminding myself that this is a long-term project. Some weeks will be slow. Some will be frustrating. The important thing is to keep moving forward.
