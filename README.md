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

楽天アフィリエイト（https://affiliate.rakuten.co.jp/ 、会員: 北田尚弘）に参加済み。
商品リンクは同サイトの商品検索→「短縮URL」タイプ（`https://a.r10.to/xxxxxx`形式、有効期限10年）で発行し、
`<a class="cta" href="https://a.r10.to/xxxxxx" target="_blank" rel="nofollow noopener">` の形で記事に設置する。

未発行の間だけ、仮リンク（`href="#" data-ad="<service-id>"><span class="tag">仮リンク</span>...`）を暫定的に使う。

- 2026-09-13: `bousai-syunou-box-hikaku.html` の3リンク（頑丈収納ボックス/ベッド下収納ボックス/屋外収納ボックス）を実リンク化済み
- 2026-09-14: 新規記事3本（ブランド比較/家具転倒防止/非常食ストッカー）を実リンク付きで公開。無印良品は楽天市場に出店なし、公式オンラインストア案内のみ
