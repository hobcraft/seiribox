# seiribox（公開ページ用）

SeiriBox（macOS アプリ）のサポートとプライバシーポリシー。
GitHub Pages で `https://hobcraft.github.io/seiribox/` に公開する。

- サポート: `https://hobcraft.github.io/seiribox/support/`
- プライバシーポリシー: `https://hobcraft.github.io/seiribox/privacy/`

**このリポジトリは公開される。アプリのソースや申請メモを入れないこと。**
ソースと内部資料は `~/claude/FileTidy/`（非公開）にある。Kotohako と同じ構成。

独自ドメイン（hobcraftdata.com）ではなく GitHub Pages に置いているのは、
ドメインをいつまで維持するか決まっていないため（2026-09-15）。
URL が変わると App Store の登録内容も直す必要があるので、
なるべく変わらない場所に置く。

## 公開の手順

GitHub 側に `hobcraft/seiribox`（**public**。無料プランの Pages は公開リポジトリのみ）が必要。
リポジトリ名が URL の `/seiribox/` になる。

```
git remote add origin git@github.com:hobcraft/seiribox.git
git push -u origin main
```

GitHub の Settings → Pages で Source を `main` / `/ (root)` にする。
公開まで数分かかる。

公開したら、2つの URL をブラウザで開いて表示されることを確認する（404 だと審査で落ちる）。
