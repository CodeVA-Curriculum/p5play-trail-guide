---
title: Make an "Asteroids" Game
nodes:
    - ./concepts/game-setup.md
authors: Jon Stapleton
description: Lorem ipsum dolor sit amet
difficulty: 3
icon: 
---

    - intro:
        - concepts/game-setup.md
        - concepts/calling-functions.md
        - applications/sprite-basics.md
    - animations:
        - $intro
        - applications/sprite-images.md
        - ./asteroids-sprites.md
        - applications/sprite-animations.md
        - ./asteroids-basics-animations.md
    - variables:
        - $intro
        - concepts/variables-types.md
        - concepts/manipulating-variables.md
        - ./asteroids-basic-score
        - concepts/randomization.md
        - applications/sprite-groups.md
        - ./asteroids-groups.md
    - player-input:
        - $variables
        - applications/mouse-position-input.md
        - applications/keyboard-click-input.md
        - applications/sprite-movement.md
        - ./asteroids-movement.md
    - scene:
        - $player-input
        - ./asteroids-projectiles.md
        - ./asteroids-progression.md
    - physics:
        - $scene
        - applications/sprite-physics-basics.md
        - ./asteroid-physics.md
        - applications/sprite-collisions.md
        - ./asteroids-collisions.md