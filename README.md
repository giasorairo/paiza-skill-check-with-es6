# about
paiza のスキルチェックでコード書くときに JavaScript(es6) x VSCode 環境下でコーディンしたかったので作った環境。

- ES6 で書いて Node.js で実行できる
- ES6 で書いて jest でテストできる

# 環境
node v16.13.2

# 使い方
- src/paiza.js にコードを書く
  - npm run start で実行
- src/paiza.spec.js にテストコードを書く
  - npm run test でテスト実行
  - テストを常駐させたい場合は npm run test
