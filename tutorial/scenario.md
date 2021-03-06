# シナリオ

## 用語集

はじめにこのワークショップで使う用語を説明します。

  * 進行役：ワークショップを進行する役割の人（すでにOSSの開発に参加している人）
    * 1人
  * 参加者：OSSの開発に参加したいけどまだ参加したことがない人・参加したことはあるけどまだ自信がない人
    * 複数人
  * メンター：参加者をサポートする役割の人（すでにOSSの開発に参加している人）
    * 複数人

## 目的

「OSS Gateワークショップ（チュートリアル）」の目的は「OSS開発に参加する最初の一歩を支援すること」です。

## 対象

  * OSSの開発に参加したいけどまだ参加したことがない人
  * OSSの開発に参加したことはあるけどまだ自信がない人

## 目的の実現方法

OSSの開発に参加したいけどまだ参加したことがない人が参加していない理由は「漠然とした不安がある」からです。このワークショップでは「不安」を解消することによりOSS開発に参加する最初の一歩を支援します。

「不安」の原因は次の通りです。

  * 「やり方」を知らないから
  * やったことがないから
  * 「失敗が怖い」から

これらの「不安」の原因を解決するために次のことを実施します。

  * 「やり方」を伝える
  * 「やり方」を実際にやってみる
  * やるときは「失敗」しても大丈夫な状況でやる

具体的には次の方法を実施して「不安」を取りのぞきます。

  * オススメのOSS開発参加方法を紹介
  * オススメの方法を実践
  * 対象OSSはメンターが開発に関わっているOSS

OSSの開発に参加する方法は無数にありますが、「好きなようにやっていいんだよ」と言うと不安を増す原因になってしまいます。「好きなように」と言われてもそもそもどのような「やり方」を選べるかもわからないからです。

このワークショップでは、OSS Gateがオススメする方法を「1つだけ」説明し、実際に参加者が「やってみます」。あえて1つに限定することにより迷いポイントが減り、不安を軽減できるからです。

参加者がオススメの方法を試すとき、「こんなissueを立てて嫌がられないかな…」と「不安」にならないよう、開発対象のOSSはメンターが開発に関わっているOSSにします。メンターからその場で「それをやっても大丈夫だよ、やってみよう！」と言ってもらえたら、その「不安」を取りのぞけるからです。

## 目的達成の評価方法

ワークショップ後、自分1人でもOSSの開発に参加できる「気がするか」どうかを判断基準とします。「気がする」なら、OSS開発への心理的敷居は十分に下がっていて、OSS開発参加への具体的なとっかかり方法が身についた、と判断します。

## 大事にしたいこと

参加者：

  * 実際にやってみる！（経験すれば多くの不安は解消するはず！）
  * 楽しむ！（経験すれば楽しいことがわかるはず！）

メンターの人の動き方の方針：

  * 答えを教えない（開発に使う言語・開発対象のOSSが多様なので知らないことも多いはず）
    * 代わりに一緒にやる。自分のPCでも並行して作業してわかったら教える、ではなく、参加者のPCで一緒に作業ということ。そのとき、自分がどうして次にこう行動をしようとしているのかの理由を伝えながら一緒に作業する。
  * 自分ならこういうときにどう考えてどう行動するかを伝える
  * 自分がフィードバックを受ける側ならこう受け取る、ということを伝える

## 開始前

  * 参加者はネットワークの設定をすること
  * メンターはネットワークの設定をすること
  * 進行役とメンターは参加者と話して参加者が開発対象とするOSSを決める
    * 次のことを加味しながら決める。OSSの技術的な難易度はそれほど重視しなくてよい。
      * 参加者が使っているOSSにする
      * 参加者が困っているOSSにする（インストールがうまくいかないとか）
      * メンターが開発に関わっているOSSにする

## 10:30 アイスブレイク

  * 参加者・メンターそれぞれ同じテーブルの人たちに自分がどうしてOSS Gateに関わっているかを話す
  * メンターは参加者と話して参加者が開発対象とするOSSを決める
    * 次のことを加味しながら決める。OSSの技術的な難易度はそれほど重視しなくてよい。
      * 参加者が使っているOSSにする
      * 参加者が困っているOSSにする（インストールがうまくいかないとか）
      * メンターが開発に関わっているOSSにする
  * [作業ログissueテンプレート](https://github.com/oss-gate/workshop/issues/4)を元に自分用の作業ログissueを作る

## 10:50 OSS開発手順を説明

目的：

  * 参加者がどうやってOSS開発に着手すればよいかわかること

目的のために達成したいこと：

  * 進行役はスライドを使って↓に書いているやり方を説明する。（スライドはoverview/または↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/oss-gate-workshop-tutorial-overview/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/oss-gate-workshop-tutorial-overview)
  * 一通りの流れがわかる
    * 頭でわかる（知識としてわかる）
    * 見てわかる（実際に自分ができなくてもいい。頭でわかったと思ったことが実際に行われていると知覚できればそれでいい。）

やること：

  * 一通りの流れを説明する
  * 説明した流れを実際のOSSに対してやってみせる
    * 説明の復習と説明だけではピンとこないところの補完、という意図
    * 開発対象のOSSはTODOとする

## 11:00 開発対象OSSを動かす

目的：

  * OSS開発に着手したときに最初にやるべき「動かすこと」を実際にやる

目的達成のために達成したいこと：

  * 困ったら相談するという習慣を身につけて欲しい
    * 実際はリモートで相談することになるが、まずは隣同士、グループ内で相談できるようになる
  * 動かすことに集中する
    * 他のことに手を出したくなるかもしれないけど、まず動かすことが大事、ということを覚えてもらう
  * ドキュメントに不備があるときに、文句を言う（Twitterでアピールするとか）よりも、次にドキュメントを読んだ人が困らないように直しておこう、と考える習慣を身につけてもらう
    * 文句を言うことはスゴイことでもカッコイイことでもない！文句を言っている時間を使って直そう。

