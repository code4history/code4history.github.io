---
layout: default.ja
permalink: /index_ja.html
link_en: /
---

# Code for Historyの活動

## Maplat
![MaplatMobile](Maplat-iPhone.png)
Maplatはクールな古地図と絵地図ビューアで、トポロジー的な同形性を維持しつつ、描画を歪めることなくあらゆる地図を重ね合わせたり切り替えたりできる世界で唯一の技術です(特許第6684776号)。美しさが全く損なわれない古地図や絵地図を使って、町を散策したり、歴史の勉強に使ったりできます。  
詳しくは[こちらのpdf](maplat_flyer_ja.pdf)をご覧ください。  

Maplatには目的別にいくつかの実装があります。

### Maplat UI [[github](https://github.com/code4history/Maplat/wiki)] [[npm](https://www.npmjs.com/package/@maplat/ui)]  
Maplat UIはデフォルトのユーザインタフェースのついたMaplatです。  
設定ファイルをWebサーバに設置すれば、サーバサイドで動くロジックは全くなしで動作します。  
クライアントサイドAPIも存在しますので、サーバサイドロジックと連携することも可能です。  

### Maplat Editor [[github](https://github.com/code4history/MaplatEditor/wiki)]  
MaplatEditorはMaplatシリーズで動作する地図データを作成するためのエディタです。  
デスクトップアプリとして、Intel MacとWin64で動作します。  
インストーラを配布しています。  

### Maplat Core [[github](https://github.com/code4history/MaplatCore/wiki)] [[npm](https://www.npmjs.com/package/@maplat/core)]  
Maplat CoreはAPI操作のみを持つMaplatです。  
全てのふるまいがAPIを通じて自由に定義できます。  

### Maplat Tin [[github](https://github.com/code4history/MaplatTin/wiki)] [[npm](https://www.npmjs.com/package/@maplat/tin)]
Maplatの動作原理の心臓部といえる、制約付き不整三角網(Constrained Triangulated Irregular Network)を生成するライブラリです。  

### Maplat Android [[github](https://github.com/code4history/MaplatAndroid)]
Maplatを使ったAndroidアプリを開発するためのKotlin/Javaライブラリです。  

### Maplat iOS [[github](https://github.com/code4history/MaplatiOS)]
Maplatを使ったiOSアプリを開発するためのSwift/Objective-Cライブラリです。  

