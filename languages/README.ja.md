<p align="center">
  <img src="../assets/hero-banner.svg" alt="Google Maps Scraper - 店舗データを一括取得" width="800">
</p>

<p align="center">
  🌍 <a href="../README.md">English</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | 日本語 | <a href="README.ko.md">한국어</a> | <a href="README.pt-br.md">Português</a> | <a href="README.it.md">Italiano</a>
</p>

<p align="center">
  <a href="https://github.com/gmapsscraper/google-maps-scraper"><img src="https://img.shields.io/github/stars/gmapsscraper/google-maps-scraper?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/gmapsscraper/google-maps-scraper/blob/main/LICENSE"><img src="https://img.shields.io/badge/ライセンス-MIT-blue.svg" alt="MITライセンス"></a>
  <a href="https://microsoftedge.microsoft.com/addons/detail/maps-leads-extractor/pjfinnoomaapaljalipcldkcpankhnaj"><img src="https://img.shields.io/badge/Edge_Add--ons-公開中-0078D7?logo=microsoftedge" alt="Edge Add-ons"></a>
  <a href="https://gmapsscraper.io"><img src="https://img.shields.io/badge/Cloud版-gmapsscraper.io-4f46e5" alt="Cloud版"></a>
</p>

<p align="center">
  <strong>Googleマップ・Bingマップから1,000件以上の店舗情報を3分以内に取得。</strong><br>
  店舗名、電話番号、メール、Webサイト、評価、口コミ、営業時間、GPS座標 — すべてCSVでワンクリック出力。
</p>

---

## Googleマップスクレイピングとは？

**Googleマップスクレイピング**とは、Googleマップの検索結果に表示される店舗・企業情報を自動的に収集する手法です。店舗名、電話番号、住所をひとつずつ手作業でコピペする代わりに、スクレイパーがすべてを自動で処理します。何時間もかかる作業が、数分で完了します。

Googleマップには数百万の店舗が登録されており、連絡先、顧客レビュー、営業時間、WebサイトURL、GPS座標といったデータが公開されています。営業チーム、マーケティング会社、起業家にとって、これは見込み客の宝庫です。

### なぜ企業はGoogleマップのデータを必要としているのか

Googleマップからの**営業リスト作成**の需要は急速に拡大しています。その理由：

- **営業・新規開拓**: 営業チームが業種・エリア・評価で絞り込んだターゲットリストを作成。渋谷で星4.5以上、口コミ100件以上のカフェは、おそらく繁盛していてB2Bサービスの予算もある。

- **市場調査**: 地域ごとの競合密度、価格帯の傾向、顧客の声を把握することで、データに基づいた出店・展開判断ができる。

- **ローカルSEO**: SEO会社がGoogleマップのデータを抽出して、ローカル検索の競合状況を分析し、クライアントのパフォーマンスをベンチマーク。

- **不動産**: 不動産業者や投資家が、物件周辺の商業施設密度を分析して立地評価に活用。

- **人材紹介**: 人材会社が成長中の企業（口コミが急増している、最近オーナー確認された店舗）を見つけて営業先に。

問題は？手作業でのデータ収集は途方もなく時間がかかること。100件の店舗情報を手でコピーすると6時間以上。Googleマップスクレイパーなら3分以内です。

<p align="center">
  <img src="../assets/comparison-chart.svg" alt="手作業 vs 自動化 — Googleマップデータ抽出の比較" width="700">
</p>

---

## 機能一覧

オープンソースのChrome拡張機能で、GoogleマップとBingマップから30以上のデータ項目を抽出。設定不要で、すぐに使えます。

### できること

| 機能 | 説明 |
|------|------|
| **2つのプラットフォーム対応** | GoogleマップとBingマップ |
| **30以上のデータ項目** | 店舗名、電話、Web、評価、口コミ、営業時間、座標… |
| **ワンクリックCSV出力** | Excel、Googleスプレッドシート、CRMにそのまま取り込み可能 |
| **APIキー不要** | ブラウザ内で完結、外部サービス不要 |
| **速度調整可能** | スクロール・クリックの間隔を設定 |
| **自動スクロール＆ページ送り** | 追加結果を自動で読み込み |
| **ダークモード** | 長時間作業でも目に優しい |
| **ドラッグ可能なパネル** | 画面上の好きな位置に配置 |

