# Functional Specification

- [Functional Specification](#functional-specification)
  - [Glossary](#glossary)
  - [I. Introduction](#i-introduction)
    - [1. Project Overview](#1-project-overview)
    - [2. Project Definitions](#2-project-definitions)
      - [A. Project Vision](#a-project-vision)
      - [B. Objectives](#b-objectives)
      - [C. Project Scope](#c-project-scope)
      - [D. Audience](#d-audience)
      - [E. Main deliverables](#e-main-deliverables)
  - [II. Functional Requirement](#ii-functional-requirement)
    - [1. Core Gameplay Mechanics](#1-core-gameplay-mechanics)
      - [A. Directly Into the Game](#a-directly-into-the-game)
      - [B. Genre-based Chapters as Gameplay Worlds](#b-genre-based-chapters-as-gameplay-worlds)
      - [C. Gameloop](#c-gameloop)
      - [D. Experimentation and Structured Problem Solving](#d-experimentation-and-structured-problem-solving)
      - [E. Story Integration](#e-story-integration)
      - [F. Reactions to Player Choices](#f-reactions-to-player-choices)
    - [2. Editor Features](#2-editor-features)
      - [A. Editor Overview (NEW section — just a few sentences)](#a-editor-overview-new-section--just-a-few-sentences)
      - [B. Enter Editor Mode](#b-enter-editor-mode)
      - [C. Main Editor Page](#c-main-editor-page)
      - [D. Toolbar](#d-toolbar)
      - [E. Drawing Mode](#e-drawing-mode)
      - [F. Music Mode](#f-music-mode)
      - [G. Coding Mode](#g-coding-mode)
      - [H. Mockups \& Design Tools](#h-mockups--design-tools)
      - [I. Testing/Preview Mode](#i-testingpreview-mode)
      - [J. Undo Feature and Autosave](#j-undo-feature-and-autosave)
    - [3. Mentor System](#3-mentor-system)
    - [4. Chapter Progression](#4-chapter-progression)
      - [A. Chapter Structure](#a-chapter-structure)
      - [B. Progression Flow](#b-progression-flow)
      - [C. Tutorial Elements](#c-tutorial-elements)
      - [D. Chapter Order](#d-chapter-order)
      - [E. Player Influence Chapter Progression](#e-player-influence-chapter-progression)
    - [5. Game Repairs](#5-game-repairs)
    - [6. Objectives \& Freedom](#6-objectives--freedom)
    - [7. Audio and Sound Design](#7-audio-and-sound-design)
    - [8. Saving system](#8-saving-system)
    - [9. UX/UI](#9-uxui)
    - [10. 3D/2D](#10-3d2d)
  - [III. Non Functional Requirement](#iii-non-functional-requirement)
    - [1. Performances](#1-performances)
    - [2. Technical Requirements](#2-technical-requirements)


## Glossary
|Term | Definition|
|-----|-----------|
| 

## I. Introduction

### 1. Project Overview

### 2. Project Definitions

#### A. Project Vision

Learn game development in it's integrality (Character making, sound design, mechanics...) often feels fragmented and tedious. Existing tools and platforms, whether tutorials, courses, or gamified apps, mostly focus on isolated topics and lack creativity or engagement.

Most of these solutions either covers small parts of what game development truly is. This methods also lacked of engagement and specificly for gamified website/apps they lack creativity

"Game dev The game" offers a solution to this issue, giving a story driven game that is also cappable of learning as well as a course or gamified apps, while allowing more creativity than those.

#### B. Objectives

➭ Create an interactive, story-driven game that teaches the fundamentals of game development and coding.

➭ Develop a modular editor where players can experiment with game mechanics, music, art, and animation.

➭ Implement a mentor system that balances learning and creative freedom.

➭ Cover multiple game genres (platformer, RTS, RPG) across progressive chapters with increasing complexity.

➭ Include meaningful player choice, leading to multiple narrative endings.

➭ Optimize the game to run smoothly on low-performance PCs. Release a playable prototype and progress toward a polished, full version.

#### C. Project Scope

|In Scope|
|--------|
Story-driven interactive learning experience
In-game editor for code, music, animation, art
Mentor guidance and adaptive hint system
Chapters focused on multiple game genres
Optimized performance for low-end machines


|Nice to have|
|------------|
Sandbox mode after main story
Online content sharing or modding support
Community-based challenges


|Out of Scope|
|------------|
Online multiplayer or co-op functionality
VR/AR platform development
In-game purchases or monetization systems

#### D. Audience

- **Junior game developers** who will learn using the game
- **Schools or educators** who might use the game as a learning tool.
- **Game devs that haven't tried some of the different game genre**.
- **Regular players** That are curious of how to make a game.

#### E. Main deliverables

The main deliverables are :

➭ **The entirety of the editor**, even tho in the first chapter the player will not use everything, the functionalities must be ready for the next chapters (more information in the [editor features](#2-editor-features)).

➭ **At least the first chapter for April 19th 2027** to receive critical gameplay feedback.

➭ **All core gameplay mechanics** to have a stable and enjoyable gameplay.

➭ **A fully functioning demo version for April 22nd 2027**.

➭ **A windows and MacOS version**.

## II. Functional Requirement

### 1. Core Gameplay Mechanics

#### A. Directly Into the Game

The player will arrive in a partially built or broken game project, where the goal is to either complete missing features or repair corrupted mechanics, visuals, or systems.

#### B. Genre-based Chapters as Gameplay Worlds

Each chapter functions like a game world built around a specific genre (platformer, strategy, RPG...). 
Players will first explore these game environments to find issues, repair broken components, and access the editor when needed.

#### C. Gameloop

Players will have this basic game loop :

![Game loop schema](/documents/images/game_loop_schema.png)

When they enter a new chapter **players plays the game** taking note of the genre and level design of this chapter.

When they find an issue in it they will open the editor and fix the issue using their creativity or use the help of the [mentor system](#3-mentor-system).

Finally they test their modification and if it's a success, they restart the loop until the end of the chapter. 

#### D. Experimentation and Structured Problem Solving

Problem solving is one of the most important skills as game dev, which is why some problems have clearly defined solutions (e.g., “fix enemy movement”), while others encourage freeform (e.g.: “design your own level layout” or “balance enemy AI”).

#### E. Story Integration

The different gameplay mechanic and features are closely tied to the storyline affecting the way of playing and the different problems solving steps inside the game.

#### F. Reactions to Player Choices

The game reacts to how players solve challenges—following mentor guidance or using creative workarounds. These choices influence dialogue, world changes, and the ending.


### 2. Editor Features


#### A. Editor Overview (NEW section — just a few sentences)

The in-game editor is the player's main tool for creating and modifying the broken games. It mimics a simplified game engine interface to help new devs learn transferable skills.

#### B. Enter Editor Mode

To enter in the editor mode, you have to press the key that, in other games, redirect players into the pause menu. This button is usually the "escape" button on computers.

The editor is supposed to look like game engine editor to make sure the new game dev aren't lost when they go to an actual game engine.

#### C. Main Editor Page

When you enter in the editor, the first page that shows up will show you the game file tree on the left, the toolbar on the top and the asset inspector.

#### D. Toolbar

The toolbar integrates the editor mode selector, meaning by clicking on it you can select the different modes, modifying the editor interface to have a better focus on a specific aspect of game dev.

The toolbar also have :

- A play button, to play the game after the modifications.
- The name of the selected asset.
- An exit game button to leave the game.
- An Undo and Redo button, in case players does a mistake.

#### E. Drawing Mode

Drawing mode will be accessible by using the editor mode selector in the [Toolbar](#c-toolbar). Drawing mode includes a color selector, multiple drawing layers and a frame animator on the right side of the screen.

The game file tree will be accessible on the left of the screen, it can be toggled on or off to to show or hide it.

In the middle, you will be able to draw the assets, the different drawing tool are under it. The different drawing tools are :

- The pencil, to draw the pixels (The pixel size can be changed).
- The eraser, to erase unwanted pixels (The pixel size can be changed).
- The paint bucket, recoloring the clicked pixel and all the other around that has the same color.
- A color picker, allowing to pick a color from a drawn pixel.
- A zone selector, allowing you to draw only in this specific zone, the selector has different modes:

  - Baguette mode : selecting the clicked pixel and all the other around that has the same color.
  - Add mode: add a selected part to the selection zone.
  - sub mode: subtract a selected part from the selection zone.



#### F. Music Mode
Music mode will be accessible by using the editor mode selector in the [Toolbar](#c-toolbar).

The user will be able to choose between many instruments and modify them within a instrument chooser and a music mixer on the right.

the user will creates music by selecting an instrument and click on the piano in the middle part.

The game file tree will be accessible on the left of the screen, it can be toggled on or off to to show or hide it.

#### G. Coding Mode
Coding mode will be accessible by using the editor mode selector in the [Toolbar](#c-toolbar). 

The user will be able to type code in the middle of the screen, they will also select assets and what action they want from the asset and it will add it to the code.

The game file tree will be accessible on the left of the screen, it can be toggled on or off to to show or hide it.

#### H. Mockups & Design Tools

Mockups are produced using Figma, allowing an animated representation of the editor's functionalities.

#### I. Testing/Preview Mode

To test the modifications, the user presses the play button on the toolbar which will throw them back into the game and directly test it out.

#### J. Undo Feature and Autosave

The game will autosave all modifications done to the game. 

If players does a mistake they can undo their mistake by pressing the undo button in the toolbar.

### 3. Mentor System

### 4. Chapter Progression

#### A. Chapter Structure

Each chapter is based on a specific game genre (e.g., platformer, RTS, RPG), and contains:

- A playable, broken game world reflective of that genre
- Game-specific mechanics (e.g., jump physics for platformers, unit logic for RTS)
- Mechanics related to previous chapters
- A set of challenges/problems to fix, customize, or create

#### B. Progression Flow

Chapters are unlocked sequentially to control the learning curve.

As chapters progress, they become more complex, introducing new:

- Parts in the editor tools (e.g., animation in Chapter 2, AI in Chapter 3).
- Gameplay logic challenges.
- Narrative beats connected to the storyline.

#### C. Tutorial Elements

- Each chapter introduces key mechanics gradually via:
  - Short mentor guidance segments.
  - Hands-on repair tasks.
  - Exploratory areas with in-world clues.

- Early chapters (e.g., platformer) are more guided; later chapters give greater freedom and more ambiguous tasks. However if they need assistance, the mentor is still available to guide players.

#### D. Chapter Order

Each chapter introduces unique mechanics related to its featured genre, allowing players to progressively explore the fundamentals of game development across different styles. 

To support gradual learning, certain mechanics and tools learned in earlier chapters are retained and expanded upon in later chapters.

This creates a logical progression, where skills build naturally from one genre to the next. For example:

- The movement and animation logic introduced in the platformer chapter will help prepare the player for unit behavior in an RTS chapter.
- The UI and dialogue tools from an RPG chapter may become useful again in a narrative-heavy final mission.


Because of this cross-chapter skill transfer, chapters must follow a carefully planned order that maintains a coherent difficulty curve and learning flow.

![Logical order]()


#### E. Player Influence Chapter Progression

Depending of the  different choices that the player selected, chapters will be slightly modified, making the game playable multiple times.

### 5. Game Repairs

### 6. Objectives & Freedom 

### 7. Audio and Sound Design

### 8. Saving system

### 9. UX/UI

### 10. 3D/2D


## III. Non Functional Requirement

### 1. Performances


### 2. Technical Requirements

For more information about the technical specificities of the project, please take a look at the [Technical Specification document]()