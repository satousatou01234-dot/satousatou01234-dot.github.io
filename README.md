# satousatou01234-dot.github.io（KOKOAPPS の開発者サイト）

GitHub Pages のユーザーサイト（`https://satousatou01234-dot.github.io/`）。

| ファイル | 役割 |
|---|---|
| `app-ads.txt` | AdMob の app-ads.txt（`https://satousatou01234-dot.github.io/app-ads.txt`）。広告枠を売ってよい相手の宣言。AdMob のパブリッシャー ID は `pub-3714197993977316`（アプリ ID `ca-app-pub-3714197993977316~…` の `~` の前） |
| `index.html` | 開発者サイトのトップ（アプリ・プライバシーポリシー・お問い合わせ） |
| `.nojekyll` | Jekyll を通さず、ファイルをそのまま出す |

プライバシーポリシーは別のリポジトリ（`privacy_policy`。`https://satousatou01234-dot.github.io/privacy_policy/`）。
このリポジトリに `privacy_policy` という名前のフォルダを作らないこと（同じ URL が重なる）。

## AdMob に app-ads.txt を認めてもらうには

1. Google Play Console の「ストアの設定」→ 連絡先の詳細の「ウェブサイト」に `https://satousatou01234-dot.github.io/` を入れる
   （AdMob はこのホスト名の `/app-ads.txt` を読む）。アプリごとに入れる
2. アプリを Google Play に公開し、AdMob の「アプリの設定」でストアの掲載情報とリンクする
3. AdMob の「アプリ」→「すべてのアプリを表示」→「app-ads.txt」タブで「アップデートを確認」。確認には最大 24 時間ほどかかる

ほかの広告ネットワーク（メディエーション）を足すときは、その会社が示す行を `app-ads.txt` に 1 行ずつ足す。
同じ AdMob アカウントのアプリは、この 1 行で全部まかなえる（アプリごとに書き足す必要はない）。
