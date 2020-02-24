# satysfi-enumitem

`enumitem` パッケージは，
箇条書き（番号付きリスト，番号なしリスト，定義リスト）を
[SATySFi](https://github.com/gfngfn/SATySFi) で実現するパッケージです．
LaTeX の [enumitem パッケージ](https://www.ctan.org/pkg/enumitem) から名付けました．

このパッケージは以下の機能を提供しています．

- 標準パッケージ (`itemize`) に比べ自由度およびカスタマイズ性の高い箇条書きコマンド
- ネスト可能な番号付き箇条書き環境
- 定義リスト

## インストール

SATySFi のパッケージマネージャである
[Satyrographos](https://github.com/na4zagin3/satyrographos)
を用いてインストールできます．
Satyrographos そのものをインストールした後（詳細は
[README of Satyrographos](https://github.com/na4zagin3/satyrographos/blob/master/README.md)
をご覧ください），
ターミナルで以下のように叩けばインストールされます:

```
opam install satysfi-class-slydifi
satyrographos install
```

インストールが完了した後は，
プリアンブル部分（`.saty` ファイルの冒頭）で以下の文を記述することで
パッケージで提供するコマンドを使えるようになります．

```
@require: enumitem/enumitem
```

## 使い方

[ドキュメント](doc/enumitem.pdf) をご覧ください．


## ライセンス

MIT
