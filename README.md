# nadesiko3-fizzbuzz

プログラミング言語「[なでしこ3](https://github.com/kujirahand/nadesiko3)」で Fizz Buzz を実装する際に便利な関数を提供する NAKO3 プラグインです。

## 利用方法について

いくつかの取り込み方法があります。

### GitHub から直接取り込む

```nako3
!「https://raw.githubusercontent.com/nekonoshiri/nadesiko3-fizzbuzz/refs/tags/v1.0.0/fizzbuzz.nako3」を取り込む。

Xを1から15まで繰り返す
　　XのFizzBuzzを表示。
ここまで。
```

### なでしこ貯蔵庫から取り込む

[なでしこ3貯蔵庫](https://n3s.nadesi.com) でも公開しているため、そちらからも取り込めます。

https://n3s.nadesi.com/show/fizzbuzz

```nako3
!「貯蔵庫:fizzbuzz.nako3」を取り込む。

Xを1から15まで繰り返す
　　XのFizzBuzzを表示。
ここまで。
```

## 開発環境について

このリポジトリ自体の開発を行う際に必要な情報を以下に示します。

### 必要なもの

- Node.js (v24 以上)
- npm

### 準備

以下のコマンドで依存パッケージをインストールします。

```sh
npm install
```

### 利用できるスクリプト

- `npm test`: ユニットテスト ([fizzbuzz.test.nako3](fizzbuzz.test.nako3)) を実行します。

## ライセンスについて

CC0 1.0 Universal です。パブリックドメインであり、著作権による制限を受けず自由に使用できます。そのため単にコピー＆ペーストして利用しても問題ありません。

※ 当ファイル (README) 内の表記と [LICENSE](LICENSE) ファイルの表記が異なる場合は [LICENSE](LICENSE) ファイルを優先します。

なお、プログラミング言語「なでしこ3」およびそれに関連するものについてはそれぞれのライセンスに従ってください。
