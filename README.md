# はじめに

## 本プロジェクトについて
- [本プロジェクト](https://github.com/dtxmuramasa/AoZs434AZUMADocs)は『Age of Z』のサーバー#434の日本人同盟、『(AZU)AZUMA』による知識の共有を目的として立ち上げ、管理、運用されています。

<br>
<br>
<hr>

# ライセンス
## Gitbookテンプレート
- 本プロジェクトは[GitbookTemplate](https://github.com/dtxmuramasa/GitbookTemplate)を基にしています。

## Gitbook
- 本ドキュメントは[Gitbook](https://github.com/GitbookIO/gitbook)を用いて生成しています。
- 本ドキュメントの更新には[Gitbook](https://github.com/GitbookIO/gitbook)が必要です。
	- [Gitbook](https://github.com/GitbookIO/gitbook)の利用には[Node.js](https://nodejs.org/ja/)が必要です。

## 導入プラグイン
- -sharing
	- https://www.npmjs.com/package/gitbook-plugin-sharing
	- 各種SNSのシェアボタンを消します。
- hide-published-with
	- https://www.npmjs.com/package/gitbook-plugin-hide-published-with
	- Gitbookへのpublishボタンを消します。
	- リポジトリなどは残っていないが、機能はする模様。
- -lunr, -search
	- https://www.npmjs.com/package/gitbook-plugin-lunr
	- https://www.npmjs.com/package/gitbook-plugin-search
	- Gitbookに標準搭載されている検索エンジンを無効化します。
- search-pro-kui
	- https://www.npmjs.com/package/gitbook-plugin-search-pro-kui
	- あらゆるutf-8文字の検索に高度に対応した検索エンジンプラグイン。
	- これを導入しないと日本語の部分検索が一部うまくいかないことがある。
		- 例えば「環境構築」での検索で引っかかる文書が「構築」では引っかからなかったりなど。
- uml
	- https://www.npmjs.com/package/gitbook-plugin-uml
	- Gitbook用のplantUMLプラグイン。
- expandable-chapters
	- https://www.npmjs.com/package/gitbook-plugin-expandable-chapters
	- サイドバーのメニューをCollapse/Expandできるツリービューにするプラグイン。
- include-codeblock
	- https://www.npmjs.com/package/gitbook-plugin-include-codeblock
	- ファイルの内容を展開してくれるマクロを提供するプラグイン。
- code-editor
	- https://www.npmjs.com/package/gitbook-plugin-code-editor
	- よくあるコードエディタとコードの実行結果が見られるアレ。
- code
	- https://www.npmjs.com/package/gitbook-plugin-code
	- 複数行のコード記述に行数を表示してくれるプラグイン。
