+++
draft = true
thumbnail = "images/reNewBlog/thumbnail.png"
tags = ["ブログ"]
date = "2020-03-12T15:59:53+09:00"
lastmod = "2020-04-18T08:34:55+09:00"
title = "ブログのリニューアルを成し遂げたぜ！"
description = "ブログをリニューアルしました。(見た目とその他もろもろ問題点)リニューアルするまでにあったブログの問題点全部改善しました。==バンバン投稿できるようになった！"
+++
## お久しぶりです

どうも、[@mira_tech](https://twitter.com/mira_tech)です。

[前投稿したの](https://www.saltandsugar.tech/post/vscode-tm/)が去年の9月、つまり5ヶ月ぐらい前が最終投稿になっておりました。**てへぺろ**&**あけおめ**

### 理由があるのです。

ちょっと待って！！**理由があるのです！**

---

**このブログ、クソアナログゴミシステム！！！！**

- めんどくさいリスト
	- テーマのアップデートができない(テーマファイルに直接カスタムを書き込んでしまった)
	- 自動デプロイされない(CIの設定で折れた)
	- www.をつけないとアクセスできない(ググるのめんどくさいし〜設定もめんどいし〜)
	- ダークモードがない(明るすぎ)(けどカスタマイズできない)
	- あといっぱい
	
~~書き出してみると全部自業自得なんだよなぁ...たまげたなぁ...~~

このようにめんどくさくて放置状態でした。さーせん(特に自動デプロイないのが厳しい。hugoで生成されたファイルをブラウザからアップするというなんともエンジニアらしくないことするのが辛い)

### 学校なくなった
みなさん新型コロナウィルス大丈夫ですか？

んでみなさんご存知の通り巷で話題の新型コロナウィルスのせいで学校が休校になったんですよね〜

重い腰を上げて**ブログを改装しよう**と思い立ちました

## 成し遂げた
最初は1日で成し遂げるつもりがどんどん伸びていき最終的に5日かけてブログの改装が完了しました。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">ダークモードとライトモードの実装だけやから50行ぐらい書いて1日で改装終わるやろ。→4　日　か　け　て　1　7　4　行　の　ク　ソ　コ　ー　ド <a href="https://t.co/UXf6gGj1OB">pic.twitter.com/UXf6gGj1OB</a></p>&mdash; 🛰🍊🍣🏓🍣ラミゴヒ@mira_tech@ヒゴミラ🍣🏓🍣🍊🛰 (@mira_tech) <a href="https://twitter.com/mira_tech/status/1237682683607576576?ref_src=twsrc%5Etfw">March 11, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

174行のうんコードを書くこともしました。(初めて素の状態からJavaScriptを100行以上書いた)

---
HugoテーマRobustをめちゃくちゃ改造した。(実際レイアウトぐらいしか原型ない)

上のヘッダーでダークモード、ライトモードを切り替えれるようにした！

あとカラフルになりました！ 気づいた人いるかも知れんけど、**[ここ](https://www.saltandsugar.tech/)の記事一覧がカラフルになってて、記事一覧から適当に記事選んで飛ぶと飛んだ先でもその色が引き継がれるんです！** 自慢ポイント！(この機能のせいで書くコードの量が莫大に増えた+うんコード化)

あと自動デプロイでができるようになった！！

[GitHub](https://github.com/mira-tech/Hugo-blog)(誰かうんコード(static/js)直してくれ)にコミットしたらaws-codebuildが勝手にビルドして更新してくれる。これ以上幸せなことはない。

その他もろもろ(URLにwwwつけなくてもアクセスできるように、テーマもきちんとサブモジュールにして別の場所で書き直しました)も**全て解決**

## 最高です
色々このブログの問題も解決して、しかもおしゃれになったのでこれを機に投稿頻度上げていきたいな〜

頑張ります。
