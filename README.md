# About Me

<p align="center"> 
  <a href="https://github.com/gtaiyou24/gtaiyou24/">
    <img src="https://komarev.com/ghpvc/?username=gtaiyou24" alt="gtaiyou24" />
  </a>
  <a href="http://twitter.com/tm_taiyo">
    <img height="20" src="https://img.shields.io/twitter/follow/tm_taiyo?label=Twitter&logo=twitter&style=flat" />
  </a>
  <a href="https://github.com/gtaiyou24">
    <img height="20" src="https://img.shields.io/github/followers/gtaiyou24?label=follow&logo=github&style=flat" />
  </a>
  <a href="http://qiita.com/gtaiyou24">
    <img height="20" src="https://qiita-badge.apiapi.app/s/gtaiyou24/posts.svg" />
  </a>
  <a href="http://qiita.com/gtaiyou24">
    <img height="20" src="https://qiita-badge.apiapi.app/s/gtaiyou24/contributions.svg" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/%E5%A4%A7%E8%80%80-%E7%94%B0%E6%9D%91-a5a028aa/">
    <img src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" alt="田村大耀" height="30" width="30" data-canonical-src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" style="max-width:100%;">
  </a>
  <a href="https://www.wantedly.com/id/taiyo_tamura">
    <img src="https://d1dlw0u96vqtxd.cloudfront.net/images/home/brand_assets/mark-wantedly@2x.png" alt="田村大耀" height="30" width="43" data-canonical-src="https://d1dlw0u96vqtxd.cloudfront.net/images/home/brand_assets/mark-wantedly@2x.png" style="max-width:100%;">
  </a>
  <a href="https://twitter.com/tm_taiyo">
    <img src="https://seeklogo.com/images/T/twitter-logo-A84FE9258E-seeklogo.com.png" alt="田村大耀" height="30" width="43" data-canonical-src="https://seeklogo.com/images/T/twitter-logo-A84FE9258E-seeklogo.com.png" style="max-width:100%;">
  </a>
</p>

# Portfolio
## 暗号通貨の自動売買システム

投資戦略をもとに暗号通貨の投資を行うシステム群。<br>
2021年6月現在は主要暗号通貨に限定して取引を行っていますが、今後は為替や株式にも範囲を広げる予定です。

本システムはマイクロサービスアーキテクチャ、DDDを採択しており、以下のリポジトリから構成されています。

| リポジトリ | 説明 |
|:------:|:-----|
| [market-data-curator](https://github.com/gtaiyou24/market-data-curator) | 市場データを収集するシステム |
| \[Secret\] [feature-analysts](https://github.com/gtaiyou24/feature-analysts) | 市場データを指標や予測値など情報のあるシグナルに変換するシステム |
| \[Secret\] [strategist](https://github.com/gtaiyou24/strategist) | シグナルを実際の投資アルゴリズムに変換する |
| \[Secret\] [asset-trader](https://github.com/gtaiyou24/asset-trader) | アルゴリズム戦略をもとに資産取引を行うシステム |

## Epic Robot - 汎用型クローリングシステム
各Webサイトからデータを収集する汎用型のクローリングシステム。各サイトのデザインに依存せずに、適切なデータを自動的に抽出できます。

収集可能なデータ

 - 記事(article) : タイトル、記事本文、更新日、サムネイル画像、meta情報、ページURL
 - 商品(item) : 商品名、ブランド名、価格、商品画像一覧、レビュー一覧、ページURL
 - 会社/組織(company/organization) : coming soon

| リポジトリ | 説明 |
|:---------|:-----|
| [epic-crawler](https://github.com/gtaiyou24/epic-crawler) | Webサイトをクローリングし、htmlページをダウンロードするシステム |
| \[Secret\] [epic-scraper](https://github.com/gtaiyou24/epic-scraper) | ダウンロードしたhtmlページからデータをスクレイピングするシステム |
| \[Secret\] [epic-robot-management](https://github.com/gtaiyou24/epic-robot-management) | Epic Robotの管理ツール |

## Techosity - テックブログ検索アプリ
各IT企業が投稿しているテックブログを収集し、検索を行うサービスです。

| リポジトリ | 説明 |
|:-------|:-----|
| [techosity-searcher](https://github.com/gtaiyou24/techosity-searcher) | 検索エンジン |
| [techosity-indexer](https://github.com/gtaiyou24/techosity-indexer) | 指定されたデータをインデックスするプログラム |

## Greeedy - ファッションアイテム検索アプリ
モール型のショッピングサイトに出店していないDHOLIC,LOCONDO,GRLなどの自社ブランドで販売している商品を収集し、一括で検索できるサービス。

| リポジトリ | 説明 |
|:--------:|:-----|
| [GreeedyiOS](https://github.com/gtaiyou24/GreeedyiOS) | iOSアプリ |
| [greeedy-searcher](https://github.com/gtaiyou24/greeedy-searcher) | バックエンドアプリケーション |

## ファッションコーディネートの生成
coming soon

## 画像検索
cifarを使って、画像検索のシステムを開発しました。

[ml-image-search](https://github.com/gtaiyou24/ml-image-search)

## 機械学習/統計全般
機械学習/統計全般の自作パッケージをまとめたリポジトリです。

 - 分類
 - 回帰
 - クラスタリング
 - 生存時間解析
 - 一般化線形モデル
 - 計量経済学
 - 時系列解析
 - ...

[ml-algorithm](https://github.com/gtaiyou24/ml-algorithm)

## 自然言語処理
[ml-nlp](https://github.com/gtaiyou24/ml-nlp)

## 画像認識
[ml-image-recognition](https://github.com/gtaiyou24/ml-image-recognition)

## 推薦システム
[recommender](https://github.com/gtaiyou24/recommender)

## DEV系

| リポジトリ | 説明 |
|:------:|:-----|
| [dev-ddd](https://github.com/gtaiyou24/dev-ddd) | ドメイン駆動設計 |
| [dev-db](https://github.com/gtaiyou24/dev-db) | DB |
| [dev-aws](https://github.com/gtaiyou24/dev-aws) | AWS |
| [dev-Linux](https://github.com/gtaiyou24/dev-Linux) | Linux |
