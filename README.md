# GPT-4 で metabase のサンプルデータを処理する

- metabase を docker で動作させた。
- sample data (8 つ) を csv でダウンロードし、zip に纏めた。
- GPT-4 で その zip から sqlite に imoort することを指示し、sqlite ファイルをダウンロードした。
- GPT-4 に sqlite ファイルをアップロードし、いくつかの質問をした。


```
売上の遷移を折線グラフにしてください。

四半期単位での売上の遷移を折線グラフにしてください

代表的な KPI で分析レポートを作成してください。適宜 グラフも添えて説明をしてください。
今後の行動の提案もお願いします。
```
