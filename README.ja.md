# Pasuko

<p align="center" style="text-align: center">
  <img src="./assets/images/logo.png" width="55%"><br/>
</p>

<div align="center">
<strong>
<samp>

[English](README.md) · [简体中文](README.zh.md) · [日本語](README.ja.md) ·
[한국어](README.ko.md) · [Español](README.es.md) · [Português](README.pt-br.md) ·
[Русский](README.ru.md) · [Francais](README.fr.md) · [Uzbek](README.uz.md) · [Deutsch](README.de.md) ·
[Türkçe](README.tr.md)

</samp>
</strong>
</div>

---
これは、元のWindowsクリップボードの機能を拡張するために使用されるクリップボードアプリケーションです

## 使用手順

- Pasukoを開いた後、`Ctrl+V` のキー組み合わせを押すとパネルを開くことができます（もちろん、Pasukoを開いた後に何かをコピーしておく必要があります）。パネル内の内容は時間順に並べられています。

![pic1](./assets/images/pic1.png)

- `J`キーと`K`キーを押して選択を上下に移動し、`Tab`キーを押して現在のカーソル位置に選択項目を入力します。なお、これは一度に1文字ずつ入力されることに注意してください。

![pic2](./assets/images/pic2.png)

- もしエントリーをあまりにも多くコピーした場合は、ノーマルモードで `F` キーを押して検索モードに入ることを選択できます。このモードではテキストボックス（編集）が追加され、検索したいテキストを入力できます。これは他のプロンプトを使用するエディタと同じような使い方です。必要な内容を見つけたら Enter を押し、`J` と `K` で選択し、`Tab` で入力します。入力が完了すると、ノーマルモードに戻ります。検索をキャンセルしたい場合や結果が期待通りでない場合は、`Esc` を押して検索を終了してください。

![pic3](./assets/images/pic3.png)

- 通常モードで編集モードに入るには `I` を押します。各アイテムのテキストを変更でき、保存するには `Enter` を押し、破棄するには `Esc` を押します。

![pic4](./assets/images/pic4.png)

- 特定の項目が不要な場合は `D` を押して削除してください。また、Pasuko に内容がない場合、`Ctrl+V` を押してもパネルは開きません。

![pic5](./assets/images/pic5.png)  ![pic6](./assets/images/pic6.png)

- パネルを閉じるには `Esc` を押してください。パスクをはトレイで見つけることができます。`Ctrl+Shift+V` は元の貼り付け用です。

> [!TIP]
> |通常|キー|機能|
> |---|---|---|
> ||J|次の項目を選択|
> ||K|前の項目を選択|
> ||Tab|選択した項目を入力|
> ||F|検索|
> ||I|編集|
> ||D|削除|
> ||Esc|パネルを閉じる|
> |検索|||
> ||Enter|項目を検索|
> ||Esc|検索をキャンセル|
> |編集|||
> ||Enter|編集完了|
> ||Esc|編集をキャンセル|

---
追伸：一部のChromiumベースのソフトウェアでは、Pasukoを使用するとカーソルの位置が正しく設定されない場合があり、その場合はパネルが左上隅に表示されます。
