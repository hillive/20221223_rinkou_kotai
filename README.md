# 発表テンプレリポジトリ

## 使用方法

### 初期設定
1. [ここ](https://github.com/hillive/documents/wiki/リポジトリを作る)を参考にリポジトリを作る
	* リポジトリ名を設定(例:20180808\_Chukan\_syarok)
  * 日付は自分の発表日
2. 作ったリポジトリにレジュメテンプレートフォルダを入れる
3. [slackとの連携をする](https://github.com/hillive/YYYYMMDD_Chukan_syarok#slack%E3%81%A8%E3%81%AE%E9%80%A3%E6%90%BA)

### コマンド
```shell
# 中間発表の場合
# 名前が[kirima_syaro]さんの「中間」発表の日が2018/8/8の場合

# 作ったリポジトリをcloneする
# github上でつくったリポジトリにあるQuick setupのhttpsのURLをコピー
$ git clone <URL>
$ cd 20180808_Chukan_syarok

# 作成したディレクトリにこのリポジトリにあるレジュメのテンプレートの名前を変更してからおく

# テンプレートフォルダがちゃんとあるか確認
$ ls -a
.                             ..
20180808_Chukan_syarok        .git

# 置いた後に以下のコマンドをいれる
$ git add .
$ git commit -m "commit message"
$ git push -u origin master
# -u origin master は最初の一回目だけ．2回目以降は git push だけでいける．
```

### slackとの連携
- [ここ](https://github.com/hillive/documents/wiki/Slack%E3%81%A8%E3%81%AE%E9%80%A3%E6%90%BA)見て

### .texやディレクトリの名前変更
`YYYYMMDD_AAAA_syarok.tex`の名前を必ず変更してください。

輪講：YYYYMMDD_Rinkou_syarok.tex

中中間：YYYYMMDD_Chuchukan_syarok.tex

中間：YYYYMMDD_Chukan_syarok.tex

最終：YYYYMMDD_Sotsuken_syarok.tex

YYYY :西暦
MM　：月
DD　：日
syarok :名前＋苗字の最初の1文字(例の場合はkirima syaroのkとsyaro)

### pushの注意点
- 1回のコミットごとに毎回pushしない
  - gitの性質上，commitごとにpushをする必要は無いので一呼吸おいてから確認をすること
  - 1日の終わりや，作業の区切りがついた時にpush

### gitの使い方を忘れたら
- [創成課題の資料](https://github.com/hillive/documents)
  - [コマンドの確認](https://github.com/hillive/documents/wiki/Git%E5%85%A5%E9%96%80)
- [ぐぐる](https://www.google.co.jp)
- それでもわからなかったら先輩や同期に聞く
