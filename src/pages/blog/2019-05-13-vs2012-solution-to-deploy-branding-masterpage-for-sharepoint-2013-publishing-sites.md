---
templateKey: blog-post
title: >-
  VS2012 solution to deploy branding masterpage for Sharepoint 2013 Publishing
  Sites
date: 2019-05-13T06:18:57.497Z
description: >-
  First of all, thanks to Kyle Schaeffer's awesome responsive starter SP2013
  masterpage project, see here:
  http://kyleschaeffer.com/sharepoint/sp-blueprint/
featuredpost: true
featuredimage: /img/chemex.jpg
tags:
  - Sharepoint
---
I've taken Kyle's package and made a VS2012 solution that you can use to deploy to a Sharepoint 2013 Publishing Site.

This is a Site scoped feature so make sure your feature receiver is Site scope not Web scoped (otherwise you will get a "Object reference" error when you try to deploy.

![Sharepoint 2016](/img/screen1.png "VS2012 Masterpage")

This is how it should look when you deploy it.



![Deploying masterpage](/img/screen2.png "Deploying masterpage")

I've not added a feature receiver to automatically switch the site masterpage to this one after you deploy. I simply used the UI to do it, ie. Site settings > Masterpage.
