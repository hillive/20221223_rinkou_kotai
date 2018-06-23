# 中間発表リポジトリ

## 使用方法

### 初期設定
1. [ここ](https://github.com/hillive/documents/wiki/リポジトリを作る)を参考にリポジトリを作る
	* リポジトリ名を設定(例:20180808\_Chukan\_syarok)
  * 日付は自分の発表日
2. リポジトリをcloneする
3. クローンしたディレクトリに **レジュメのテンプレート** と **.gitignore** を置く
  * .gitignoreはこのリポジトリをコピーする
  * 注意:.gitignoreを入れる前にaddした場合はゴミファイルがgitに上がってしまうので必ず.gitignoreを最初に入れてから行う
  * .gitignore はgitのリポジトリにアップロードしないファイルが記述されている
4. [slackとの連携をする](https://github.com/hillive/YYYYMMDD_Chukan_syarok#slack%E3%81%A8%E3%81%AE%E9%80%A3%E6%90%BA)

### コマンド
```shell
# 名前が[kirima_syaro]さん発表日が2018/8/8の場合
# リポジトリを作る
$ git clone <URL>
$ cd 20180808_Chukan_syarok

# 作成したディレクトリにこのリポジトリにあるレジュメのテンプレートと.gitignoreを置く

# latexファイルと.gitignoreがちゃんとあるか確認
$ ls -a
.                             .gitignore
..                            20180808_Chukan_syarok
.git                          README.md

# 置いた後に以下のコマンドをいれる
$ git add .
$ git commit -m "commit message"
$ git push -u origin master
```

### slackとの連携
- [ここ](https://github.com/hillive/documents/wiki/GitHubとSlackの連携)見て

### pushの注意点
* **自分の名前のブランチにいることを確認してからpushすること**
* gitの性質上，commitごとにpushをする必要は無いので一呼吸おいてから確認をすること

### gitの使い方を忘れたら
- [創成課題の資料](https://github.com/hillive/documents)
  - [コマンドの確認](https://github.com/hillive/documents/wiki/Git%E5%85%A5%E9%96%80)
- [ぐぐる](https://www.google.co.jp)
- それでもわからなかったら先輩や同期に聞く
