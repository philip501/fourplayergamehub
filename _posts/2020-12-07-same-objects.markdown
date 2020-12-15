---
layout: games
title: "Same Objects"
category: games
permalink: /docs/games/same_objects/
---

|![](/assets/img/g_same_objects.jpg){:style="text-align: center; border-radius: 8px"}

The goal of this game is to press the button whenever at least four of the same image are visible on the screen. The fastest one to do so will be awarded a point and your button will be highlighted in green (as can be seen in the picture above). In case of this event the other images will be darkened. In case a button is pressed and this requirement is not met you will lose a point, your button will be highlighted in red, and the game continues.

The number of same images is four by default. The parameter describing it is 'max_choices' and can be customised.

Prior to the game the description visible on the screen is the following.
![](/assets/img/d_same_objects.jpg){:style="text-align: center; border-radius: 8px"}
<br>
<br>
list of customisable parameters:
- number_of_rounds
- real_max_counter
- default_schedule_interval
- minimum_schedule_interval
- delta_schedule_interval
- max_choices
