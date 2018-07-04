﻿# uPDFLoader
UnityでPDFをTexture化してロードできるようにするライブラリです。(Windows限定)

PDFをコマンドラインでランタイムに1枚ずつ画像化(jpg)し、JPGの連番をキャッシュディレクトリに生成します。

PDF変換時に連番画像のパスを取得しているのでそれを用いて擬似的にPDFをロードできます。

# 使い方
* クローン
* [GhostScriptのインストール](https://www.ghostscript.com/download/gsdnld.html)
* UniRxの導入

# UnityPackage版
[リリースチャンネルの方を参照して下さい](https://github.com/negipoyoc/uPDFLoader/releases)


# 注意
GhostScriptのバージョンはgs9.23でデフォルトのディレクトリにインストールされているもの。
（バージョン変更時PDFGenerator.csのgsPathを書き換えること。実行ファイルのPathが必要）

