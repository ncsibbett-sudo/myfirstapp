# Product Requirements Document (PRD)

**Title:** Penguin Surf Dash  
**Version:** 1.0  
**Date:** September 12, 2025

## 1. Overview

### Summary
Penguin Surf Dash is an endless runner game inspired by Temple Run, where the player controls a penguin riding a surfboard through an icy obstacle course. The player uses arrow keys to make quick decisions—jumping, sliding, and dodging obstacles—while racing to achieve the highest score possible.

### Goals
- Deliver a fast-paced, addictive endless runner
- Keep controls intuitive and responsive
- Use a unique penguin-and-surfboard theme to differentiate from similar games

## 2. Core Gameplay

### Controls
- **Up Arrow** → Jump over obstacles (e.g., ice cracks, logs, small icebergs)
- **Down Arrow** → Slide under obstacles (e.g., icicles, low ice bridges)
- **Left Arrow** → Turn/move left at junctions or dodge side obstacles
- **Right Arrow** → Turn/move right at junctions or dodge side obstacles

### Game Loop
- Player starts at the top of an icy slope with the penguin already in motion
- Obstacles and pathways are procedurally generated to increase replayability
- The penguin accelerates gradually, making reaction times shorter as the run continues
- The run ends if the penguin crashes into an obstacle or fails to turn in time

### Scoring System
- **Distance traveled:** Primary score metric
- **Collectibles:** Fish tokens scattered on the path give bonus points
- **Combos:** Successfully chaining multiple jumps/slides without failure earns multipliers

## 3. Environment & Aesthetic

### Theme
- Frozen arctic environment with icebergs, glaciers, and icy caverns
- Dynamic background changes: icy cliffs, frozen oceans, aurora skies

### Obstacles
- Ice cracks (jump over)
- Icicles/ice stalactites (slide under)
- Ice blocks or fallen logs (jump)
- Narrow bridges / sharp turns (left or right)
- Moving seals or walruses (dodge)

### Visual Style
- Cartoonish, playful art with bright colors
- Penguin has a vibrant surfboard with customizable skins (cosmetic unlocks)

## 4. Features

### Core Features
- Endless procedural map generation
- Simple arrow-key controls
- Increasing speed/difficulty over time
- Score and leaderboard system

### Optional/Stretch Features
- Power-ups (e.g., speed boost, invincibility shield, magnet for fish)
- Daily challenges/quests
- Character customization (different surfboard designs, outfits)
- Multiplayer leaderboards or head-to-head racing

## 5. Technical Requirements

### Platform
- PC (keyboard required for arrow controls)
- Future expansion to mobile (swipe gestures replacing arrow keys)

### Engine
- Unity or Unreal Engine recommended for 3D endless runner functionality

### Performance
- Target 60 FPS smooth gameplay
- Quick input responsiveness (max input lag <100ms)

## 6. Success Metrics

- **Engagement:** Average session length > 5 minutes
- **Retention:** 30% day-7 player return rate
- **Virality:** Players share high scores or compete with friends
- **Revenue Potential** (if monetized): Cosmetic skins and optional ad-based rewards