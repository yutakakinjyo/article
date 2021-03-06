# Tech Lead という仕事内容の考察

[rebuild.fm - ep.126](http://rebuild.fm/126/) で話に上がってた [Good Tech Lead, Bad Tech Lead](https://medium.com/swlh/good-tech-lead-bad-tech-lead-948b2b806d86#.1f8r31vk2) を読んだ。
開発現場の中で、何が「良い Tech Lead」で何が「悪い Tech Lead」なのかが書かれている。Tech Lead とはチームの中で技術の方向性を決めるリーダーの行うことだと思もう。

## 僕は Tech Lead してる?

気になったのは、Tech Lead という職能(?)があることで、僕の今やっている仕事とすごく近い気がする。

僕は今は、短いスパンのプロジェクトに参加していて、そこで主に`コードレビュー`、`テストの自動化`と`開発フローの取り決め`を担当している。機能を追加するためのコードはほとんど書いていない。コードを書くときはリファクタリングするときぐらいだ。

記事に書いてあるが、

> To good tech leads, details matter. Code quality, code reviews, and testing are just as important as shipping on time.

の部分がほぼ一致している。逆に一致していないのは、それ以外のところだ。プロダクトの方向性については、あまり関与していない。PM やメンバーにドメインについて有識者がいるため、そちらに任せてある。なので自分のことを Tech lade をしている。と言っていいかは判断しかねている。

## Tech Lade の必要性

やっていて思うことは、Tech Lead という立場の人は必要なのだろうと思う。  
プログラムを書くには集中力がいる。機能追加のためにプログラムを書く人は、その時はそれだけに集中できるのが望ましい。  
だから、その時にはそれ以外のことは他の人が担当すると良い。その一部を担うのが Tech lead なんだと思う。
プログラムを書いてる時に、テストが自動化されてなかったり、開発フローが明確に定められてなかったりすると、プログラム書く事以外で作業の効率を落としてしまう。
だから Tech leader が先読みをして、詰まりそうなところを先に埋めておく方がいい。

また、全体の統一性を維持することも必要だと思う。僕はここ二ヶ月ただひたすらにコードレビューをしてきた。そこでは、「こっちではこういう書き方をしているので、そこに合わせてくれ。」とレビューする機会がかなり多かった。もしかするともっとキチンと規約を定めると、そういうことは起きなかったかもしれないが、最初から規約を決めるのは難しかったという言い訳をしておく。またメンバーに互いにコードレビューをさせる手もあったが、適切にコードレビューできる能力はないと判断したので、僕がすべてレビューした。
とにかく、それで全体のコードがあまりチグハグにならずに済んでいるとは思う。

## Tech Leade に必要な能力

知識もそうだが、経験も必要になってくると思う。知識だけではどうしても先読みできない部分が出てくる。
経験から、「だいたいこういう時はこうなる」とか「このコードはいづれ変更の妨げになる」とかわかってくる。
