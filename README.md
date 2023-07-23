# APIアプリ
　●締切日：2023/6/16
　●提出日：2023/7/23
## DEMO
## まずはじめに
とにかく大きく遅れてます。
今後のことを考えると何かを変えないと。。
みなさん、本当にフォローして下さってるのに。がんばらないと。

## 紹介と使い方
ゴルフが好きなので、お気に入りのゴルフ場リストを作りました。

## 工夫した点
localStorageからゴルフ場データを抽出する時に、他のurlからlocalStorageに保存したデータを拾わないようにするために、
keyの接頭辞に'golfcourse_key,'を付けて保存するようにしました。
表示する時に、この'golfcourse_key,'が接頭辞となっているkeyのvalueだけを抽出するようにしました。
ただ保存の際、localStorageのアドレスを自分で指定できるのであれば、他のURLの保存先とlocalStorageを共有しなくて済むので、
そっちのほうが良いと思いました。


## 苦戦した点
1.localStorageにjpgを保存する方法が分かりませんでした。

2.登録したゴルフ場を地図上にピン止めしてリスト表示したかったのですが、そこまでの時間がありませんでした。

## 参考にした web サイトなど
授業で使った実際のコード、
授業で使った資料、
Ilty、
Chat-GPT（よくわからないコードや書き方がでてきても、そのまま貼り付けないで理解するように努めました）

## その他
毎日一人反省会の時間を作り、原因を洗い出し、対策を考え改善します。
