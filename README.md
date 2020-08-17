# LaravelChartSample

メモ

・前提としてプロジェクトを作成していてルーティングを済ませていること
コントローラーではソート 済のキー、データを渡している。

## 手順
```Bash
npm install chart.js
````

jsファイル作成

import 'chart.js'でインポート(jsページ内)

webpack.min.jsの編集
```Javascript
mix.js('resources/js/show_chart.js', 'public/js')
```

コンパイル

blade作成