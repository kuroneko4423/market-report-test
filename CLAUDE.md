# タスク
`RSS一覧`の各リンク先のニュースを読み取り、本日の株式市場（日本、米国）の動向を予想したレポートを作成する。

# ルール
- ディレクトリ構成は`reports`配下に、YYYY,MM,DDディレクトリをそれぞれ階層構造で配置
- `reports`ディレクトリ配下に対象日付のDDディレクトリを作成する。
- 月初もしくは当日の月のディレクトリがない場合はMMディレクトリを作成後にDDディレクトリを作成する。
- 年初もしくは当日の年のディレクトリがない場合はYYYYディレクトリを作成後にMM,DDディレクトリも作成する。
- ファイル名は`markets-report-YYYYMMDD.md`とする。

# RSS一覧

## 一般ニュース・新聞

### 日経新聞

| ラベル | URL |
|---|---|
| 速報 | https://assets.wor.jp/rss/rdf/nikkei/news.rdf |
| 政治・経済 | https://assets.wor.jp/rss/rdf/nikkei/economy.rdf |
| ビジネス | https://assets.wor.jp/rss/rdf/nikkei/business.rdf |
| マーケット | https://assets.wor.jp/rss/rdf/nikkei/markets.rdf |
| テクノロジー | https://assets.wor.jp/rss/rdf/nikkei/technology.rdf |
| 国際・アジア | https://assets.wor.jp/rss/rdf/nikkei/international.rdf |
| スポーツ | https://assets.wor.jp/rss/rdf/nikkei/sports.rdf |
| 社会 | https://assets.wor.jp/rss/rdf/nikkei/society.rdf |
| 地域 | https://assets.wor.jp/rss/rdf/nikkei/local.rdf |

### ロイター

| ラベル | URL |
|---|---|
| トップニュース | https://assets.wor.jp/rss/rdf/reuters/top.rdf |
| ワールド | https://assets.wor.jp/rss/rdf/reuters/world.rdf |
| マーケット | https://assets.wor.jp/rss/rdf/reuters/markets.rdf |
| 経済 | https://assets.wor.jp/rss/rdf/reuters/economy.rdf |
| ビジネス | https://assets.wor.jp/rss/rdf/reuters/business.rdf |
| オピニオン | https://assets.wor.jp/rss/rdf/reuters/opinion.rdf |
| ライフ | https://assets.wor.jp/rss/rdf/reuters/life.rdf |

### ブルームバーグ

| ラベル | URL |
|---|---|
| マーケット | https://assets.wor.jp/rss/rdf/bloomberg/markets.rdf |
| ファイナンス | https://assets.wor.jp/rss/rdf/bloomberg/finance.rdf |
| 国際情勢 | https://assets.wor.jp/rss/rdf/bloomberg/international.rdf |
| 企業 | https://assets.wor.jp/rss/rdf/bloomberg/companies.rdf |
| テクノロジー | https://assets.wor.jp/rss/rdf/bloomberg/technology.rdf |
| 経済・政策 | https://assets.wor.jp/rss/rdf/bloomberg/economics.rdf |
| オピニオン | https://assets.wor.jp/rss/rdf/bloomberg/opinion.rdf |

### 産経新聞

| ラベル | URL |
|---|---|
| 速報 | https://assets.wor.jp/rss/rdf/sankei/flash.rdf |
| 社会 | https://assets.wor.jp/rss/rdf/sankei/affairs.rdf |
| 政治 | https://assets.wor.jp/rss/rdf/sankei/politics.rdf |
| 経済 | https://assets.wor.jp/rss/rdf/sankei/economy.rdf |
| 国際 | https://assets.wor.jp/rss/rdf/sankei/world.rdf |
| スポーツ | https://assets.wor.jp/rss/rdf/sankei/sports.rdf |
| エンタメ | https://assets.wor.jp/rss/rdf/sankei/entertainments.rdf |
| ライフ | https://assets.wor.jp/rss/rdf/sankei/life.rdf |

### 読売新聞

| ラベル | URL |
|---|---|
| 新着 | https://assets.wor.jp/rss/rdf/yomiuri/latestnews.rdf |
| 社会 | https://assets.wor.jp/rss/rdf/yomiuri/national.rdf |
| 政治 | https://assets.wor.jp/rss/rdf/yomiuri/politics.rdf |
| 経済 | https://assets.wor.jp/rss/rdf/yomiuri/economy.rdf |
| 国際 | https://assets.wor.jp/rss/rdf/yomiuri/world.rdf |
| テクノロジー | https://assets.wor.jp/rss/rdf/yomiuri/science.rdf |
| エンタメ・文化 | https://assets.wor.jp/rss/rdf/yomiuri/culture.rdf |
| 社説 | https://assets.wor.jp/rss/rdf/yomiuri/editorial.rdf |

## その他

### みんかぶ FX/為替

| ラベル | URL |
|---|---|
| 要人発言 | https://assets.wor.jp/rss/rdf/minkabufx/statement.rdf |
| 株式 | https://assets.wor.jp/rss/rdf/minkabufx/stock.rdf |
| 商品/債券 | https://assets.wor.jp/rss/rdf/minkabufx/commodity.rdf |