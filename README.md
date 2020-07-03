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

## Historical Open Data Creation / Distribution

### Jizo Project [[github](https://github.com/code4history/JizoProject/wiki)]
It is an activity to collect the location and photographs of Jizo, stone Buddhist statues, small wayside shrines in Nara city and make it into an open database.  
It is a project to rediscover the value of Nara's historical and religious assets, which are considered to be denser than the convenience stores in metropolitan cities.  

### Tatebayashi Stone Monuments open database [[github](https://github.com/code4history/TatebayashiStones)]
Some volunteers in Tatebayashi started a project about 50 years ago to collect the data of all stone monuments throughout the city and edited them as a series of five volumes named "Tatebayashi no Nobotoke Meguri".  
We make these volumes into open data and survey how they are now.  
We try to bring a new light to the forgotten achievements of 50 years ago, when valuable achievements were made.  

### Tile mapping of US Army "Japan City Plan" map
We work on the creation of tiled mapping data of the "Japan City Plan", a collection of the University of Texas, which was used by the U.S. military to govern Japan immediately after the Pacific War.  
This map could not be correctly converted into GIS data even if it was processed using the described geodetic and projection systems.  
However, we succeeded in converting the map into GIS data by identifying a method that can be processed by [unraveling the details of how the map was created](https://blog.chizuburari.jp/entry/20130220/1361390148).  

### Open Data Collection of Poems by Himeji Poet Toru Otsuka [[Wikisource](https://ja.wikisource.org/wiki/%E5%A4%A7%E5%A1%9A%E5%BE%B9%E3%83%BB%E3%81%82%E3%81%8D%E8%A9%A9%E9%9B%86)]
We are promoting a collection of poems by Toru Otsuka, a Himeji poet in the early Showa period, as open data at Creative Commons BY-SA 4.0.  
It has been less than 70 years since his death and the copyright of them are not expired yet, but with the permission of the copyright successor, we are proceeding to publish it on CC.  

