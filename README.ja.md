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
