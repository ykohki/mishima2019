# mishima2019


## mishima.syk#14のスライドは[こちら](https://drive.google.com/open?id=1ytNCDf2zXPHaDovfGSJ8fPklwZiga3kx)


## GithubPagesで今回のまとめを作ってみました。→[こちら](https://ykohki.github.io/mishima2019/)


## 進んだこと

### 0日目
 * 三島に到着
 * AWSに初めて触れる
 * atomでREADMEを書き始める（プレビュー機能）

### 1日目
 * metagenome解析（実行）
 * Nimに触れる、atomで動かす

### 2日目
 * BS-seq解析（実行、解読）終了！
 * 発現類似度の計算スクリプト、Pythonverを理解、Pandasで。
 * ikraで40サンプルほどをまわした。iDEPに入れることはできた。
 * IsoformSwitchAnalyzeRのダイジェスト版を実行する
 * metagenome、他のサンプルでもQIIME2で解析できないか試してみる（途中）


### 3日目
 * metagenome解析（解読）
 * ikraをtravis ciに対応させる。
 * IsoformSwitchAnalyzeRを自前のデータでやってみる


### 4日目
 * leafcutterの実行
 * travis ciの並列化
 * coverallsをつける
 * プレゼン作成

### 5日目
 * mishima.syk#14の参加、発表


## 学んだことのまとめ
記録は全て、ScrapBoxに保存しています。ScrapBoxは無料でUPの制限もなく、コードがきれいに表示できる、ページとページを簡単に使えるので今イチオシでハマっています。



## 日々の感想
三島に来たからこそ、オフラインで学べたことを簡単に箇条書きで書いていきます。

### 19/09/16 0日目
到着。  
ホテルのWiFiはルーターを使えば、わりと快適。  

富士山きれい！
![huzi](photo/DSC_3685.JPG)

