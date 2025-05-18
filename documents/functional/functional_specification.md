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
    - [3. Mentor System](#3-mentor-system)
    - [4. Chapter Progression](#4-chapter-progression)
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
- 
- **Regular players** That are curious of how to do a game.

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


### 3. Mentor System

### 4. Chapter Progression

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