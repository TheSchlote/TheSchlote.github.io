---
layout: post
title: "Two Weeks of Progress - Auth MVP, Connect App, and Easter Break Ahead"
date: 2025-04-13
---

Hey everyone, it's TheSchlote!

It's been a couple weeks since my last update (whoops), but things have still been moving - just more on the business dev side than game dev. Let's catch up on what's been happening and what's next.

## Moral Support Auth MVP - Taking Shape

A lot of recent effort has gone into building out **Moral Support Auth**, the centralized authentication system for the Moral Support Studios Suite. This app will eventually handle login for all other apps in the suite.

Here's what we've tackled so far:
- Created the `MoralSupport.Authentication` solution using Clean Architecture
- Set up the base projects for Web, Application, Domain, and Infrastructure
- Started scaffolding the Razor Pages for the Google Sign-In flow
- Prepped EF Core integration for saving authenticated users
- Began wiring in token verification logic behind the scenes

It's not quite done yet, but the bones are in place and it's starting to look like a real app.

## Next App - Moral Support Connect

After nearing completion on **Moral Support Tasks**, we decided to pivot toward a smaller, more focused app before going too big. That brought us to **Moral Support Connect**, an app to help users sign in with Google, create organizations, invite other users, and assign roles within those orgs.

This is inspired by my wife's family business, where everyone helps out across multiple companies but still needs clear separation for ownership, maintenance, and record keeping.

This app will:
- Let people log in with Google
- Create & manage organizations
- Assign roles and permissions
- Lay the groundwork for collaborative business tools

It's meant to be small, simple, and practical - just enough to solve real problems without over-scoping.

## Game Dev - On Pause (For Now)

I haven't made any progress on the **Corrupted Virtues** prototype the past couple weeks. It's still something I care deeply about and want to finish this year, but I've been prioritizing the Moral Support Suite lately. That's where most of my energy is going right now.

Once I've got Auth and Connect in a good place, I'll loop back around to game dev and give it the time it deserves.

## No Post Next Week - Easter Break

Heads up: there won't be a blog post next weekend. I'll be taking a break for Easter and spending some quality time with family. Regular updates will resume the week after.

Thanks again for following along-I'll see you in two weeks!

