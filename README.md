# sandbox-scraping-organization
CANPANFIELDSからNPOの情報をスクレイピングするサンプル.  
直近で必要だったので、とりあえず動けばいいやの精神で雑に作った.

## USAGE

```.sh
npm run fetch-link
npm run scrape
```

## OUTPUT
以下の情報がCSV形式（カンマ区切り）で取得される.

* 法人の種類
* 団体名（法人名称）
* 代表者役職
* 代表者氏名
* 郵便番号
* 都道府県
* 市区町村
* 詳細住所
* 団体ホームページ
* 団体ブログ
* Facebook
* Twitter
* 代表者ホームページ（ブログ）
* 寄付
* ボランティア
* 関連ページ
* 閲覧書類
* お問い合わせ用メールアドレス
* 電話番号
* 連絡先区分
* 連絡可能時間
* 連絡可能曜日
* 備考
* 助成金・補助金・物品等、他の組織から受けた支援の実績
* 他のNPO・市民活動団体との協働、他の学協会との共同研究・協働の実績
* 企業・団体との協働・共同研究の実績
* 行政との協働（委託事業など）の実績
* カテゴリ
* サブカテゴリ

