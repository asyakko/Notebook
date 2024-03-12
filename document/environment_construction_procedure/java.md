
# 環境構築手順（Java）
***
#### Eclipse
Eclipse（イクリプス、英: Eclipse）は、コンピュータプログラミングにおいて使用される統合開発環境（IDE）である。
[Eclipse (統合開発環境)](https://ja.wikipedia.org/wiki/Eclipse_(%E7%B5%B1%E5%90%88%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83))

##### Spring Tools
フレームワーク「Spring Boot」での開発に適したEclipse
##### All on One
他言語で開発可能なプラグインが入ったEclipse

<br>

#### JDK
Java Development Kit (JDK) はオラクル（旧サン・マイクロシステムズ）により提供されている、プログラミング言語Javaを使ってJavaアプリケーションおよびその他のソフトウェアコンポーネントを構築するためのソフトウェア開発キット (SDK) および開発環境である。
[Java Development Kit](https://ja.wikipedia.org/wiki/Java_Development_Kit)

この手順では[Amazon Corretto](Amazon-Corretto)を使用します。

<br>

##　環境構築で必要なファイル
***

## ダウンロードサイト一覧
***
#### Eclipse
https://willbrains.jp/

#### Spring Tools
https://spring.io/tools

#### eclipse日本語化ツール
https://willbrains.jp/pleiades.html?v=4#PLUGIN

#### JDK（Amazon Corretto）
https://aws.amazon.com/jp/corretto/

[Amazon-Corretto]: https://aws.amazon.com/jp/corretto/

<br>

## 直ダウンロードリンク一覧
***

#### Spring Tools 4
* [4.21.1](https://cdn.spring.io/spring-tools/release/STS4/4.21.1.RELEASE/dist/e4.30/spring-tool-suite-4-4.21.1.RELEASE-e4.30.0-win32.win32.x86_64.self-extracting.jar)
* [4.17.2](https://download.springsource.com/release/STS4/4.17.2.RELEASE/dist/e4.26/spring-tool-suite-4-4.17.2.RELEASE-e4.26.0-win32.win32.x86_64.self-extracting.jar)

#### eclipse日本語化ツール
* https://ftp.jaist.ac.jp/pub/mergedoc/pleiades/build/stable/pleiades-win.zip

#### JDK（Amazon Corretto）
* [corretto-21](https://corretto.aws/downloads/latest/amazon-corretto-21-x64-windows-jdk.msi)
* [corretto-17](https://corretto.aws/downloads/latest/amazon-corretto-17-x64-windows-jdk.msi)

<br>

## インストール手順
***
### Spring Tools
1.  インストールしたい場所にダウンロードしたファイルを配置して実行。<br>※配置場所はドライブ(C:\\)直下など階層の浅い場所に配置すること。（ファイルパスが長くなると動作しない場合があります）
1. 特に変更せず「Next」を押下し続ける。

#### eclipse日本語化ツール
1. 日本語化するアプリケーションの「選択」押下。
1. Spring Toolsでインストールした「SpringToolSuite4.exe」を選択。
1. 「日本語化する」押下。
  

#### JDK（Amazon Corretto）
1. インストーラーを実行。
1. 特に変更せずNextを押下し続ける。


<br>

## Eclipseの設定
***

#### JDK
EclipseのJava実行環境にインストールしたJDKを紐づける。
1. EclipseのJDKの設定を開く。
   * ツールバー > ウィンドウ > 設定 > Java > インストール済みのJRE
1. インストールしたJDKが存在しない場合は以下の手順で追加する。
   * 「追加」ボタン押下。
   * 「標準VM」を選択して「次へ」を押下。
   *  JREホームの「ディレクトリ」を押下してインストールしたJDKのフォルダを選択する。
      * 例：　C:\Program Files\Amazon Corretto\jdk21.0.2_13
1. インストールしたJDKにチェックを入れて「適用」を押下する。




