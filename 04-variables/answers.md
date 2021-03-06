# 変数の宿題の解答

## 変数の宣言と代入の方法

1. `let`, `const`, `var`
2. キーワードの1つを使って `fruit` という変数を宣言し、`apple` という文字列を代入してください。

```js
let fruit = "apple";
```

3. キーワードの1つを使って `height` という変数を宣言し、`185` という数値を代入してください。

```js
const height = 185;
```

4. キーワードの1つを使って `weather` という変数を宣言し、`sunny` という文字列を代入してください。

```js
var weather = 'sunny';
```

* `let`, `const`, `var` が出てくれば順番は気にしません。

## 変数の再代入 - 基礎

1. 再代入できる変数を宣言しましょう。`fruit` という名前にして、`apple` という文字列を最初は代入してください。

```js
let fruit = "apple";
```

2. `console.log` を使って、`fruit` の中身を右側に表示してみてください。

```js
console.log(fruit);
```

* ここでは変数の中身をコンソールに出したいから、以下ではないことに注意。

```js
console.log("fruit");
```

3. `fruit` に `orange` を再代入してください。

```js
fruit = "orange";
```

* 再代入するときは、変数を宣言するキーワードはあってはいけません。
* 変数を宣言すること＝変数を新しく作ることだからです。

4. `console.log` を使って、`fruit` の中身を右側に表示してみてください。

```js
console.log(fruit);
```

5. 2番と5番で何が違ったかを理解してください。

2番では `apple` が表示されたのに、5番では `orange` が表示されましたよね。

## 変数の再代入 - 中級

1. 再代入できる変数を宣言しましょう。`number` という名前にして、`1` を最初は代入してください。

```js
let number = 1;
```

2. `number` という変数に、`number` に 1加算した数を代入します。

```js
number = number + 1;
```

3. 2番を5回繰り返してください（2番を含めて合計5回）。

```js
number = number + 1;
```

4. `console.log` を使って、`number` の中身を右側に表示してみてください。何が表示されますか？

```js
console.log(number);
```

これで `6` が表示されましたよね。
