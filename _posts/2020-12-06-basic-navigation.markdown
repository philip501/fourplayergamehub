---
layout: explorer
title: Basic Navigation
category: explorer
permalink: /docs/explorer/basic_navigation/
---


#### 1. Basics

|![]({{site.baseurl|append:"/assets/img/explorer.jpg"}}){:style="text-align: center; border-radius: 8px"}

By default the entrypoint to the built-in explorer is:

{% highlight c %}
/data/data/org.muenz.fourplayer/files/app
{% endhighlight %}

This is the path where all the files are stored on your android phone. Your current path is always displayed on the top next to the for symbols as can be seen in the picture above. The functionalities of the symbols are
<table style="border: none; background-color: white">
  <tr style="border: none; background-color: white; list-style: none">
    <td style="border: none; background-color: white; list-style: none; width: 20%">
      <img src="/assets/img/icons/home.png" alt="" style="text-align: center">
    </td>
    <td style="border: none; background-color: white; list-style: none">
      The home button will always redirect you back to the entrypoint-path from above.
    </td>
  </tr>
  <tr style="border: none; background-color: white; list-style: none">
    <td style="border: none; background-color: white; list-style: none; width: 20%">
      <img src="/assets/img/icons/sdcard.png" alt="" style="text-align: center">
    </td>
    <td style="border: none; background-color: white; list-style: none">
      Pressing this button will direct you to the path of your SD card. The permission to access your SD card has to be granted first. You can manage your permissions in your phone's Settings > Apps > 4 Player Game Hub > Permissions. Otherwise you will be directed to an (intended) error screen. In this case tapping the screen will get you back to the explorer.
    </td>
  </tr>
  <tr style="border: none; background-color: white; list-style: none">
    <td style="border: none; background-color: white; list-style: none; width: 20%">
      <img src="/assets/img/icons/search.png" alt="" style="text-align: center">
    </td>
    <td style="border: none; background-color: white; list-style: none">
      Pressing the search button will enable you to type in a custom path in place of the current directory. Pressing this button again will direct you to the path of your choice. If the path is invalid you will be directed to an (intended) error screen. In this case tapping the screen will get you back to the explorer.
    </td>
  </tr>
  <tr style="border: none; background-color: white; list-style: none">
    <td style="border: none; background-color: white; list-style: none; width: 20%">
      <img src="/assets/img/icons/logo.png" alt="" style="text-align: center">
    </td>
    <td style="border: none; background-color: white; list-style: none">
      This button will redirect you back to the game.
    </td>
  </tr>
</table>

Other than those symbols clickable objects are folders and .png, .jpg and .txt files. Tapping on a folder opens the respective path, <span style="color: red">the '../' folder navigates you to the parent folder</span>. When pressing a file of one of those types a file viewer opens displaying it. At the bottom of this screen is a return button leading back to the explorer and a copy button (see picture below). For the usage of this copy option see [Local Files]({{site.baseurl|append:"/docs/explorer/local_files"}}).

|![]({{site.baseurl|append:"/assets/img/myviewer.jpg"}}){:style="text-align: center; border-radius: 8px"}

You can copy multiple files at the same time. When doing so the 'SD card' button will get replaced by the following with which you can look at your currently stored files you intend to copy.

<table style="border: none; background-color: white">
  <tr style="border: none; background-color: white; list-style: none">
    <td style="border: none; background-color: white; list-style: none; width: 20%">
      <img src="/assets/img/icons/copy.png" alt="" style="text-align: center">
    </td>
    <td style="border: none; background-color: white; list-style: none">
      When this button is pressed your currently stored files you intend to copy are displayed on your screen. In order to visualize that you are viewing these files the colours of this button get inversed (see next).
    </td>
  </tr>
  <tr style="border: none; background-color: white; list-style: none">
    <td style="border: none; background-color: white; list-style: none; width: 20%">
      <img src="/assets/img/icons/copy_inv.png" alt="" style="text-align: center">
    </td>
    <td style="border: none; background-color: white; list-style: none">
      This button indicates that you are viewing your currently stored files you intend to copy. Pressing it results in getting back to the explorer at your current path and in inverting its colour to the original one.
    </td>
  </tr>
</table>

When being pressed your screen will look as follows.

|![]({{site.baseurl|append:"/assets/img/copy.jpg"}}){:style="text-align: center; border-radius: 8px"}

If you copied a file by accident you can remove it again by pressing the trash bin icon on the right side of the according file.

#### 2. New File / Folder

There are predefined places where you can create new subfolders and where you can paste your copied files to (see [local files]({{site.baseurl|append:"/docs/explorer/local_files/"}})). When available the button for these actions is always displayed at the very bottom of the current folder's files. The option for creating a new subfolder is displayed by the "+" button (see pictures below). When pressed a textfield pops up where you can type in the name of the new subfolder. Pressing "create" will then create the new subfolder with the name of your choice.

|![]({{site.baseurl|append:"/assets/img/new_folder.jpg"}}){:style="text-align: center; border-radius: 8px; margin-bottom: 10px"}![]({{site.baseurl|append:"/assets/img/new_folder_pop_up.jpg"}}){:style="text-align: center; border-radius: 8px; margin-bottom: 10px"}![]({{site.baseurl|append:"/assets/img/new_folder_created.jpg"}}){:style="text-align: center; border-radius: 8px"}

Into these created subfolders you can copy your files. When navigating to one of these at the very bottom of the files a button is displayed with name "COPY INTO THIS FOLDER" (see pictures below). Pressing this button results in a textfield to open up. Make sure you take the description into account when chosing a name (see also [local files]({{site.baseurl|append:"/docs/explorer/local_files/"}})). Press "copy" and the new file will show up in your folder unless the name already exists. In this case nothing happens and the folder will get displayed as it was before.

|![]({{site.baseurl|append:"/assets/img/copy_into.jpg"}}){:style="text-align: center; border-radius: 8px; margin-bottom: 10px"}![]({{site.baseurl|append:"/assets/img/copy_into_name.jpg"}}){:style="text-align: center; border-radius: 8px; margin-bottom: 10px"}![]({{site.baseurl|append:"/assets/img/copy_into_new.jpg"}}){:style="text-align: center; border-radius: 8px; margin-bottom: 10px"}

The option to name the file you intend to copy into this folder will only pop up when you have only one file currently stored. Otherwise all the files will get copied into this folder with their original name. Any file which would cause a name violation will get ignored in this process.

You can rename files and directories by holding the corresponding button for at least one second. Releasing the button will again open up a textfield where you can type in a new name.
