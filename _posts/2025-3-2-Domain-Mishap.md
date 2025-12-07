---
layout: post
title: "Domain Mishap and Avoiding UI"
date: 2025-03-02
---

You may have noticed I didn't post last week. That's because, in an attempt to add my **Moral Support Studios** custom domain, I accidentally brought my site down for about two weeks... whoops!  

I ended up having to put in a support ticket with GitHub to get it fixed. Even after removing the domain, the site was still trying to redirect there, so it never worked. *Obviously*, that's been fixed now, and everything is back up and running!

---

## Progress (Or Lack Thereof)  

Unfortunately, I didn't make a lot of progress this week. I had been procrastinating on making the UI for displaying the turn order, and I've also been avoiding the UI for showing available movement for units.  

Honestly, I'm just *not* good at UI in general, and I've realized that when I force myself to work on something I really don't want to do, it *kills* my motivation. But in the end, I think this is actually pushing me past MVP. I'll focus on making the game look good UI-wise during the **Polish phase** in the last quarter of the year. *Or at least, that's what I'm telling myself.*  

---

## The Combat Order System  

While I didn't get much development done, I did flesh out how I want the combat order to work-and it's **pretty much implemented** now.  

I've decided to follow an **Action Point** system based on a unit's Speed stat. These Action Points accumulate until they breach an **Action Threshold**-at that point, the unit takes their turn. I really like this approach.  

My next steps are still to display the turn order, but rather than dealing with a complicated UI, I think I'm just going to start by logging it in the **Debugger**. Later, I might put it on the screen as plain text.

---

## Looking Ahead: A Busy March  

Heads up-March is going to be an **extremely** busy month for me, and I seriously doubt I'll make much progress.  

But that's okay! I'm actually ahead of schedule. I've been able to knock out a lot of setup and make solid progress on both **pathfinding** and the **turn-based system**. So, even if next month is slow, I know I'm still moving forward.