* 三島駅の南北連絡通路がない。。。  
[三島駅の南北通り抜け](http://www.zkaiblog.com/httk/27937)

* Markdownの記法を学ぶ  
参考：[Git Hubにて使用する簡単なMarkdown記法まとめ](https://qiita.com/do7be/items/d21405a3d243dde37f92)  
[markdown-cheatsheet.md](https://gist.github.com/mignonstyle/083c9e1651d7734f84c99b8cf49d57fa)

  * atomでプレビューができる。  
  →[AtomのMarkdownプレビュー機能を使ってみた](https://qiita.com/vonderinsel/items/1cc44618c43e42492c10)  
  ![atom_preview](photo/atom_preview.png)


* AWSの入門


## 19/09/17 1日目

* 8:40発のバスで到着。

* 坊農さんより、いろんな話をお聞きする。  
 * 本の部数について初めて聞いたので驚いた


* githubの勉強
 * copyleft･･･公開されたソフトウェアなどについて、利用・再配布・改変の自由を認める思想。
 * キャラの商品がある  
 ![github](photo/github_chara.webp)

 * topでhello worldと検索すると、全世界でのたくさんのタイプミスが見つかる。  
 https://github.com/search?q=hello+world  
 気にせず未熟なコードを書き込め！という意味だそう。

## 19/09/18 2日目

* [Human Re-sequencing](https://github.com/ddbj/human-reseq)
 * ヒトのデータはそのデータベースから持ち出せない→cwlを渡して、そのパイプラインで解析してもらって、結果だけもらう。統一させる。


* BS-seqも大きく変わる？
 * 今の技術は周りくどい。直接メチル化シトシンが読めればいい！  
 nanoporeの仕組み（電位差を読む）で、「メチル化シトシン」が読み取れればいけるのでは？あとは精度の問題か。

* RNA-seqも進歩の余地あり。
 * 今はcDNAに逆転写してるが、RNAの中にcDNAになりにくいものも。RNAを直接読みたい。nanopore？

* Python2のmac2はどうなる。。。

* ツールの開発は資金面が難しい。。。
  * イギリスのwellcome trust


* ほおずきおいしい。


* どこまでやりたいか。


* 2日目にして、ホテルのTVをモニタ化できることに成功！笑  
フロントにダメ元で聞いてみたところ、入力切り替えできるリモコンを貸してもらえました。  
ただHDMIケーブルは持参必須ですね。
![TV](photo/DSC_3706.JPG)


## 19/09/19 3日目

* 今日は初富士山！

* メタゲノムも結局メタデータが一番大事。どんな条件でサンプルとったのか。突き詰めたら、その日の気温は、湿度は、等々。細胞の良さ具合とか。

* 寄生蜂。1個の卵が数個～数千個の胚を生じる。ゲノムはn半数体。
 * ソルジャー
 * 論文⇒[Apoptosis-mediated vasa down-regulation controls developmental transformation in Japanese Copidosoma floridanum female soldiers](https://www.sciencedirect.com/science/article/pii/S0012160619302556?via%3Dihub)
* 真社会性→[真社会性・・・ハチやアリの社会はすごい](http://www.eonet.ne.jp/~kotetu/Eusociality.htm)

* シルク×パーキンソン病の論文→[Identification of key uric acid synthesis pathway in a unique mutant silkworm Bombyx mori model of Parkinson's disease.](https://www.ncbi.nlm.nih.gov/pubmed/23894418)

* micropython→[MicroPython ガイド](https://microbit.org/ja/guide/python/)



## 19/09/20 4日目

* PubMedにのるのは、出版されてから3〜4日程度かかる！誰かがやってくれているから。世の中そんなに便利じゃない。

* 田舎はお店が厳しく自然淘汰される。おいしいお店しか残らない。中立説はない。田舎はその点がよいか。
* しいたけキャッチャー
* [ベアードビール](https://bairdbeer.com/ja/)

* 坊農さんより、明日のsykの発表のダイジェストを一足先に聞かせて頂く。
 * 坊農さんのスライド→https://github.com/bonohu/slides
 * git pitch、おもしろい！  
 だが、もうすぐ有償化するらしい。。。  
 https://gitpitch.com/bonohu/slides?p=190921mishimasyk14#/

 メモ
 * a.k.a･･･also known as、またの名を。
 * Allie･･･[CWL](http://allie.dbcls.jp/short/exact/Any/CWL.html)
 * CWLの使われている例→https://gitpitch.com/bonohu/slides?p=190921mishimasyk14#/3/3  
 NCBIの例→PGAP[NCBI Prokaryotic Genome Annotation Pipeline](https://github.com/ncbi/pgap)
 * Common Workflow Language Viewer→例）https://github.com/dbcls/AOE/blob/master/gethoge-and-pigz.cwl
 * kallisto bustools→https://www.kallistobus.tools/about
 * ええとこ
  * 個別のプログラムインストール不要。Dockerとcwltoolが入っていればいい
  * いろんなサーバーでメタ解析とかできる。
 * あかんとこ
  * コンテナサイズが巨大。
  * メモリが多く必要。プロセスのメモリ＋Dockerのメモリが必要。
 * ハッシュタグ #CommonWL
 * 本→生命科学者のためのDr.Bonoデータ解析実践道場

* 癌学会も。  
 メモ
 * SNP chip
 * gnomAD browser  
 ![genomAD browser](photo/genomADbrowser_foxp3.png)   

## 19/09/21 5日目

* 沼津港を訪れる。

* Mishima.syk#14に参加する。[conpass](https://connpass.com/event/137642/)

* ①KNIME @PK（[@t_kahi](https://twitter.com/t_kahi?lang=ja)）
 * in vitroの創薬
  * KNIME analytics platform ⇒GUI [KNIME Analytics Platform とは？](https://service.infocom.co.jp/knime/)
  * ケモインフォでよく使われる。
  * 中でRが使える。
  * random forestとか機械学習も。
  * cellProfiler(HCSのスタンダート、フリーソフト)を使った、high content analysis(high content screening)
  * High Content Screening(HCS)とは，何千もの化合物やsiRNAライブラリーを処理した細胞内の生理活性を測定することができる自動顕微鏡スクリーニング技術のこと。  
  細胞や細胞内のオルガネラ，タンパク質などを複数の蛍光物質で染色をし測定することからhigh contentと呼ばれています．  
  [【HCS】High Content ScreeningとCellProfilerについて](https://www.t-kahi.com/entry/2018/12/25/222120)より。

  * ソフトは、condaとかでインストールできても、ライセンスがfreeじゃないときもある。
  * バイオインフォ系、統合TVもサポートしてた。→Galaxyだけが残った→その後、今はCWL。

* ② 大川さん([@fmkz___](https://twitter.com/fmkz___))
 * ケモ、バイオインフォ。
 * データサイエンティスト→ドメイン、ITスキル、統計処理能力が必要。  
 2種類存在、①まずドメインがある→プログラミング（創薬ではこっちが重視）、②IT→ドメインか。
 * udemyではデータサイエンティストにはなれない。汚いデータを前処理して、統計処理にもっていけることが必要。
 * KNWF･･･拡張子。
* ③ ([@iwatobipen](https://twitter.com/iwatobipen?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor))
 * Airflow
 * Luigiではない。
 * Jupyterでプレゼンができるっぽい→（参考：[【Day-5】Jupyterでできる！イケてるプレゼンスライドの作り方](https://www.procrasist.com/entry/5-jupyter-slide)  
 [Jupyter Notebookでプレゼンをするとっても便利な方法](https://qiita.com/cvusk/items/d425751ba663dc8c6517)）


## 19/09/22 6日目


## お食事日記

### 0日目
* 夜  
 近くのラーメン屋にて。

### 1日目
* 昼

![1_lunch](photo/1_lunch.JPG)

* 夜
ホテルの夜鳴きそば。
![1_dinner](photo/1_dinner.JPG)

### 2日目


### 3日目


### 4日目


### 5日目

### 6日目