### プラットフォーム比較

| データ項目 | Googleマップ | Bingマップ |
|-----------|:-----------:|:---------:|
| 店舗名 | ✅ | ✅ |
| 住所（フル） | ✅ | ✅ |
| 電話番号 | ✅ | ✅ |
| Webサイト | ✅ | ✅ |
| 星評価 | ✅ | ✅ |
| 口コミ数 | ✅ | ✅ |
| カテゴリ | ✅ | ✅ |
| 営業時間 | ✅ | ✅ |
| GPS座標 | ✅ | ✅ |
| 価格帯 | ✅ | ✅ |
| オーナー情報 | ✅ | — |
| Place ID | ✅ | — |
| Plus Code | ✅ | — |

<p align="center">
  <img src="../assets/workflow-diagram.svg" alt="Googleマップスクレイパーのワークフロー — 検索→抽出→出力" width="700">
</p>

---

## 活用シーン

<p align="center">
  <img src="../assets/use-cases.svg" alt="Googleマップスクレイパーの業種別活用シーン" width="700">
</p>

### 1. 営業チーム・リード獲得代行

最も多い使い方：**B2B営業リストの構築**。インサイドセールスが抽出データを使ってピンポイントでアプローチ：

- 「新宿 美容院」で検索 → 500件の美容院の電話番号とWebサイトを抽出
- 星4.0以上、口コミ50件以上でフィルタ → 安定した店舗を特定
- CSV出力 → CRMにインポート → アウトリーチ開始

**結果**: 丸一日かけてリストを作る代わりに、10分で質の高いリストが完成。

### 2. 不動産業者

不動産の営業・投資家がGoogleマップデータを活用：

- 物件周辺の商業施設密度を分析
- 成長中の店舗を発見（口コミが多い＝繁盛している）
- 地域の事業者とのネットワーク構築

### 3. 人材紹介・ヘッドハンター

人材会社が営業先を見つける：

- 新規オープンの店舗（口コミ少、最近登録）→ 人手が必要な可能性大
- 急成長中の店舗（口コミ急増）→ 採用活動中の可能性
- 「スタッフ募集中」と記載のある店舗 → 即アプローチ

### 4. SEO代理店

SEOのプロがGoogleマップスクレイピングを活用：

- **競合分析**: クライアントのローカル市場に何社の競合がいるか？
- **サイテーション構築**: NAP（名前・住所・電話）の一貫性を確認
- **口コミモニタリング**: 競合の口コミ頻度とセンチメントを追跡

### 5. マーケットリサーチ

コンサルタントや調査会社がデータを抽出して：

- 地域別の業種集中度をマッピング
- エリア間の価格帯パターンを分析
- 未開拓市場の発見（店舗密度が低い＋人口が多い地域）

---

## 使い方

### ステップ1: 検索する

