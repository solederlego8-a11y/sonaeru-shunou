# そなえる収納

賃貸・一人暮らし向けの防災収納メディア。防災グッズの中身ではなく「どこに・どう収納するか」に特化。

- 公開URL: https://solederlego8-a11y.github.io/sonaeru-shunou/
- リポジトリ: https://github.com/solederlego8-a11y/sonaeru-shunou

## 構成

```
index.html            トップページ
guide.html            完全ガイド（記事一覧のハブ）
blog.html             新着順の記事一覧
about.html            サイトについて・広告表示ポリシー
articles/*.html       個別記事
assets/style.css      共通CSS
```

サイトは静的HTML。`main`ブランチにpushするとGitHub Pagesが自動的に再ビルド・公開する。

## 戦略資料

事業戦略・キーワード・記事テンプレート・90日計画は「防災収納ブループリント」（Artifact）を参照。
主軸: 「賃貸・一人暮らしの防災収納」1テーマに絞って開始。マンション停電対策・車載防災は却下。

## 楽天アフィリエイトリンクについて

記事内の商品リンクは、実際の楽天アフィリエイトIDが判明するまで仮リンク
（`<a class="cta" href="#" data-ad="<service-id>"><span class="tag">仮リンク</span>...`）で運用する。
実リンクが判明したら `href` を差し替え、`<span class="tag">仮リンク</span>` を削除する。
