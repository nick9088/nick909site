+++ 
draft = false
date = 2022-08-07T14:25:12+02:00
title = "How to remove microsoft edge from windows"
description = "this guide shows how to remove edge from windows (only chromium-based)"
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++
you may know that annoying browser pre-installed on windows.

in this guide i'll show you how to uninstall it.

for this you have to edit your system registry, so follow every step i do.

First, on your keyboard press WIN + R, and then type regedit.exe, and click ok

![step 1](/images/removedge/step1.gif)

Second, navigate to:

HKEY_LOCAL_MACHINE\
 SOFTWARE\
  WOW6432Node\
   Microsoft\
    Windows\
     CurrentVersion\
      Uninstall\
       Microsoft Edge

![step2](/images/removedge/step2.gif)

Then, click on NoRemove and set its value to 0

![step3](/images/removedge/step3.gif)

After that close the system registry and try uninstalling it from control panel or from settings

>if it gives some errors just click ok on them and reboot your pc

thank you for following this guide i hope it works

bye