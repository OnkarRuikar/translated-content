---
title: "スキルテスト: リンク"
slug: Learn_web_development/Core/Structuring_content/Test_your_skills:_Links
original_slug: Learn/HTML/Introduction_to_HTML/Test_your_skills:_Links
l10n:
  sourceCommit: 8e2641ebe076ab89299c77a51ece882de4ba5efb
---

{{learnsidebar}}

このスキルテストの目的は、あなたが [HTML でのハイパーリンクの実装](/ja/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)を行う方法を理解しているかどうかを評価することです。

> [!NOTE]
> 以下の対話型エディターで解決に挑戦することができます。ただし、コードをダウンロードし、[CodePen](https://codepen.io/)、[jsFiddle](https://jsfiddle.net/)、[Glitch](https://glitch.com/)などのオンラインツールを使用して作業することが便利な場合もあります。
>
> 行き詰まったら、助けを求めましょう。このページの最下部の[評価またはさらなるヘルプ](#評価またはさらなるヘルプ)の節をご覧ください。

## 課題 1

このタスクでは、クジラの情報ページのリンクを埋めるのを手伝っていただきます。

- 最初のリンクは、現在のページと同じディレクトリーにある `whales.html` というページにリンクされるようにします。
- また、マウスオーバーしたときに、このページにはシロナガスクジラやマッコウクジラの情報が含まれていることをユーザーに指示するツールチップを付けましょう。
- 2 つ目のリンクは、ユーザーの既定のメールアプリケーションで、受信者を "whales\@example.com" に設定してメールを開くためのリンクに変更しましょう。
- メールの件名が「クジラについての質問」と自動的に記入されるように設定すると、ボーナスポイントも得られます。

> [!NOTE]
> この例の 2 つのリンクには `target="_blank"` 属性が設定されています。これは厳密には最善の手法ではありませんが、ここではリンクが埋め込まれた `<iframe>` で開かないようにし、その過程で例のコードを削除するようにしています。

下記のライブコードを更新して、完成例を再現してみてください。

{{EmbedGHLiveSample("learning-area/html/introduction-to-html/tasks/links/links1.html", '100%', 700)}}

> [!CALLOUT]
>
> 自分のエディターやオンラインエディターで作業する場合は、[この課題の開始時点のものをダウンロード](https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/tasks/links/links1-download.html)しましょう。

## 課題 2

この課題では、4 つのリンクが適切な場所にリンクするように記入していただきます。

- 最初のリンクは、カレントディレクトリーの中の `blue` というディレクトリーにある `blue-whale.jpg` という画像にリンクするようにしましょう。
- 2 つ目のリンクは、カレントディレクトリーの 1 つ上のディレクトリーである `narwhal` というディレクトリーにある `narwhal.jpg` という画像にリンクするようにしましょう。
- 3 つ目のリンクは、UK の Google 画像検索にリンクしてください。ベース URL は `https://www.google.co.uk` で、画像検索は `imghp` というサブディレクトリーに配置されています。
- 4 つ目のリンクは、現在のページの一番下にある段落にリンクしましょう。これは `bottom` という ID が付いています。

> [!NOTE]
> この例で最初の 3 つのリンクには `target="_blank"` 属性が設定されています。これは厳密には最善の手法ではありませんが、ここではリンクが埋め込まれた `<iframe>` で開かないようにし、その過程で例のコードを削除するようにしています。

下記のライブコードを更新して、完成例を再現してみてください。

{{EmbedGHLiveSample("learning-area/html/introduction-to-html/tasks/links/links2.html", '100%', 800)}}

> [!CALLOUT]
>
> 自分のエディターやオンラインエディターで作業する場合は、[この課題の開始時点のものをダウンロード](https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/tasks/links/links2-download.html)しましょう。

## 課題 3

以下のリンクは、一角獣に関する情報ページ、対応するメールアドレス、および 4MB の PDF ファクトファイルへのリンクです。この課題では、次のことを行ってください。

- リンクテキストの書き方が悪い既存の段落を選び、良いリンクテキストがあるように書き直しましょう。
- 警告を追加する必要があるリンクには、警告を追加しましょう。

> [!NOTE]
> この例における最初と 3 つ目のリンクには `target="_blank"` 属性が設定されています。これは厳密には最善の手法ではありませんが、ここではリンクが埋め込まれた `<iframe>` で開かないようにし、その過程で例のコードを削除するようにしています。

下記のライブコードを更新して、完成例を再現してみてください。

{{EmbedGHLiveSample("learning-area/html/introduction-to-html/tasks/links/links3.html", '100%', 700)}}

> [!CALLOUT]
>
> 自分のエディターやオンラインエディターで作業する場合は、[この課題の開始時点のものをダウンロード](https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/tasks/links/links3-download.html)しましょう。

## 評価またはさらなるヘルプ

この例は、上記のインタラクティブエディターで練習することができます。

この作品を評価してほしい、行き詰っているので相談に乗ってほしいという方は次のようにしてください。

1. 作品をオンラインの共有可能なエディター、例えば [CodePen](https://codepen.io/)、[jsFiddle](https://jsfiddle.net/)、[Glitch](https://glitch.com/) に置いてください。コードは自分で書いても、上の節でリンクされている開始時点のファイルを使用しても構いません。
2. [MDN Discourse forum 学習カテゴリー](https://discourse.mozilla.org/c/mdn/learn/250)に評価や助けを依頼する記事を書いてください。投稿には以下を記載してください。

   - 「リンク、スキルテスト 1 のための評価希望」のような説明的なタイトル。
   - すでに持っている内容や、私たちに望むことの詳細。例えば、行き詰まって助けが必要な場合や、評価を希望する場合などを指示してください。
   - 評価やヘルプが必要な例へのリンクを、オンライン共有エディターで示してください（上記のステップ 1 で述べたとおり）。コードを見ることができなければ、コーディングの問題で誰かを助けることはとても難しいのです。
   - 実際の課題または評価ページへのリンク。あなたが助けを求めている問題を探すことができます。
