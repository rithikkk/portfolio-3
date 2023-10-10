---
title: "Alien Attack - MacEwan University Project"
date: "2023-01-01"
image: "images/portfolio/item2.png"  
categories: ["Game", "WebGL", "Design", "JavaScript", "Python"]
description: "Alien Attack: A thrilling game where players fend off waves of alien invaders."
draft: false
project_info:
- name: "Client"
  icon: "fas fa-user"
  content: "MacEwan University"
- name: "Project Type"
  icon: "fas fa-seedling"
  content: "Game Development"
- name: "Technologies"
  icon: "fas fa-cogs"
  content: "WebGL, Python, JavaScript"
- name: "Project Link"
  icon: "fas fa-link"
  content: "https://github.com/Ryan-at-git/CMPT370_GroupProject"
---

## Introduction

Alien Attack is a game developed by our team at MacEwan University, where players control a jet and must shoot down incoming aliens to survive. The game includes power-ups that can help the player by doubling their bullets. However, if an alien collides with the player's jet, the player's health decreases by 20 points. The player starts with a maximum health of 100 points, and if their health reaches 0, the game is over.

Developing this game presented several challenges, including finding the right models that could render correctly in the game engine. We also experienced performance issues when spawning too many enemies, which caused lag, and difficulties with lighting on different textures for models.

## Methods

The game's functionality comprises several components:

1. **Terrain**: The game's environment features an earth-like terrain, rendered using texture blending techniques to achieve a realistic look.
2. **Main Player**: Players control a detailed jet model, allowing them to navigate the 3D space and engage with the alien enemies.
3. **Static Interactable Objects**: Power-ups, such as the double-bullet upgrade, are scattered throughout the environment.
4. **NPCs**: Alien enemies spawn infinitely, presenting a continuous challenge for players.
5. **Change of View**: Players can switch between first-person and a top-down view perspective.

## Theory

In Alien Attack, we applied various computer graphics theories and principles. This enhanced visual appeal and engagement. Here's a breakdown:

- **Modeling and Viewing**: We used 3D models for the player-controlled jet, alien enemies, and power-ups. These were created with 3D modeling tools and imported into the game engine. Camera controls allow players to switch views, enriching the gameplay.
  
- **Shading and Light Models**: Shading and light models give the game a visually appealing look. We factored in ambient, diffuse, and specular lighting components for model details. Strategically placed lights illuminate the environment, adding depth and realism.
  
- **Texture**: We applied textures to models and terrain for enhanced visuals. The 2D images mapped onto 3D models give details to the jet, aliens, and power-ups. The earth-like terrain is textured and rotates to present a realistic environment.
  
- **Collision Detection**: Crucial for game mechanics. It determines interactions like jet-alien collisions and power-up collections. We employed sphere colliders for accurate and efficient collision detection.

## Implementation Details

Our team's unique contributions include:

- **Infinite Spawning Algorithm**: Designed for a continuous challenge. It randomizes alien positions, ensuring each game session remains unique.

- **Jet Model**: We picked a model and texture balancing aesthetics with performance.

- **Earth Terrain**: Simulated earth-like terrain using a rotating earth texture. It adds depth to the gameplay.

## Analysis & Discussion

Developing Alien Attack was both challenging and rewarding. We successfully blended player-controlled jets, alien invaders, and dynamic environments. The project offered insights into game development intricacies: optimizing performance, designing visuals, and gameplay balance. 

We faced challenges like game lag and rendering complex models but tackled them through optimization. For future enhancements, we consider diverse power-ups, optimized models, varied enemy types, and a broader game world for a richer experience.



