# AviUtl2 非公式言語ファイル
## このファイルについて
個人的に修正した [AviUtl2](https://spring-fragrance.mints.ne.jp/aviutl/) の日本語言語ファイルとその他です。<br>
Windows で標準的に使用されている日本語のテキストに修正 (フォルダー、名前を付けて保存、「全て」の綴りを「すべて」に変更など) や「こうした方が良いのでは？」と思う箇所を個人的に弄ってます。

![Sample](./sample.png)

## 言語ファイルの内容について
言語ファイルである、aul2 ファイルは UTF-8 なテキストファイルです。<br>
UTF-8 に対応したテキストエディタを使用すれば、翻訳やテキストの修正が簡易的に行えます。

## ファイルのインストールと設定
プレビュー編集画面にドラッグ&ドロップまたは、`C:\ProgramData\aviutl2\Language` にファイルを配置で言語が追加できます。<br>
`設定 -> 言語の設定`を選択し、Japanese_Mod を選択で適用されます。

### 翻訳のサンプル
左側に**ソースとなる日本語のテキスト**、イコールの隣の**右側に翻訳後のテキスト**という構成です。<br>
`Root、Layer、Scene、OK` はセミコロンで除外されているのでテキストを変更するには、左側のテキストのセミコロンを外す必要があります。

```
ファイル=ファイル
プロジェクトを新規作成=プロジェクトを新しく作成
プロジェクトを開く=プロジェクトを開く
最近使ったプロジェクト=最近開いたプロジェクト
バックアップしたプロジェクト=バックアップ済みのプロジェクト
プロジェクトを保存=プロジェクトを保存
プロジェクトを別名で保存=名前を付けてプロジェクトを保存
ファイル出力=ファイルをエクスポート
プロジェクトを保存して終了=プロジェクトを保存して終了
Root=ルート
Layer=レイヤー: 
Scene=シーン:
```
## English_GPT.aul2 について
GPT を使用と自分の能力を駆使して英語訳したバージョンのファイルです。<br>
標準で入っている言語ファイルは余分な空白やテキストの間違いがあったので、できる限り修正した物です。<br>
`設定 -> 言語の設定`を選択し、English_GPT を選択で適用されます。

![sample2](./sample_eng.png)

#### English (GPT)
`English_GPT.aul2` is English translated language file, created using GPT and my own skills.<br>
The standard included language file had extra spaces and text errors, so this version has been corrected as much as possible.<br>
To apply it, go to `設定 -> 言語の設定` and select `English_GPT`.

## Blank_Language.aul2 について
今後、他の言語に翻訳する方用のファイルです。<br>
**右側の翻訳済みのテキストを消した状態**で、**翻訳すべきテキストのソースのみ**になっています。

**翻訳のサンプル**を元に **Blank_Language.aul2** を編集するとその言語に訳せます。

#### English (GPT)
This file is for those who want to **translate into other languages in the future**.<br>
It contains only the source text to be translated, with the **right-side translated text removed**.

You can translate it into any language by editing **Blank_Language.aul2** using the **translation sample as a reference**.

## 更新履歴
- Beta 4 に対応済み
- 個人的に修正した日本語言語ファイルを作成
- 同時に英語が変だったことや余分な空白などがあったので修正したものを作成 (もっと自然な英語訳にしてくれる人募集)
- 翻訳者が翻訳しやすくなるであろう言語ファイルのブランク版を作成
- プラグイン情報とスクリプト情報の綴りを変更 (プラグインの一覧、スクリプトの一覧に変更)

## 言語ファイルの改変や再配布について
改変や再配布を行うのは自由にしてくれて構いません。<br>
むしろ、Premiere Pro 風にしたり DaVinci Resolve 風に改変しても良い奴です。
