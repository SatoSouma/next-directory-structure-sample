# ディレクトリ用構成 sample

## public

- 画像など

## src

- コード類はここに纏める

### components

- 各ディレクトリ毎に styles ディレクトリや hooks ディレクトリ(organisms み)が存在する

- atoms
  - 最下位のパーツ、ラベルなど
  - 処理部は書いては行けない
- molecules
  - 2 つ以上のパーツを組み合わせたもの
  - 処理部は書いては行けない
- organisms
  - 結構でかいコンポーネント
  - 処理部はここに書く
- templates
  - pages とほぼ変わらん、最上位コンポーネントに近い
  - 処理部は書いては行けない

### hooks

- page コンポーネント用の hooks を保管

### pages

- ルーティングされる最上位コンポーネント

### utils

- 共通・汎用的な処理を入れる

### types

- ts の型定義ファイルを入れる

### styels

- page コンポーネント用の css ファイルが入る
