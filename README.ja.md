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

