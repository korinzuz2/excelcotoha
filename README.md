# Excelで簡単に日本語の自然言語処理をできるようにするマクロ

詳しくはQiita記事参照。
https://qiita.com/Harusugi/items/535874c0456dbc4db231

## 使い方
### 1.COTOHA APIに登録する
今回の言語処理はCOTOHA APIを使っているため、まずは登録します。
for Deveropersという無料プランがあるのでそちらを申し込みます。(1日各API1000回まで。)
Developer Client id、Developer Client secretという２つのキーがもらえるので、控えておきます。

### 2. マクロ入りエクセルファイルをダウンロードする
下記からダウンロード (Downloadと書かれたボタンをクリック)
https://github.com/korinzuz2/excelcotoha/blob/master/COTOHA%E5%85%AC%E9%96%8B%E7%94%A8.xlsm

### 3. ダウンロードしたブックを開き、マクロを有効化する
開くと警告ウインドウなりでマクロを有効化するか聞かれるので、有効にするをクリック

### 4. HTTPリクエストを有効にする
Excelを開いた状態でAlt + F11するとウインドウが立ち上がるので
そのツールバーからツール→参照設定で「Microsoft XML v6.0」というものにチェックを入れます。

### 5. 項番1で得たキーを書き込む
シートのB1, B2セルに項番1で発行されたClient id、Client secretを書き込みます。
書き込むとしばらくして、様々なサンプルの解析結果が表示されます。
※サンプルは色々やってるので時間がかかると思います。適宜削ってお使いください。

