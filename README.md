# texでのレポート作成のサンプル

***

レポートのテンプレートTexファイルです．

テンプレートの書き方はあくまで例なので，各自書きやすいように構成を変更してください．  
レポート作成の際には，内容として

- 解析の目的
- データの説明，解析手法
- 結果
- 考察
 
を入れるようにしてください．

### 使い方

terminal で以下を入力

```sh
$ platex report.tex
```

これで `report.dvi` ファイルなどが作られる．その後，以下を入力．

```sh
$ dvipdfmx report.dvi
```

これで `report.pdf` が作られる．
