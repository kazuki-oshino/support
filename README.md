# App Support

iOSアプリのサポートページとプライバシーポリシーを管理するリポジトリです。

## 構成

各アプリは独立したディレクトリで管理されています。

```
support/
├── _config.yml          # GitHub Pages設定
├── index.md             # トップページ
├── app-ads.txt          # AdMob用 app-ads.txt
└── {app-name}/          # 各アプリのディレクトリ
    ├── index.md         # アプリ紹介
    ├── privacy.md       # プライバシーポリシー
    ├── support.md       # サポートページ
    └── terms.md         # 利用規約（任意）
```

## GitHub Pagesの設定

1. GitHubでこのリポジトリをPublicで作成
2. Settings → Pages → Source を `main` ブランチの `/ (root)` に設定
3. 公開URLは `https://kazuki-oshino.github.io/support/` になります

## URL形式

各アプリのページは以下の形式でアクセスできます：

- アプリ紹介: `https://kazuki-oshino.github.io/support/{app-name}/`
- プライバシーポリシー: `https://kazuki-oshino.github.io/support/{app-name}/privacy`
- サポート: `https://kazuki-oshino.github.io/support/{app-name}/support`
- 利用規約: `https://kazuki-oshino.github.io/support/{app-name}/terms`
