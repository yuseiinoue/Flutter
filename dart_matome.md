# Flutter まとめノート

## dartまとめ


## [値と型]
- `int`：整数型 → `int a = 10;`
- `double`：小数 → `double pi = 3.14;`
- `String`：文字列 → `String name = 'Dart';`
- `bool`：真偽値 → `bool judge = true;`

## [変数と定数]
- 変数：`var x = 10;` / `int x = 10;`
- 定数（実行時）: `final x = 10;`

## [リスト]
- リストの作成：`List<int> numbers = [1, 2, 3];`
- 要素の追加：`numbers.add(4);`
- インデックスアクセス：`print(numbers[0]);`
- 長さを取得：`print(numbers.length);`

## [if構文]
`int score = 85;
if (score >= 90) {
  print('Excellent');
} else if (score >= 70) {
  print('Good');
} else {
  print('Try again');
}`

## [三項演算子]
`int a = 10;
String result = (a > 5) ? '大きい' : '小さい';
print(result);`

## [switch-case]
`String grade = 'B';
switch (grade) {
  case 'A':
    print('Excellent');
    break;
  case 'B':
    print('Good');
    break;
  case 'C':
    print('Average');
    break;
  default:
    print('Invalid grade');
}`

## [while構文]
`int count = 0;
while (count < 5) {
  print(count);
  count++;
}`

## [for構文]
`for (int i = 0; i < 5; i++) {
  print(i);
}`

## [for-in構文]
`List<String> fruits = ['apple', 'banana', 'orange'];
for (var fruit in fruits) {
  print(fruit);
}`

## [戻り値]
`void main() {
  hello();
}
void hello() {
  print("Hello.");
}`
出力 → "Hello."

## [引数]
`void main() {
  hello("タロー");
  hello("ジロー");
}
void hello(name) {
  print("こんにちは、$name さん！");
}`
出力 → こんにちは、タロー さん！
      こんにちは、ジロー さん！

## [クラス]
`void main() {
  Person me = Person();
  me.name = "Taro";
  me.age = 39;
  me.say();
}
class Person {
  String name = "";
  int age = 0;
  void say() {
    print("Hi, I'm $name. I'm $age years old.");
  }
}`

## [コンストラクタ]
