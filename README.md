# [Sequence Sketch Local](https://su5filed.github.io/sequence-sketch-local/sequence-editor.html)

![テキストとシーケンス図を並べて編集するSequence Sketch Localの画面](screenshot.png)

**テキストでも、マウスでも。ローカルで完結するシーケンス図エディターです。**

左側にテキストを書くと、右側にシーケンス図を描画します。図上で矢印や注釈を追加・移動すると、テキストにも反映されます。

[SequenceDiagram.org](https://sequencediagram.org/) の使い勝手と記法を参考に、インターネットに接続できない環境でも手軽に作図できるツールを目指して作成しました。同サービスとは関係のない独立したプロジェクトで、構文は一部に対応しています。

## 特徴

- **オフライン動作**：アプリ本体はHTMLファイル1つ。インストール・サーバー・外部ライブラリは不要です。
- **テキストと図の双方向編集**：入力でもドラッグ操作でも、図とソースを更新できます。
- **基本的なシーケンス図に対応**：参加者、矢印、自己呼び出し、外部とのメッセージ、note、activation、alt／else、dividerを扱えます。
- **画像出力**：SVG・PNG保存に対応しています。
- **図のデータを送信・収集しません**：作図はブラウザ内で処理し、アクセス解析や広告は組み込んでいません。

## 使い方

1. [sequence-editor.zipをダウンロード](https://github.com/su5filed/sequence-sketch-local/raw/refs/heads/main/sequence-editor.zip)して展開します。
2. `index.html`（配布ファイルが `sequence-editor.html` の場合はそちら）をEdgeまたはChromeで開きます。
3. 左側へソースを入力するか、右側の生命線をドラッグして矢印を追加します。注釈や分岐は右クリックメニューから追加できます。

図形や文字はダブルクリックで編集できます。詳しい操作はHelpのInstructions、変更履歴はRelease Notesをご覧ください。

**ソースの自動保存はありません。** ページを閉じたり再読み込みしたりする前に、左側のテキストをコピーして保管してください。画像の保存先指定には、対応するデスクトップ版EdgeまたはChromeが必要です。

## 開発について / Contributing

現在は試作品です。個人的に必要と感じた基本機能を中心に実装しており、SequenceDiagram.orgの全機能・全構文には対応していません。

改善への参加を歓迎します。自由にForkして修正・コミットし、Pull Requestをお送りください。バグ報告や機能提案も歓迎します。

This project is a prototype implementing the basic features I personally need. It does not support all features or syntax of SequenceDiagram.org.

Contributions are welcome! Feel free to fork the repository, make changes, commit them to your fork, and submit a pull request. Bug reports and feature suggestions are also welcome.

## ライセンス / License

本プロジェクトは [MIT License](LICENSE) で公開しています。商用利用、改変、再配布、販売が可能です。配布時には著作権表示とライセンス文を保持してください。本ソフトウェアは現状のまま提供され、保証はありません。

This project is released under the [MIT License](LICENSE). Commercial use, modification, redistribution, and sale are permitted. Redistributions must retain the copyright notice and license text. The software is provided “as is,” without warranty.

## プライバシー

アプリは入力したソースや図を外部へ送信しません。外部リンクを開いた際やGitHub／GitHub Pagesで閲覧した際の通信・アクセス情報は、各サービスの取り扱いに従います。詳細はアプリ内のHelp → Privacy Policyをご覧ください。
