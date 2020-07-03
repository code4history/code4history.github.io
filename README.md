---
layout: default
permalink: /index.html
link_ja: /index_ja.html
---

# Code for History Activities

## Maplat
![MaplatMobile](Maplat-iPhone.png)
Maplat is a cool historical map and pictorial map viewer and is the only technology in the world that allows you to overlay and switch over any maps with keeping topological homeomorphism and without distorting it (Japan Patent No. 6684776). You can use it to walk around town or study history without spoiling the beauty of histrical maps or pictorial maps.  
For more detail information, please see [this pdf](maplat_flyer.pdf). 

Maplat has several implementations for its purpose.

### Maplat UI [[github](https://github.com/code4history/Maplat/wiki)] [[npm](https://www.npmjs.com/package/@maplat/ui)]
Maplat UI is Maplat with default UI.  
If you put the configuration files on a web server, it will run without any server-side logic.  
There is also an client-side API, so it can work with server-side logic.

### Maplat Editor [[github](https://github.com/code4history/MaplatEditor/wiki)]
MaplatEditor is an editor for creating map data that works with the Maplat series.  
As a desktop application, it runs on both Intel Mac and Win 64.  
Installers are distributed in the site.  

### Maplat Core [[github](https://github.com/code4history/MaplatCore/wiki)] [[npm](https://www.npmjs.com/package/@maplat/core)]
Maplat Core is API only version of Maplat.  
All behaviors can be freely defined through the API.  

### Maplat Tin [[github](https://github.com/code4history/MaplatTin/wiki)] [[npm](https://www.npmjs.com/package/@maplat/tin)]
It is a library for generating the Constrained Triangulated Irregular Network, which is the heart of the operating principle of Maplet.  

### Maplat Android [[github](https://github.com/code4history/MaplatAndroid)]
This is the Kotlin/Java library for developing Android apps using Maplat.  

### Maplat iOS [[github](https://github.com/code4history/MaplatiOS)]
This is the Swift/Objective-C library for developing iOS apps using Maplat.  

