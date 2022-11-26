# Screen Capture
[Booth](https://lesspeer-waya.booth.pm/items/4349439) | [GitHub](https://github.com/waya0125/ScreenCapture) | [WebSite](https://waya0125.com/) | [Twitter](https://twitter.com/wayamoti2015)

## **=== 概要 ===**
**キャラクターをキレイに撮影したい！その一心で作りました。**  
※ このソフトウェアは、キャラクターの撮影を目的としています。  
※ スクリプトをEditorフォルダに格納します。Editorフォルダに格納しないとビルド時、エディタ再生時にエラーになります。  

**特徴：**
- Main Cameraに投影されたオブジェクトを撮影できます。
- カメラの解像度に応じてスクリーンショットの解像度を変更します。
- アルファ値を変えることで透過画像も可能。
- スクリプト側でファイルのヘッダー名の命名規則を変えることができます。

**前提：** Main Cameraには必ずタグ「MainCamera」を付けてください。

**使い方：**
1. ScreenCapture.unitypackageをインポートします。*1
2. メニューから「Tools」→「Screen Capture」を選択します。
3. 「Capture」ボタンを押すと、スクリーンショットが撮影され、スクリーンショットが保存されます。

*1 （わかる人向け）VRChatで使用する場合は、zipを展開したものをVCC経由でセットアップして下さい


## **=== リリース ===**
**バージョン1.0.0（最新版）**  
*リリース日: 2022年11月27日*

- スクリーンショットをAssets/Screenshot/フォルダに保存するように指定。
- スクリーンショットの解像度をカメラの解像度に応じて変更するように指定。
- アルファ値に対応させて透過画像も可能にした。

# 参考文献
## ～コードのベース～
[Unity]Unity Editor上でスクリーンショットを撮る方法 - [https://nobushiueshi.com/unityunity-editor上でスクリーンショットを撮る方法/](https://nobushiueshi.com/unityunity-editor%E4%B8%8A%E3%81%A7%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%E3%82%92%E6%92%AE%E3%82%8B%E6%96%B9%E6%B3%95/)  

## ～プラットフォーム判定～
Unity プラットフォーム判別 - https://qiita.com/Ubermensch/items/75072ef89249cb3b30e7  
RuntimePlatform - https://docs.unity3d.com/ScriptReference/RuntimePlatform.html  

## ～ファイラーで表示する方法～
【Unity】 セーブファイルのパスを開くメニューを作る - https://www.urablog.xyz/entry/2021/11/05/070000  
How to Open a File or Folder in Terminal on Mac - https://www.switchingtomac.com/tutorials/how-to-open-a-file-or-folder-in-terminal-on-mac/  
【 xdg-open 】コマンド――ファイルをデフォルトアプリケーションで開く - https://atmarkit.itmedia.co.jp/ait/articles/1906/06/news007.html  

## ～ディレクトリの有無判定～
Unity フォルダやファイルの有無を確認し無ければ生成する - https://hakase0274.hatenablog.com/entry/2019/07/27/223840  
[unity]指定されたファイルがどのパスにあるか調べる - https://www.create-forever.games/unity-directory-getfiles/  