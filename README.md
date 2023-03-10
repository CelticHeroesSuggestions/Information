# Information

## Overview

This project contains detailed suggestions that DECA Games can use to quickly improve the game Celtic Heroes. The repositories here include specific database changes and UI changes to make immediate game improvements the game. This project is ENTIRELY community-driven and is not affiliated whatsoever with DECA games (although we hope they use our suggestions).

Each suggestion is a short `.md` file detailing what the change is. Suggestions are categorized into several areas:

## Database

The database is the MySQL database that Celtic Heroes servers use in their backend. Among other things, the database contains all dialogue, quests, items, skills, NPCs, spawn points, mob stats, and other non-graphical assets.

Suggestions here must be formatted as follows:

Create a new `.md` file in the appropriate folder. The file's title should reflect the change, for easier browsing. The file contains a suggestion as follows:

```
* Title: A concise one-sentence "changelog" style title.
* Why: A concise one-sentence justification for the change.
* Table: Which table to edit.
* ID: An item ID to edit, or the item/quest/mob name.
* Change: What change to make.
* (bonus): An example MySQL command to run, as a starting point for DECA.
```

Suggestions can have multiple IDs and Changes.

For example:

```
* Title: Add focus and vitality to Dhiothu's seer necklaces.
* Why: Seer necklaces are currently underpowered compared to the equivalent Sage necklaces.
* Table: Items
* ID: 65607
* Change: +200 focus, +200 vitality 
* ID: 65608
* Change: +250 focus, +250 vitality
* ID: 65609
* Change: +300 focus, +300 vitality
* ID: 65610
* Change: +350 focus, +350 vitality
* ID: 65611
* Change: +400 focus, +400 vitality
```

The intention is DECA can use these suggestions to more easily make targeted, specific improvements to the game.


## User Interface

The user interface is built using the Unity Game Engine. That gives a lot of inside as to how the UI can work, as Unity uses a standard collection of UI elements and practices.

Suggestions here must be formatted as follows:

```
* Title: A concise one-sentence "changelog" style title.
* Why: A concise one-sentence justification for the change.
* Screen: Which screen to edit.
* Element: Which element to edit.
* Change: What change to make.
* (bonus) Example Code: A short Unity C# code snippet, as a starting point for DECA. This might require you to make guesses about the clientside code, however the developers should be able to figure it out. Reference a code sample from StackOverflow, the Unity Forums, or Unity Documentation if you'd like.
```

Suggestions can have multiple Elements and Changes.

For example:

```
* Title: Reduce outline on text.
* Why: UI text was recently changed to have a thicker border, which looks bad.
* Screen: All.
* Element: All UI text.
* Change: Reduce the outline width of the text UI objects.
* Example Code: [example here] (https://stackoverflow.com/questions/62421243)
```

That's all! Hopefully this project can collect a number of modifications players would like DECA implement in the base game.
