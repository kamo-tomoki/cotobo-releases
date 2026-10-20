# cotobo-releases

Cotobo デスクトップ版の公式アプリ配布用リポジトリです。

- アプリ本体のソースは別の非公開リポジトリにあります。
- GitHub Releases に macOS 向けの配布物（`zip` / `dmg` / `latest-mac.yml`）を置きます。アプリはここから更新を確認します。
- `min-version.json` の `minimumVersion` を下回るバージョンは強制アップデートの対象になります。`0.0.0` は強制なしを意味します。
