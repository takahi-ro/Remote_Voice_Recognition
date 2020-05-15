# Remote_Voice_Recognition
リモートミーティングでの音声認識の活用事例

# About / 概要
聴覚障害者が会議に参加しにくい問題があり，音声認識を用いて情報共有しようと試みられています．2020年5月現在，新型コロナウイルスの流行により，リモートにて会議がほとんどになりつつありますが，聴覚障害者が参加しにくく，音声認識を活用できていない課題が今にも残されています．そこで，聴覚障害当事者と所属研究室の皆さんとの協調によって考案した，3つの活用事例を紹介いたします．

<blockquote class="twitter-tweet"><p lang="und" dir="ltr"><a href="https://twitter.com/hashtag/xdiversity?src=hash&amp;ref_src=twsrc%5Etfw">#xdiversity</a> <a href="https://twitter.com/xdiversity_org?ref_src=twsrc%5Etfw">@xdiversity_org</a> <a href="https://twitter.com/hashtag/stayhometokyo?src=hash&amp;ref_src=twsrc%5Etfw">#stayhometokyo</a> <a href="https://twitter.com/hashtag/%E9%9F%B3%E5%A3%B0%E6%96%87%E5%AD%97%E5%A4%89%E6%8F%9B?src=hash&amp;ref_src=twsrc%5Etfw">#音声文字変換</a> <a href="https://t.co/VNKQcZONsR">pic.twitter.com/VNKQcZONsR</a></p>&mdash; 落合陽一 (@ochyai) <a href="https://twitter.com/ochyai/status/1260610691041357825?ref_src=twsrc%5Etfw">May 13, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

# 基本的な考え方
私の考えとしては，**リアルタイムで会話を展開**であり，誤変換を人手による修正は一旦置いといて，各自音声認識に合わせてもらうことにしました．

[Google 音声文字変換](https://play.google.com/store/apps/details?id=com.google.audio.hearing.visualization.accessibility.scribe&hl=ja)


# 課題
- 誤変換
  - 

- 発言タイミング
Google 音声文字変換は，誰かが発言したのか掴みにくい問題があります．そのため，下記の対応を取っています．
  - 主に用いている，zoomやGoogle Meetsは，発言している話者の画面枠が緑色に変換しているため，それで判断する
  - 議事録では，（）などで誰かが発言したのかわかるようにできるだけ残す

- 発言方法
今回，私は発言する際，基本的に音声（口話）で話していますが，音声で話したくない or 話せない人はどうすべきか議論はまだ残されており，たまに話題になっていることもあります．結局，**チャットもしくは手話通訳の配置**しかないとベターになってしまいますが，本来であれば，自然と第一言語である手話で話せるようにしても良いよね…と考えています．

- 呼びかけ&気付き
議論，報告や確認などで聞かれる際に誰かを名前で呼ぶことが聴者文化では一般的ですが，ろう文化では手を振ったりするなどで対応しています．しかし，聴者とろう者が混ざっている状態だと，今は私を呼びかけるために手を振ってきたのか？，それとも，単純に動いているだけ？といったケース，または私の名前が出てきたから私のことを呼んでいるのか？，偶然にも誤変換で出てきただけなのか？というケースなどで，気付きにくいことが度々あります．なので，このラボでは，誤変換されにくく，簡単に言いやすい単語**アンパンマン**と変換されたら私のことを呼んでいると簡単な慣習を設けました（落合さんによる柔軟な発想でアンパンマンになるとは思ってもいなかった事態でした）．
  - 候補に挙がった語一覧
    - アンパンマン
    - バイキンマン
    - ゼータガンダム
    - スポンジボブ

- ハードウェア（製品）
今回，用意したハードウェア（製品）は，PCと比べて一般的に用いるようなものではなく，音楽や映像配信などを趣味にしている人が用いるような製品です．そのため，手元にない方は購入する必要がありますが，やや高価になります．また，新型コロナウイルスの影響により，購入する人が増えてきたため，在庫不足になってしまうなどで，速やかに手に入れにくい状況になっております．
  
- ネットワーク
