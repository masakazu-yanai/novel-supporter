# 小説推敲補助ソフト「Novel Supporter」

## 公式サイト

以下のページが公式配布元です。説明や各種ドキュメントを用意しています。

**小説推敲補助ソフト「Novel Supporter」 - クロノス・クラウン -**  
https://crocro.com/pc/soft/novel_supporter/

## 紹介

本ソフトの目的は、小説の**推敲を補助**することです。

本ソフトは、小説をゼロから書くためのソフトではありません。書き上げた原稿の、**推敲を補助**するためのソフトです。

各種ツールを実行することで、小説のテキストファイルを加工して強調します。そうすることで、推敲の際に見落としがちな部分を、**見落とし難く**します。

本ソフトは、あくまで推敲の補助を行なうためのものです。小説自体を、機械的に改変するものではありません。

眼鏡をかけると文字が見やすくなるのと同じように、よく言われる注意点を気づきやすくするために、本ソフトを利用して下さい。

## 主な機能

小説のテキストファイルを加工して、小説の推敲を補助します。

以下のようなツールを収録しています。

* 単語近傍探索
* こそあど確認
* 文末重複確認
* 段落先頭重複確認
* 文章警告
* 画数ヒートマップ
* 文長ヒートマップ
* ルビ追加
* 文字種表示
* 指定文字数改行
* 音声読み上げ（SAPI5）
* センチメント分析
* 使用単語集計
* 正字略字切り替え
* 章ボリューム表示
* 言い回し確認
* 表記ゆれ確認
* 時系列分析

## 利用開始方法

### Windows環境

1. Zipファイル「novel\_supporter\_X.X.X.zip」をダウンロードして解凍する。
2. 64bit版Windowsの場合は「\_\_start\_\_.bat」をダブルクリックする。
	* 内部的には「NovelSupporter-win32-x64/NovelSupporter.exe/」を実行。
3. 32bit版Windowsの場合は「\_\_start\_32bit\_\_.bat」をダブルクリックする。
	* 内部的には「NovelSupporter-win32-ia32/NovelSupporter.exe/」を実行。

### Mac環境

1. [Mac実行用のElectron](https://github.com/electron/electron/releases/download/v7.1.7/electron-v7.1.7-darwin-x64.zip)（60MB）をDLして解凍する（[配布ページ](https://github.com/electron/electron/releases/tag/v7.1.7)）。
2. Zipファイル「novel\_supporter\_X.X.X_asar.zip」をダウンロードして解凍する。
3. 以下は、コマンドライン環境（ターミナル）で操作する。
4. 解凍した『Novel Supporter』の「asar」ディレクトリを、カレントディレクトリにする。
5. 「～/Electron.app/Contents/MacOS/Electron app.asar」を実行する。
	* 「～」は解凍したElectronのディレクトリのパス。
	* 「app.asar」を引数にして実行。

※ プログラムが分かる人は、実行用のスクリプトファイルを書いておくと便利です。
