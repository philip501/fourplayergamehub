---
layout: explorer
title: Local Files
category: explorer
permalink: /docs/explorer/local_files/
---

|![](/assets/img/local_files.jpg){:style="text-align: center; border-radius: 8px"}

This is the directory where your local files are stored on your phone:

{% highlight c %}
/data/data/org.muenz.fourplayer/files/local_files
{% endhighlight %}

You can either navigate to this directory or type it via the search button (see [basic navigation](/docs/explorer/basic_navigation) for more details). Here you can further customise your games.

#### 1. Celebrities

You can copy files into this folder. Please make sure that the names of these files are as described in the docs for [celebrities](/docs/games/celebrities/). When copied multiple files at once make sure to rename the files accordingly.

#### 2. Memory

You cannot directly copy files into this folder. First, you need to create a subfolder (see [basic navigation](/docs/explorer/basic_navigation/#2-new-file--folder)). Each subfolder serves as a collection of a memory set of cards. You can then copy your files into the subfolders. Each subfolder can contain a maximum of 20 cards. Notice that you HAVE to copy 20 images into one subfolder in order for it to be used for the game. You can delete files again as well as subfolders as described in [basic navigation](/docs/explorer/basic_navigation/).

In order to see what the intended subfolder structure looks like you can navigate to

{% highlight c %}
/data/data/org.muenz.fourplayer/files/app/Memory
/data/data/org.muenz.fourplayer/files/app/Memory/Emojis
{% endhighlight %}

#### 3. SameObjectsPics

You cannot directly copy files into this folder. First, first you need to create a subfolder (see [basic navigation](/docs/explorer/basic_navigation/#2-new-file--folder)). Each subfolder can contain a maximum of 6 cards. Notice that you HAVE to copy 6 images into one subfolder in order for it to be used for the game. You can delete files again as well as subfolders as described in [basic navigation](/docs/explorer/basic_navigation/).

In order to see what the intended subfolder structure looks like you can navigate to

{% highlight c %}
/data/data/org.muenz.fourplayer/files/app/SameObjectsPics
/data/data/org.muenz.fourplayer/files/app/SameObjectsPics/memes
{% endhighlight %}

#### 4. Slotcar

Here you can create tracks. To do so press "MAKE NEW TRACK" (see picture below). For further information about how to create a track see the docs of [slotcar](/docs/games/slotcar/). A new track will create a file both in the "Tracks" and the "TracksCarPos" subfolder. If you want to delete a track again make sure you delete both of these files. Be careful when deleting files from the "TracksCarPos" subfolder. If a custom track is chosen for the slotcar game without having a corresponding \_car\_pos.csv file, this will lead to an error and the game will probably crash.

|![](/assets/img/slotcar_local.jpg){:style="text-align: center; border-radius: 8px"}

In order to see what the subfolder structure and corresponding files look like you can navigate to 

{% highlight c %}
/data/data/org.muenz.fourplayer/files/app/SlotCar
/data/data/org.muenz.fourplayer/files/app/SlotCar/Tracks
/data/data/org.muenz.fourplayer/files/app/SlotCar/TracksCarPos
{% endhighlight %}

#### 5. Logs

Here the (error) logs of this app are stored. See [logs](/docs/explorer/logs/) for further information.
