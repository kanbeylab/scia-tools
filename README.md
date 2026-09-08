# SCIA Tools

SCIA（セカンドキャリア・インキュベーション協会）の講座で使う、ブラウザ完結型ツール置き場。

## ツール一覧

| ツール | 用途 | URL | 作成者 |
|---|---|---|---|
| Next Journey Map | Hatchフェーズ：Identity / WHAT / HEART / MESSAGE / VOICE を整理し、変遷を記録 | https://kanbeylab.github.io/scia-tools/hatch-next-journey-map/ | 向山 |

## ルール（重要）

このリポジトリは**公開**です。以下を守ってください。

1. **受講生の個人情報を一切含めない** — 氏名、会社名、発言内容、サンプルデータも含む
2. **APIキーを書かない** — OpenAI / Anthropic / Google などのキーをHTMLやJSに埋め込まない
3. **外部にデータを送らない** — fetch / XMLHttpRequest で外部サービスにユーザー入力を送信しない
4. **保存はユーザーのPCへ** — データはファイルのダウンロードまたはブラウザ内のみ。サーバー保存が必要な場合は事前に相談

受講生のデータはNotion（SCIA 0期 個別カルテ）で管理します。ここには置きません。

## 追加方法

1. `ツール名/` フォルダを作り、その中に `index.html` を置く
2. この README の一覧に1行追加する
3. push後、数分で `https://kanbeylab.github.io/scia-tools/ツール名/` で動きます
