# nilgiri-tea

## なにこれ
[・◡・]< [nilgiri-tea.net](http://nilgiri-tea.net)用Tumblrテーマを書き換えよう計画。  
とりあえずriot.js使ってみようプランで書き換え中。  
環境は[この辺](http://qiita.com/yaaah93/items/071a1c573eb763212e48)参考に。
コード周りはReactだけど[この辺](http://qiita.com/monpy/items/b6ebe9bc77b3ad0ffade)を見つつ。


## いまここ
[・◡・]< ひとまず投稿一覧をFetchしてきて画像が出るぐらいの所まできているよ。  
ある程度要素を表示できるぐらいのところまで書けたらスタイルも修正していきたい。

画像はどうしよう…  
photosetの扱いがめんどそう……。

画像クリック→モーダルオープンにすべきかな…

ページネーションを入れて、さらにinfiniteScroll入れる感じかなあ……？
→offsetの実装が必要になってくる

Like/rblgまわりどうすればよいのか調べねば。

## これから
[・◡・]< ひとまずまともに動かしたい。  

最終的にはAWS S3あたりで動かす感じに……？  
個別ページ取得するAPIがないので、そこだけ問題…Staticにする……？

### デザイン改善が最大の課題。
[・◡・]< 特に個別ページがイケてない  
レスポンシブ対応したいよね  
あとは適当にエフェクトとか付けつつ。ただしシンプルめでいきたい。

[・◡・]< ローダー付けような