# JavaScript基礎 (日本語版)

## 1. JavaScriptの出力
JavaScriptはさまざまな方法でデータを出力できます：
- `window.alert()`: アラートボックスをポップアップ
- `document.write()`: HTML出力に書き込む
- `innerHTML`: HTML要素に書き込む
- `console.log()`: ブラウザのコンソールに書き込む

## 2. JavaScriptの構文
- JavaScriptはスクリプト言語です
- 変数を宣言するには`var`、`let`、または`const`キーワードを使用
- 値を代入するには等号`=`を使用

## 3. JavaScriptのステートメント
- JavaScriptステートメントはブラウザへのコマンドです
- ステートメントは通常セミコロン`;`で終わります
- コードブロックは中括弧`{}`で囲みます

## 4. JavaScriptのコメント
- 単一行コメント：`// これは単一行コメントです`
- 複数行コメント：`/* これは複数行コメントです */`

## 5. JavaScriptの変数
- 変数は情報を格納するコンテナです
- 変数の宣言：`var x;`、`let y;`、または`const z = 5;`
- 変数の型：
  - 数値（整数または浮動小数点）
  - 文字列
  - ブール値
  - 配列
  - オブジェクト
  - Undefined
  - Null

## 8. JavaScriptの条件文
- if文
```javascript
if (条件) {
  // コードブロック
} else if (条件) {
  // コードブロック
} else {
  // コードブロック
}
```
- switch文
```javascript
switch(式) {
  case x:
    // コードブロック
    break;
  case y:
    // コードブロック
    break;
  default:
    // コードブロック
}
```

## 9. JavaScriptのループ
- forループ
```javascript
for (let i = 0; i < 5; i++) {
  // コードブロック
}
```
- whileループ
```javascript
while (条件) {
  // コードブロック
}
```
- do...whileループ
```javascript
do {
  // コードブロック
} while (条件);
```

## 10. JavaScriptの関数
- 関数定義
```javascript
function 名前(引数1, 引数2, 引数3) {
  // コードブロック
}
```
- 関数式
```javascript
const x = function(a, b) {return a * b};
```
- アロー関数
```javascript
const x = (a, b) => a * b;
```