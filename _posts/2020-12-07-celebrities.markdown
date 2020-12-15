---
layout: games
title: "Celebrities"
category: games
permalink: /docs/games/celebrities/
---

|![]({{site.baseurl|append:"/assets/img/g_celebrities1.jpg"}}){:style="text-align: center; border-radius: 8px"}

The goal of this game is to press the button whenever the name matches the image displayed on the screen. The fastest one to do so will be awarded a point and your button will be highlighted in green (as can be seen in the picture above). In case a button is pressed and the name does not match the image you will lose a point and your button will be highlighted in red.

By default there are eight different celebrities to be recognised. You can add more to your local files which will be also considered for the game. Please make sure that tha name of the added file is of the format 'NAME_NUMBER' where 'NAME' is the name of the person with all spaces replaced by '\_' and 'NUMBER' is a natural number (including zero). If you add multiple images of the same person make sure that you chose '0' as the number for the first, '1' as the number for your second, and so on. How to add a file to your local files is explained in the [docs]({{site.baseurl|append:"/docs/explorer/basic_navigation/"}}).

By default you have three seconds to recognise whether the image and the matches. This and other parameters (see list of customisable parameters below) can be customised.

Prior to the game the description visible on the screen is the following.
![]({{site.baseurl|append:"/assets/img/d_celebrities.jpg"}}){:style="text-align: center; border-radius: 8px"}
<br>
<br>
list of customisable parameters:
- number_of_rounds
- max_counter
- min_counter
- default_schedule_interval
