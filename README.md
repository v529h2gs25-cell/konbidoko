# コンビどこ？ v0.1

コンビニと近隣の集合スポットを組み合わせて表示するスマホ対応の試作Webアプリです。

## 起動方法

`index.html` をブラウザで開くか、GitHub Pagesで公開します。Leaflet、地図タイル、Overpass APIのためインターネット接続が必要です。現在地取得は原則HTTPS（GitHub Pagesなど）で動作します。

## GitHub Pages 公開

1. GitHubで公開リポジトリ `konbidoko` を作成
2. `index.html`, `style.css`, `app.js` をリポジトリ直下にアップロード
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save
4. 数分後、表示されたURLを開く

## 注意点

- OpenStreetMapの登録状況に依存し、網羅性は保証されません。
- 距離は直線距離で、徒歩距離ではありません。
- 人数は入力できますが、v0.1では実際の収容人数情報がないためランキングには反映しません。未確認と明示します。
- スコアは距離とスポット種類のみの参考値です。
- 滞在許可・営業時間・安全性・混雑は未検証です。利用前に現地ルールを確認してください。
- 公開Overpass APIは混雑・利用制限があります。大規模公開時は専用バックエンド、キャッシュ、適切なデータ提供契約が必要です。
- 地図データ: © OpenStreetMap contributors。

## 次の開発

徒歩経路API、利用可能時間、現地写真、人数の検証済みデータ、投稿機能、重複候補の統合、サーバー側キャッシュ。
