# Jリーグ歴代全選手収録のATOK変換辞書

1992年のJリーグ開幕から現在に至るまでに選手登録歴のある選手名のほとんど[※](#網羅性について)を収録したATOK互換の変換辞書ファイルです。

![demo](./demo.gif)

## ダウンロード方法

[ダウンロードリンク](https://raw.githubusercontent.com/belltailjp/jleague-all-players-atok-dictionary/master/J%E3%83%AA%E3%83%BC%E3%82%B0%E6%AD%B4%E4%BB%A3%E9%81%B8%E6%89%8B%E5%90%8D%E8%BE%9E%E6%9B%B8.txt)で開いた辞書ファイルをブラウザのメニューから保存する。
（Google Chromeの場合、ファイル → ページを別名で保存）

ATOK対応のためUTF-16で提供しています。
IMEソフトウェアによっては同じ内容の[UTF-8版](https://raw.githubusercontent.com/belltailjp/jleague-all-players-atok-dictionary/master/J%E3%83%AA%E3%83%BC%E3%82%B0%E6%AD%B4%E4%BB%A3%E9%81%B8%E6%89%8B%E5%90%8D%E8%BE%9E%E6%9B%B8_utf8.txt)も利用可能です。

こちらの辞書は以下の3パターンの内容をすべて含んでいますが、それぞれのパターンのみの辞書も提供しています。

* 姓名読み → 姓名漢字
* 名読み → 名漢字
* 名読み → 姓名漢字

[こちら](https://github.com/belltailjp/jleague-all-players-atok-dictionary/tree/master)から対応する.txtのリンクをクリックし、"Raw"ボタンをクリックするとダウンロード可能リンクを開くことができます。


## ATOK登録方法

* ATOKメニューの辞書ユーティリティを開く
* 「ツール」メニューから「ファイルから登録・削除」
* 「単語一括処理」画面で、先ほどダウンロードしたファイルを指定

参考
https://support.justsystems.com/faq/1032/app/servlet/qadoc?QID=033072


他のIMEソフトウェアとの互換性について
* Android版ATOKにはインポート可能であることが報告されています
* Google日本語入力ではインポート可能です
* Microsoft IMEは未確認です
* Macの標準日本語入力アプリでは未確認です


## 注意

### 正確性について

この辞書は、手作業で注意深く作成されたものではありません。
Jリーグのデータにおける選手名の漢字表記および英語表記から最先端のAI技術（ChatGPT）によりひらがな表記を推定することで作成したものです。

従ってひらがな表記が誤っている例（正しい読みを入力したにも関わらず漢字に変換できない）も含まれるのでそれを了承の上ご利用ください。
なお、仕組み上、漢字が誤っている例は基本的に含まれていない想定ですが、それも含めて内容の正確性については一切無保証です。

誤った例を発見した場合、[誤りを見つけた場合](#誤りを見つけた場合)に従って報告が可能です。


### 網羅性について

Jリーグに選手登録歴のある選手のうち、基本的に以下のような選手を除いてほとんどの選手が登録されています。
* 日本語表記での名前がすべてカタカナからなる選手を除く
* その他、ChatGPTが処理できなかった名前の選手を除く


## 誤りを見つけた場合

* Githubアカウントを持っている場合
  * [報告ページ](https://github.com/belltailjp/jleague-all-players-atok-dictionary/issues)からissueを作成する
    * Pull Requestは送らないでください。このリポジトリの辞書データは別の非公開データから自動生成しているため、Pull Requestを送ってもマージされません。その代わり、誤りの報告があった場合に非公開データを編集した上でこちらの辞書データを更新します。
* それ以外の場合
  * TBA


## 更新履歴
* [2023/11/27]
  * 一部誤りの修正
  * 曖昧な名前（複数の名前で登録歴がある選手）を一部対応
  * UTF-8版を提供
  * 名→姓名の辞書を提供。内容を分離。ファイル名変更
* [2023/11/25] 初版
