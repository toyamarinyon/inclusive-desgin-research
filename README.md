# インクルーシブデザインについて調べたり考えたりしたメモ

## 当面の目標

- インクルーシブデザインについて考えていきたいが、まずはアクセシビリティを考慮したウェブサイトを実装することにどれくらいコストがかかるかを明らかにする
- ビックテック企業のインクルーシブデザインの取り組みや、インクルーシブデザインに力を入れている人について把握する

### 仮説

- 実装レベルではツールやベストプラクティスが揃っていて、そんなに大変ではないのではないか？
  - プログラマに親和性の高い方法で取り入れる（CIでチェック、VSCodeの拡張機能など）方法がありそう
    - どんなことは機械的にチェックできて、どんなことは人が考えないといけないか
  - もし大変なのであれば、どのあたりが大変か
    - コンテンツを作成するのが大変？（画像のalt, 動画の説明文など）

## このレポジトリを作ったときに考えていたこと

インクルーシブなプロダクトを作るのは、追加のコストがかかりそうな印象がある。僕はテスト駆動開発についても同じようなことを思っていた。だけど、テスト駆動開発は、今はプロダクトを作る上でなくてはならないものになっている。
もしかしたら、インクルーシブなプロダクトも同じかもしれない。

また、もしインクルーシブなプロダクトを作ることにものすごくコストがかかるのであれば、そこにはテクノロジーで解決できる課題がたくさんあるかもしれない。

僕は、テクノロジーが苦手な友人や家族に、テクノロジーを使うとこんなに楽しいことができるんだよ、人生豊かになるよって紹介して、実際に使って喜んでもらうのが好きだ。学生の頃、Windowsの画面が殺風景で楽しくないという友人に、壁紙とアイコンを変えて、可愛くしたら、すごく喜んでもらえて、「これなら使える！」と言われたことがすごく嬉しかった。

一方で、仕事では考慮すべきパターンが最低限になるように要件や仕様を調整することが多い。これは、まず動くものを作って、それを使ったフィードバックをもとに改善していくからなのだけど、まず動くものを作るときに、自分の文化や価値観、経験をもとにしていて、それ以外のものは無意識に排除しているのだと思う。

どうしても時間がかかることもあると思う。だけど、心掛け一つで変わったり、ツールを導入したり作ることで実現できることもあると思うので、今できることを考えて、行動していこう。

## なるほどねと思った言葉、数字

> Googleでは、ダイバーシティ、エクイティ、インクルージョンについて、ジムに通って筋トレをするようなものだとよく言われる。はじめは、課題や努力に嫌気がさすかもしれないけれど、「プロダクトインクルージョンの筋力」が鍛えられるにつれて楽になってくるし、楽になれば、楽しんでワクワクできるようになってくる。
アニー・ジャン＝バティスト. Google流 ダイバーシティ＆インクルージョン　インクルーシブな製品開発のための方法と実践 (Japanese Edition) (p. 23). Kindle Edition. 

> ダイバーシティ（多様性）とインクルージョンの急先鋒ジョー・ガースタント［1］は、「意図的に、じっくりと、積極的に包摂しなければ、無意識に排除してしまう」と人々の注意を喚起する。
アニー・ジャン＝バティスト. Google流 ダイバーシティ＆インクルージョン　インクルーシブな製品開発のための方法と実践 (Japanese Edition) (p. 19). Kindle Edition. 

![見過ごされてきた人々の持つ機会と購買力](assets/images/image001.png)

画像の引用元: アニー・ジャン＝バティスト. Google流 ダイバーシティ＆インクルージョン　インクルーシブな製品開発のための方法と実践 (Japanese Edition) 