やること：

  * 開発対象のOSSをforkする
  * ドキュメント（READMEなど）に書いている通りにインストールしてみる
    * ドキュメントにtypoや古い記述など不備があったら作業ログissueにメモしておく。理由は後でpull requestするから。
    * インストール方法や使い方をググる前に公式ドキュメントを参照する習慣をつける。
      * ググって見つかる非公式の情報がないと使えないOSSよりも公式ドキュメントを読めばわかるOSSにするべきで、そうなっていないなら私たちが開発に参加してよいものにするべき。
  * インストールできたらドキュメントに書いている通りに動作を確認する
  * グループの他の人がまだ動かせていなかったらフォローする。
  * 動いたら「開発用にインストール」する
    * ドキュメントに不備があったらメモしておくというやり方は「動かす」ときと同じ
  * 「開発用にインストール」できたら「テスト」を動かす
    * ドキュメントに不備があったらメモしておくというやり方は「動かす」ときと同じ
    * テストが動かなかったらメモしておく。やり方は「動かす」ときと同じ。

## 12:00 ミニふりかえり

目的：

  * ふりかえりのリハーサル
    * 作業ログが後で自分の役に立つことを実感してもらう
  * 今後進むべき方向を確認して、午後を有意義に過ごすため

目的のために達成したいこと：

  * 「まず動かす」のときに作業ログをとる

やること：

  * 進行役は参加者を1人選んでデモをする
  * デモの後は各メンターでやってもらう
  * 1メンターあたり2参加者をフォローする
  * 1人の参加者がふりかえりをしている間、もう1人は得られるものがないかという気持ちで見守る
  * 1人終わったら交代
  * ふりかえりの仕方はissueに書いてある

## 12:15 （昼食）

近所にランチを食べに行きましょう。

参加者は午前中に気になったことを進行役・メンターに聞いてみてください。

進行役・メンターは参加者に楽しんでいるか聞いてみてください。

## 13:15 対象OSSを動かす（続き）

## 14:20 休憩

10分休憩。

## 14:30 プロジェクトにフィードバックする

目的：

  * 動かす・開発用にインストール・テストを実際にやってみて気づいたことをOSSプロジェクトにフィードバックすることを「体験」する
    * issueでもpull requestでもよい

目的達成のために達成したいこと：

  * 進行役はスライドを使って↓に書いているやり方を説明する。（スライドはfeedback/または↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/oss-gate-workshop-tutorial-feedback/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/oss-gate-workshop-tutorial-feedback)

やること：

  * 動かす・開発用にインストール・テストのなかで見つけたドキュメントの不備がどんなものか他の人に伝わるようにまとめる
    * わかりにくかったところに対する改善案をまとめるのもよい。
  * まずは自分の考えを整理する
    * OSSの開発ではインターネット越しのやりとりが基本なので、文章で伝える必要がある。
    * 少なくとも自分が理解できるような文章にまとめること。
    * 自分の考えを文章にまとめるのは難しいと思うのでメンターには考えの整理を手伝ってあげて欲しい。
    * まとめたものは作業ログissueにコメント。
  * 自分の考えがまとまったら開発者に伝わるようにまとめ直す
    * 「読む人」が理解できることが大事
    * メンターは読む人視点を伝えてあげて欲しい。
    * これもまとめたものは作業ログissueにコメント。
  * 実際に報告する
    * これはupstream（開発元）のissueに報告。

## 16:20 休憩

10分休憩。

## 16:30 ふりかえり

目的：

  * 参加者のよい行動を伸ばすため
  * 参加者が困っていることを解決するため
  * 参加者が見過ごしている問題（= 解決するべき問題）を気づかせるため
  * 参加者が明日進むべき先を目指すため

目的達成のために達成したいこと：

  * 参加者の作業ログを元にメンターが参加者をサポートする。

やること：

  * 進行役は参加者を1人選んでデモをする
  * デモの後は各メンターでやってもらう
  * 1メンターあたり2参加者をフォローする
  * 1人の参加者がふりかえりをしている間、もう1人は得られるものがないかという気持ちで見守る
  * 1人終わったら交代
  * ふりかえりの仕方はissueに書いてある

## 17:00 まとめ

目的：

  * 今日やったことの意味を再確認する
  * 今日やったことを明日以降に活かす

目的達成のために達成したいこと：

  * 進行役はスライドを使って↓に書いているやり方を説明する。（スライドはconclusion/または↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/oss-gate-workshop-tutorial-conclusion/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/oss-gate-workshop-tutorial-conclusion)

やること：

  * 今日やったことを再確認
  * 今日やったやりかたの思惑を説明
  * 明日からのヒントを提示

## 17:10 質疑応答

  * 進行役が司会をする
  * 質疑応答をしながら、メンターに「ふりかえりをして印象に残ったこと（他の参加者に共有したいこと）」を話してもらう（話が1つ終わるごとに参加者に質問がないか聞く）
    * 紹介してくれるメンターは[oss-gate/workshop issue #5](https://github.com/oss-gate/workshop/issues/5)に書き込んで欲しい。

## 17:30 アンケート記入

  * [アンケート](TODO)を記入する
  * このアンケートはこのあとの「ワークショップのふりかえり」ですぐに使う

## 17:45 ワークショップのふりかえり

  * アンケート結果をみながら今後もっとうまくやるにはどうすればよいかを検討する