[Googleマップ](https://www.google.com/maps)または[Bingマップ](https://www.bing.com/maps)を開いて、ターゲットを検索：

- 「渋谷 カフェ」
- 「新宿 美容院」
- 「大阪 税理士」
- 「福岡 居酒屋」

### ステップ2: 抽出する

拡張機能のアイコンをクリック。**Start**を押すと：

1. 表示されているすべての店舗情報を取得
2. 自動スクロールで追加結果を読み込み
3. 各店舗の詳細情報を取得
4. 重複をリアルタイムで除去

### ステップ3: 出力する

**CSV**をクリック — 完了。ファイルはそのまま使えます：

- **CRM**: HubSpot、Salesforce、Pipedrive
- **スプレッドシート**: Googleスプレッドシート、Excel、Airtable
- **メールツール**: Mailchimp、配配メール、SendGrid

---

## インストール方法

### 方法1: Edge Add-ons（おすすめ）

ワンクリック、設定不要：

👉 **[Edge Add-onsからMaps Leads Extractorをインストール](https://microsoftedge.microsoft.com/addons/detail/maps-leads-extractor/pjfinnoomaapaljalipcldkcpankhnaj)**

### 方法2: ソースコードから読み込み

```bash
git clone https://github.com/gmapsscraper/google-maps-scraper.git
# ブラウザ: chrome://extensions/ → デベロッパーモード → パッケージ化されていない拡張機能を読み込む
```

---

## 無料版 vs Pro版

| 機能 | 無料（オープンソース） | Pro（gmapsscraper.io） |
|------|:--------------------:|:---------------------:|
| 基本データ抽出 | ✅ | ✅ |
| Googleマップ | ✅ | ✅ |
| Bingマップ | ✅ | ✅ |
| CSV出力 | ✅ | ✅ |
| 30以上の項目 | ✅ | ✅ |
| **メールアドレス抽出** | — | ✅ |
| **SNSプロフィール** | — | ✅ |
| **大量一括抽出** | — | ✅ |
| **クラウド処理** | — | ✅ |
| **APIアクセス** | — | ✅ |
| **スケジュール実行** | — | ✅ |
| 速度 | ブラウザ依存 | 1,000件以上/3分 |
| 最大取得数 | 約200件 | 無制限 |

<p align="center">
  <a href="https://gmapsscraper.io?ref=github-profile-ja">
    <img src="https://img.shields.io/badge/Pro版を試す-14日間返金保証-4f46e5?style=for-the-badge" alt="Pro版を試す">
  </a>
</p>

---

## よくある質問

### Googleマップのスクレイピングは合法？

公開されている店舗情報の収集は、多くの法域で一般的に合法とされています。店舗名、電話番号、住所は企業自身が公開しているデータです。ただし、レートリミットを守る、データをスパムに使わない、個人情報保護法を遵守する、といった点は必ず守ってください。

### 1回のセッションで何件取得できる？

オープンソース版では、1回の検索で**最大約200件**が現実的です。[Pro版（クラウド）](https://gmapsscraper.io?ref=github-profile-ja)なら実質無制限です。

### Bingマップでも使える？

はい。**GoogleマップとBingマップの両方**に対応しています。どちらのプラットフォームにいるかを自動検出します。

### APIキーは必要？

不要です。拡張機能はブラウザ内で完結し、外部サービスへの接続は一切ありません。

### 対応ブラウザは？

Chromiumベースのすべてのブラウザ：Chrome、Edge、Brave、Opera、Vivaldi、Arc。

### データの精度は？

GoogleマップまたはBingマップに表示されている情報をそのまま抽出するため、ソースと同じ精度です。電話番号と住所の正確性は通常**90%以上**です。

---

## 今すぐ始める

<table>
<tr>
<td align="center" width="33%">
<h3>🆓 無料・オープンソース</h3>
<p>基本データ、30以上の項目、CSV出力</p>
<a href="https://github.com/gmapsscraper/google-maps-scraper">GitHubで見る →</a>
</td>
<td align="center" width="33%">
<h3>📦 Edge Add-ons</h3>
<p>ワンクリック、設定不要</p>
<a href="https://microsoftedge.microsoft.com/addons/detail/maps-leads-extractor/pjfinnoomaapaljalipcldkcpankhnaj">インストール →</a>
</td>
<td align="center" width="33%">
<h3>🚀 Pro Cloud</h3>
<p>メール、SNS、一括、API</p>
<a href="https://gmapsscraper.io?ref=github-profile-ja">無料で試す →</a>
</td>
</tr>
</table>

---

<p align="center">
  <sub>営業チーム、代理店、マーケターのために作りました。<br>
  <a href="https://github.com/gmapsscraper/google-maps-scraper">⭐ スターをお願いします</a> — 他の人が見つけやすくなります。</sub>
</p>
