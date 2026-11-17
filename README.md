# sutedoki-data

iOS アプリ「すてどき」が読み込む、東京都の区市町村ごとのごみ収集日データの配信用リポジトリです（GitHub Pages）。

- `v1/manifest.json` … 版・生成日時・SHA-256
- `v1/tokyo.json` … 収集日データ本体（60/62 区市町村）

アプリは約半年ごとに manifest を確認し、新しい版だけを取り込みます。データの生成元はアプリ本体のリポジトリ（非公開）です。

## 出典

- 16区市: [japan-gomi-data](https://github.com/tecolicom/japan-gomi-data)（tecolicom, CC BY 4.0）を加工して利用
- その他: 各区市町村が公表しているごみ収集カレンダー・収集曜日表をもとに作成（大田区は東京都オープンデータ, CC BY 4.0）。各地域の出典はデータ内の `source` を参照

実際の収集日は各区市町村の最新の案内を確認してください。
