---
layout: single
title: "Rock Paper Scissors Advanced (WIP!)"
author:
  avatar: "assets/images/cat.png"
  bio: programmer, game designer, lover of cats
  links:
    - label: "GitHub"
      icon: "fab fa-github"
      url: "https://github.com/fhchu"
    - label: "LinkedIn"
      icon: "fab fa-linkedin"
      url: "https://linkedin.com/in/felix-h-chu"
    - label: "Email"
      icon: "far fa-envelope"
      url: "mailto:felixhchu@gmail.com"
---
![RPS Advanced](/assets/images/rpsadvanced.png) 

## How do you turn Rock Paper Scissors into a strategy game?

The goal of this project is to develop a game with fun one-versus-one "combat" that rewards planning, thinking ahead, and understanding your opponent's behavior. Check out my [dev blog!](https://fchu.substack.com/)

There are two main constraints: first is that there are three inputs: rock, paper, and scissors. The second is there cannot be any progression between games. These two constraints allow new players to quickly learn and understand the game systems and mechanics.

## Game Rules

Players play normal games of Rock Paper Scissors over and over, earning points for winning. After certain thresholds, play is paused and players take turns picking basic upgrades such as "+1 point to Rock" or more complicated upgrades such as "When you win, earn +1 point if you play a different hand than before" or "Your third rock in a row breaks ties". After enough rounds, the game ends and the winner is the player with the most points.

## Paper Playtest Example
![RPS Paper Playtest](/assets/images/rpspaperplaytest.png)

Paper playtests quickly revealed that stopping to reward points and remembering who played what, and when, was cumbersome and taxing, especially after multiple rounds of upgrades. Playable demo [coming soon](https://fchu.itch.io/)!