### Maplat適用サイトの自主運営
Maplatの適用例デモと趣味的な実益を兼ねて、いくつかの街の街歩き用古地図サイトを運営しています。
* [ぷらっと奈良](https://s.maplat.jp/r/naramap/)
* [ぷらっと館林](https://s.maplat.jp/r/tatebayashimap/)
* [ぷらっと会津若松](https://s.maplat.jp/r/aizumap/)
* [ぷらっといわき](https://s.maplat.jp/r/iwakimap/)
* [ぷらっと東京中央区](https://s.maplat.jp/r/chuokumap/)

## 歴史的オープンデータの作成配布

### 地蔵プロジェクト [[github](https://github.com/code4history/JizoProject/wiki)]
奈良市内の地蔵、石仏、小祠などの位置と写真を集約しオープンデータベース化する活動です。  
無数にあり都会のコンビニエンスストアより密度が高いと思われる奈良の歴史的、信仰的資産の価値の再発見を試みるプロジェクトです。  

### 館林石造史跡オープンデータベース [[github](https://github.com/code4history/TatebayashiStones)]
館林で約50年前に有志が始めた市内全域での石造史跡の悉皆調査「たてばやしの野仏巡り」シリーズ全5巻をオープンデータ化するとともに、現況調査まで行うプロジェクトです。  
50年前に価値ある成果が残されているにもかかわらず、忘れ去られている成果に再度光を当てます。  

### 米軍Japan City Plan地図のタイル地図化 [[github](https://github.com/code4history/jcp_maps)]
テキサス大学のコレクションである、太平洋戦争直後に米軍が日本統治に利用したJapan City Plan地図のタイル地図データ化に取り組みます。  
この地図は記載されている測地系、投影系で処理しても正しくGISデータ化できませんでしたが、[作られた時の経緯を紐解くことで処理できる方法を特定](https://blog.chizuburari.jp/entry/20130220/1361390148)し、GISデータ化に成功しました。

### 姫路の詩人大塚徹の詩集オープンデータ化 [[Wikisource](https://ja.wikisource.org/wiki/%E5%A4%A7%E5%A1%9A%E5%BE%B9%E3%83%BB%E3%81%82%E3%81%8D%E8%A9%A9%E9%9B%86)]
昭和初期の姫路の詩人、大塚徹の詩集のCreative Commons BY-SA 4.0でのオープンデータ化を進めています。  
死後70年経っておらず著作権の消滅前ですが、著作権継承者の了承を得てCCにて公開を進めています。  

### 歴史的史跡、事象などのWikipedia記事執筆 [[一覧](https://ja.wikipedia.org/wiki/%E5%88%A9%E7%94%A8%E8%80%85:Kochizufan)]
忘れ去られた歴史的史跡や事象などを掘り起こし、Wikipedia記事として未来に残す活動をしています。  
特色として、文献だけでなく、古地図や地理的データまで調査して記事を起こす独自性を提供しています。  
代表的な記事：「[鬼界ヶ島 (奈良市)](https://ja.wikipedia.org/wiki/%E9%AC%BC%E7%95%8C%E3%83%B6%E5%B3%B6_(%E5%A5%88%E8%89%AF%E5%B8%82))」「[勝願院](https://ja.wikipedia.org/wiki/%E5%8B%9D%E9%A1%98%E9%99%A2)」「[瓦堂の芝居小屋](https://ja.wikipedia.org/wiki/%E7%93%A6%E5%A0%82%E3%81%AE%E8%8A%9D%E5%B1%85%E5%B0%8F%E5%B1%8B)」「[八島陵](https://ja.wikipedia.org/wiki/%E5%85%AB%E5%B3%B6%E9%99%B5)」「[福寺](https://ja.wikipedia.org/wiki/%E7%A6%8F%E5%AF%BA)」「[嶋田神社](https://ja.wikipedia.org/wiki/%E5%B6%8B%E7%94%B0%E7%A5%9E%E7%A4%BE)」「[村井古道](https://ja.wikipedia.org/wiki/%E6%9D%91%E4%BA%95%E5%8F%A4%E9%81%93)」「[春日移し](https://ja.wikipedia.org/wiki/%E6%98%A5%E6%97%A5%E7%A7%BB%E3%81%97)」「[館林の牛頭天王信仰](https://ja.wikipedia.org/wiki/%E9%A4%A8%E6%9E%97%E3%81%AE%E7%89%9B%E9%A0%AD%E5%A4%A9%E7%8E%8B%E4%BF%A1%E4%BB%B0)」「[尾曳稲荷神社](https://ja.wikipedia.org/wiki/%E5%B0%BE%E6%9B%B3%E7%A8%B2%E8%8D%B7%E7%A5%9E%E7%A4%BE)」「[お茶のおばあさん](https://ja.wikipedia.org/wiki/%E3%81%8A%E8%8C%B6%E3%81%AE%E3%81%8A%E3%81%B0%E3%81%82%E3%81%95%E3%82%93)」「[北尾重光](https://ja.wikipedia.org/wiki/%E5%8C%97%E5%B0%BE%E9%87%8D%E5%85%89)」「[大沢豊子](https://ja.wikipedia.org/wiki/%E5%A4%A7%E6%B2%A2%E8%B1%8A%E5%AD%90)」「[大塚徹 (詩人)](https://ja.wikipedia.org/wiki/%E5%A4%A7%E5%A1%9A%E5%BE%B9_(%E8%A9%A9%E4%BA%BA))」  

## 他の団体の活動支援
Code for Historyを名乗る前の活動も含みます。  
本業としているわけではありませんが、Maplatの適用方法相談含め、古地図や地誌調査、図書館リファレンスなどを活用したノウハウで協力できることがあれば可能な範囲でお引き受けできます。  
お気軽にお問い合わせください。

### 北海道のアイヌ語地名位置特定支援
大学共同利用機関法人 人間文化研究機構の[歴史地名データ](https://www.nihu.jp/ja/publication/source_map)制作において、5万分の一地形図からの位置特定で旧版地形図に位置ずれ、ゆがみが多く位置特定できなかったところを、位置同定技術を提供して協力しました。  

### ヒロシマ・アーカイブへの協力
[渡邉英徳](https://ja.wikipedia.org/wiki/%E6%B8%A1%E9%82%89%E8%8B%B1%E5%BE%B3)先生を中心とした広島原爆の記憶証言を残すサイト「[ヒロシマ・アーカイブ](http://hiroshima.mapping.jp/index_jp.html)」に、[国土地理院の地形データを読み込むオープンソースライブラリの提供](https://github.com/tilemapjp/Cesium-JapanGSI)で協力しました。  

### Maplat適用案件への協力、サポート
いくつかのCode for Historyを主体としないMaplat適用案件への導入支援を行いました。  
公開できないものなどもありますが、公開可能な事例としては以下のようなものがあります。  
* 株式会社まちづくりプラットフォーム様の「[観光クラウドアプリ](https://www.machi-pla.com/apps/)」へのMaplat (MaplatAndroid, MaplatiOS)適用支援
* 大阪市東成区様の「[ひがしなりまち歩きアプリ](https://higashinari-walk.fun/)」へのMaplat (Maplat UI)適用支援

### 偉人、史跡などの来歴など調査
公開できない案件が多いですが、偉人、史跡などについて、古地図や地誌、図書館調査などを中心とした支援を行ってきました。

