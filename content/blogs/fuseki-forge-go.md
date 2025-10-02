---
title: "Designing Fuseki Forge Go"
date: 2024-05-12
draft: false
description: "How I translated the strategy of Go into a calm, focused mobile experience."
author: "Alexander Büchler"
tags:
  - Product Design
  - SwiftUI
  - UX Research
image: "https://images.unsplash.com/photo-1511512578047-dfb367046420?auto=format&fit=crop&w=1200&q=80"
toc: true
---

When I started Fuseki Forge Go, my goal was to design a tool that treated the ancient game of Go with the same respect modern chess apps give to their players. Most Go apps feel cluttered, visually noisy, or stuck in desktop paradigms. I wanted to blend the meditative pace of the game with a crisp, focused interface.

## Mapping the journey

I began by interviewing a handful of club players about their daily routines. Their feedback revealed that most people review games on the subway or a sofa—places where one-handed navigation matters. That insight shaped the entire layout: primary controls sit at thumb height and complex options hide behind contextual menus.

### Prioritising states over screens

Rather than creating separate screens for playing, reviewing, and learning, I designed one adaptable board component. It reacts to context—showing review tools when you're replaying a match or hint options when you're practising life-and-death problems. This kept the codebase leaner and gave players a consistent experience.

## Crafting a calming palette

To support focus I borrowed colours from traditional Go stones: soft slate for the background, warm off-white for points of interaction, and a single highlight colour that only appears on critical actions. Paired with haptic feedback and subtle animations, the app feels responsive without being distracting.

The project is still evolving, but these foundations have already made playtests smoother and more engaging. Next on the roadmap is integrating SGF import/export so players can jump between the app and their favourite desktop tools.
