# Airfoile

A daily guessing game for NACA 4-digit airfoils. You see the shape; guess the `MPXX` code in 6 tries.

- **M** – max camber, % chord
- **P** – position of max camber, tenths of chord
- **XX** – max thickness, % chord (symmetric sections are `00XX`)

Each digit is marked as right (■), off by one (bold border), or with an arrow saying go higher / lower. Your last guess is overlaid as a dashed outline.

Play: https://orangebannana.github.io/airfoile/

Single static `index.html`, no build step.
