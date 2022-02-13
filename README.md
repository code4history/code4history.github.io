---
layout: default
permalink: /index.html
link_ja: /index_ja.html
---

# Code for History Activities

## Maplat
![MaplatMobile](Maplat-iPhone.png)
Maplat is a cool historical map and pictorial map viewer and is the only technology in the world that allows you to overlay and switch over any maps with keeping topological homeomorphism and without distorting it (Japan Patent No. 6684776). You can use it to walk around town or study history without spoiling the beauty of histrical maps or pictorial maps.  
For more detail information, please see these pdfs:  
* [Business side info](Introduction_of_Maplat_solution.pdf)
* [Technical detailed info](maplat_flyer.pdf)

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

### Operation of Maplat-applied sites
We run several historical city map web sites for street walking for both Maplat demonstration and hobbyist profit.  
* [Maplat Nara](https://s.maplat.jp/r/naramap/)
* [Maplat Tatebayashi](https://s.maplat.jp/r/tatebayashimap/)
* [Maplat Aizu Wakamatsu](https://s.maplat.jp/r/aizumap/)
* [Maplat Iwaki](https://s.maplat.jp/r/iwakimap/)
* [Maplat Tokyo Chuo-ku](https://s.maplat.jp/r/chuokumap/)

## Historical Open Data Creation / Distribution

### Jizo Project [[github](https://github.com/code4history/JizoProject/wiki)]
It is an activity to collect the location and photographs of Jizo, stone Buddhist statues, small wayside shrines in Nara city and make it into an open database.  
It is a project to rediscover the value of Nara's historical and religious assets, which are considered to be denser than the convenience stores in metropolitan cities.  

### Tatebayashi Stone Monuments open database [[github](https://github.com/code4history/TatebayashiStones)]
Some volunteers in Tatebayashi started a project about 50 years ago to collect the data of all stone monuments throughout the city and edited them as a series of five volumes named "Tatebayashi no Nobotoke Meguri".  
We make these volumes into open data and survey how they are now.  
We try to bring a new light to the forgotten achievements of 50 years ago, when valuable achievements were made.  

### Tile mapping of US Army "Japan City Plan" map [[github](https://github.com/code4history/TatebayashiStones)]
We work on the creation of tiled mapping data of the "Japan City Plan", a collection of the University of Texas, which was used by the U.S. military to govern Japan immediately after the Pacific War.  
This map could not be correctly converted into GIS data even if it was processed using the described geodetic and projection systems.  
However, we succeeded in converting the map into GIS data by identifying a method that can be processed by [unraveling the details of how the map was created](https://blog.chizuburari.jp/entry/20130220/1361390148).  

### Open Data Collection of Poems by Himeji Poet Toru Otsuka [[Wikisource](https://ja.wikisource.org/wiki/%E5%A4%A7%E5%A1%9A%E5%BE%B9%E3%83%BB%E3%81%82%E3%81%8D%E8%A9%A9%E9%9B%86)]
We are promoting a collection of poems by Toru Otsuka, a Himeji poet in the early Showa period, as open data at Creative Commons BY-SA 4.0.  
It has been less than 70 years since his death and the copyright of them are not expired yet, but with the permission of the copyright successor, we are proceeding to publish it on CC.  

### Writing Wikipedia Articles on Historic Sites, Events, etc. [[List](https://ja.wikipedia.org/wiki/%E5%88%A9%E7%94%A8%E8%80%85:Kochizufan)]
We are working to dig up forgotten historical sites and events and turn them into Wikipedia articles for future.  
As a feature, we provide uniqueness to make articles by investigating not only literature but also historical maps and geographical data.  
Leading articles:"[Kikai-ga-Shima (Nara)](https://ja.wikipedia.org/wiki/%E9%AC%BC%E7%95%8C%E3%83%B6%E5%B3%B6_(%E5%A5%88%E8%89%AF%E5%B8%82))","[Shogan-in temple](https://ja.wikipedia.org/wiki/%E5%8B%9D%E9%A1%98%E9%99%A2)","[Playhouse in Kawarado](https://ja.wikipedia.org/wiki/%E7%93%A6%E5%A0%82%E3%81%AE%E8%8A%9D%E5%B1%85%E5%B0%8F%E5%B1%8B)","[Yashima Mausoleum](https://ja.wikipedia.org/wiki/%E5%85%AB%E5%B3%B6%E9%99%B5)","[Fukudera temple](https://ja.wikipedia.org/wiki/%E7%A6%8F%E5%AF%BA)","[Shimada shrine](https://ja.wikipedia.org/wiki/%E5%B6%8B%E7%94%B0%E7%A5%9E%E7%A4%BE)","[Kodo Murai](https://ja.wikipedia.org/wiki/%E6%9D%91%E4%BA%95%E5%8F%A4%E9%81%93)","[Kasuga-utsushi](https://ja.wikipedia.org/wiki/%E6%98%A5%E6%97%A5%E7%A7%BB%E3%81%97)","[Belief of Gozu-Tenno in Tatebayashi](https://ja.wikipedia.org/wiki/%E9%A4%A8%E6%9E%97%E3%81%AE%E7%89%9B%E9%A0%AD%E5%A4%A9%E7%8E%8B%E4%BF%A1%E4%BB%B0)","[Obiki Inari shrine](https://ja.wikipedia.org/wiki/%E5%B0%BE%E6%9B%B3%E7%A8%B2%E8%8D%B7%E7%A5%9E%E7%A4%BE)","[Tea Granny](https://ja.wikipedia.org/wiki/%E3%81%8A%E8%8C%B6%E3%81%AE%E3%81%8A%E3%81%B0%E3%81%82%E3%81%95%E3%82%93)","[Shigemitsu Kitao](https://ja.wikipedia.org/wiki/%E5%8C%97%E5%B0%BE%E9%87%8D%E5%85%89)","[Toyoko Osawa](https://ja.wikipedia.org/wiki/%E5%A4%A7%E6%B2%A2%E8%B1%8A%E5%AD%90)","[Toru Otsuka (Poet)](https://ja.wikipedia.org/wiki/%E5%A4%A7%E5%A1%9A%E5%BE%B9_(%E8%A9%A9%E4%BA%BA))"  

## Support for activities of other organizations
Including activities before we call ourselves Code for History.  
Although we are not in the main business, we can help you to the extent possible, if we can cooperate with you through know-how utilizing old maps, chorography surveys, and library references, including consultation on how to apply Maplat.  
Please feel free to contact us.  

### Assistance in Locating Ainu Names in Hokkaido
In the production of [historical place name data by National Institutes for the Humanities](https://www.nihu.jp/ja/publication/source_map), we provided cooperation by providing location identification technology for places where the location could not be identified due to a large amount of displacement and distortion in the old version of the topographic map when the location was identified from the topographic map with a scale of 1: 50,000.  

### Cooperation with the "Hiroshima Archive"
We cooperated with Professor [Hidenori Watanabe](https://ja.wikipedia.org/wiki/%E6%B8%A1%E9%82%89%E8%8B%B1%E5%BE%B3) and his staff in providing [an open source library that reads topographical data from the Geospatial Information Authority of Japan](https://github.com/tilemapjp/Cesium-JapanGSI) to "[Hiroshima Archive](http://hiroshima.mapping.jp/index_en.html)" a site that preserves memories and testimonies of the Hiroshima atomic bomb.  

### Cooperation and support for Maplat applications
We helped with the implementation of Maplat applications which are not operated by Code for History.  
Some of them cannot be published, but the following are some examples that can be published.  
* Supporting the application of Maplat (Maplat Android, Maplat iOS) to the "[Sightseeing cloud application](https://www.machi-pla.com/apps/)" of the Machidukuri-Platform Co., Ltd.
* Support for application of Maplat (Maplat UI) to "[Higashinari City Walk App](https://higashinari-walk.fun/)" in Higashinari Ward, Osaka City

### Investigation of the origin of great figures and historic sites
There are many projects that cannot be opened to the public, but we have provided support mainly for historical maps, chorographies, and library surveys for great figures and historic sites.  

## What we will do in the future

### GIS Open Data for Castle Structure
We would like to start with Tatebayashi Castle, then next are Himeji Castle, Aizu-Wakamatsu Castle, Iwaki-Taira Castle, Kanazawa Castle and Sendai-Aoba Castle.  
First of all, we will create GIS data of defensive structures (Castle walls, moats, gates, etc.), and after that, we would like to work on the area polygon of town names in the castle town.  
As a similar initiative, we plan to expand it to include data on the Naramachi area in Nara.  

### Historical Koaza position open data
The Center for Open Data in the Humanities is providing [current Koaza position open data](http://geoshape.ex.nii.ac.jp/ka/) including the polygon boundaries.  
We hope to extend it to include historical Koaza.  
It may not be possible to include the polygon boundary, but I would like to start with Tatebayashi, even if it is just a representative point.  

### Provision of open data sightseeing POI
We would like to provide POI data on historical sites that can be used freely for sightseeing applications in various places.  
As a feature, we would like to make it unique, including unique contents such as "[Kikaigashima](https://ja.wikipedia.org/wiki/%E9%AC%BC%E7%95%8C%E3%83%B6%E5%B3%B6_(%E5%A5%88%E8%89%AF%E5%B8%82))" and "[Tea Granny](https://ja.wikipedia.org/wiki/%E3%81%8A%E8%8C%B6%E3%81%AE%E3%81%8A%E3%81%B0%E3%81%82%E3%81%95%E3%82%93)".  
We would like to start with Tatebayashi, Nara, Himeji, Aizu-Wakamatsu, Iwaki, Kanazawa, Sendai and Nobeoka.  

