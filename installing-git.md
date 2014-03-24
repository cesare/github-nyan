---
layout: default
---

## Gitのインストール

### CUI

#### Git本家からダウンロード

ソースパッケージによる配布のほか、バイナリ版も配布されています。  
<http://git-scm.com/downloads/>

#### Homebrewでインストール (Macの人向け)

Homebrew がすでにインストールされている Mac をお使いの方は、こちらがいちばん手軽かと思われます。

```bash
$ brew install git
```

### GUI

GUI版のクライアントもあります。お好みでどうぞ。

* [GitHub for Mac] (http://mac.github.com/)
* [GitHub for Windows] (http://windows.github.com/)
* [SourceTree] (http://www.sourcetreeapp.com/) Atlassian謹製。Bitbucketじゃくても使えます。GitとMercurialに対応。

### GitHub for Mac からコマンドラインツールをインストール

上記の GitHub for Mac をインストールすると、コマンドラインツールが使えるようになります。

設定方法は、

* GitHub for Mac を起動する
* メニューバーの「GitHub」から「Preferences...」を選択
* ダイアログ上部タブの「Advanced」を選ぶ
* 「Install Command Line Tools」ボタンを押す

![Screenshot]({{site.baseurl}}/images/github-mac-command-line-tools.png)


### CUIインストール確認 (Mac, Linux)

ターミナルを起動して、

```bash
$ git --version
# => git version 1.9.1 のようにバージョンが表示されればOK
```
