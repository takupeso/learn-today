「クックパッドが目指す、これからのデザインとプロダクトのあり方」
宇野　雄さん

クックパッド
毎日の料理を楽しみにする会社

料理のユーザー体験
一日の時系列　朝食、レシピ考える、洗い物、昼食、かたずけ、夕食
一生の時系列　離乳食、こだわりの食材、健康、食育、環境

クックパッドのできていないこと
横断的体験が設計されていない
一目でこれをしてほしいっている意思が足りない
アプリがweb的
クックパッド株式会社が提供したいことと、サービスが提供していることが一緒になってしまっている

期待値に対する振る舞いを共有する
	ちょっとした説明
	メンテナンスの対応
	ローディングじの表示
	ユーザビリティ
	アクセシビリティ
	アイコンのモチーフ
	マイコンインタラクション

デザインはデザイナーだけがやるわけじゃない
デザインは、目的を達成するための手段

会社にとってのデザインは出口だが、
ユーザーにとっては入り口

「生鮮ECクックパッドマート - サービスの立ち上げから拡大に向けて」
長野佳子

アジェンダ
サービスモデル
仮説検証のプロセス
スケールに向けた取り組み
開発チームの体制

クックパッドマート
近所で受けとるピックアップ型のEC
送料無料

解決したい課題
平日に買い物する時間がない、お店がしまっている
他ネットスーパーでは、最低注文金額がある
生鮮食品は難しい

買い物難民の救済

最小のプロトタイピングで十分な学びを得る

買い物上手な主婦による、買い物代行サービスが最初の仮説
	クックパッド社員を対象にやった
		スプレットシートを使った
	チームメンバーがレンタカーで買い出しを行なった
	ちゃんとお金をもらった　クレカ決済
コード０行のプロトモデル

検証
	１対１の大工モデルはスケールの課題が大きそう
		梱包スキルにばらつき、分別むずい
	自分で買えないものに価値がある　お肉や野菜
	いつでも買えるものは価値なし

	DesignSpring Googleベンチャーズ
	短期間で集中してプロトタイプ作る　検証したいことを検証するために作成する
体験全体をプロトタイピングする
	インタビュー中、メンバーは別室でみる
		ポストイットにインタビュー対象者の動きをメモる　ピンクがポジティブ、グリーンがネガティブ

最初は人の手で、それをシステム化する

「料理の学習体験をデザインする」
須藤耕平


どのような思考で開発を進めていたか
目的：ユーザーの料理の腕を上達させる

難しい
上達の定義ができない
定義できないので、何を学ぶべきかがわからない

ユーザーの要望
レシピを見ずに、手持ちの食材で料理ができるようになりたい

まとめ
いろんな見方で分割して考えようぜ


###「新規サービス開発を加速させる技術とデザイン」###
#藤井けんじろう#
#Komerco#
#料理関連の商品が買えるサービス(iOSのみ)#

当時の体制
エンジニア４
デザインー１
ディレクター１

メモ
最初はミニマムで作る
	- 正常系のみ(エラー処理は後ほど)
デザイン速度あげる
	- デザインツールを変えた sleche→figmaに　オンライン上で同時編集　デザイン変更の履歴も見れる　プロトタイプも作れる
	- コンポーネントデザインを導入
開発スピードあげる
	- UIガイドラインを作る カラーコード、マージンとかをまとめる
	-
	-

iOSはバージョンごとに画像が複数必要
	アイコンファイルを作成する
		メリット
			WebとiOS共有で使える
			GitPageで実際に見れる
アニメーション導入
	- アニメーションの導入コスト
	- 簡単に導入？
	- webとiOSどっちも入れる？？

Lottie導入
	AfterEddectsから作成

ライブラリを導入するときには、ミニマムで導入し、確認する

コミュニケーションコストを極限に減らす仕組みを作る

デザインコンポーネントをコードに変える
	ReactComponent化
		細かい仕様をコードでも、デザイン上でも確認できる

コンポーネントを繋ぐだけでいい感じにデザインされる幸せな世界

### Challenges for Global Service from a Perspective of SRE 2nd season ###
世界71ヶ国26言語

イギリス ブリストル
SRE

一行のログの先には、一人のユーザーがいる

自律的なチームを目指す

## メモ ##
グローバルチームの繊維

チャプター 業種ごと
すクアッド 業務ごと

自利的な
規律　ルール
自由　オーナーシップを持てるか
責任　全体の工程で責任感をモテるか
最適化　ベストプラクティスを採用できるか

ラーニングコストが低いこと

去年力を入れたこと
	- コンテナへの移行
	- SSH不要なデバック

###レシピを解析する！Machine Readable Recipe（MRR: 機械可読なレシピ）の開発###
## 伊尾木 将之##

MRR
人間がフォーマットに従っていない人間が作成した文章から、
機械がわかるレシピに変換してあげる

###クックパッド動画事業開発のチャレンジ###
cookpadTV株式会社


## メモ ##
料理動画事業部を子会社に
意思決定の速度を向上させるため

2018年 拡大
2019年 収益化

新規事業を大量に開発

開発基盤を整える

2018年の開発事例
cookpadstoreTV
スーパーで料理動画を流す

メッセージをバッファリング
バッファリング方針を決める
	- コメント繁栄を遅らせない
	- コメントの順序保証は行わない


###〜霞が関〜　クックパッドiOSアプリの破壊と創造、そして未来###
Object-v と Swiftがごっちゃになっている

アプリのマルチモジュール化

DyanamicFramework
画面感を疎結合にできる

開発者の生産性を高めるのが霞ヶ関

既存のアーキテクチャを生かしたマルチモジュール化

Xcodeプロジェクトの破壊

###スケーラブルなセキュリティ監視基盤の作り方###
セキュリティ監視とは
防御　脆弱性なくす、権限
検出　攻撃を発見する
対応　攻撃に対する回復を行う

監視　検出＋一部対応

監視があるのは？
	防御だけでは対応できない
	検出の方が、利用者に負担が少ない

本日のトピック：スケーラブルな監視

セキュリティ監視における消耗
	- 誤検知 謝って検知
	- 過剰検知 防御できていたものを検知

消耗をなくには
	- 検知のルールで不要なアラートを除外

Security as code
検知に関わる処理をコードに


######

Organized Around Business Capabilities

カオスエンジニアリング
システムが不安定な状態に耐えることができるかん子湯を構築する

アジェンダ
	- クックパッドがカオスえんジアリングを導入したか
	- マイクロアーキテクチャにおける障害の問題

	大モノリス時代
		サービス開発速度の低下
		リリース速度の低下

	大マイクロサービス時代
		サービス間通信の状況がすぐにわからない

	対策
		service mesh
			サービス間通信の状況把握ができる
			適切なリトライ設定などにより一時的な障害に耐えられる

マイクロサービス化
	メリット
		サービス開発速度向上
		リリース速度の向上
	デメリット
		複雑化
		一部サービスで障害が起きると、複数のサービスに影響が出る
		ストレージが死ぬ、ネットワークが死んだらサービスが全部死ぬ

マイクロサービス障害における問題
	サービスは正しく壊れるか
	障害時にどのように挙動するのか

TODO 意図的に障害を起こしてみる

カオスエンジニアリング ＝ マイクロサービス上の障害における解決策

カオスエンジニアリングをどのようにやっていくのか

カオスエンジニアリングは、わからないことをわかるようになるために手段
	- Fault Injection Testing
	- 本番環境での断続的なカオス実験

###なぜ毎日の料理を楽しみにするのか###
##成田一生##

リリース
2018年
cookpadTV Live
Komerco

ミッション
毎日の料理を楽しみにする

料理って必要ですか??
根本的な質問を忘れない
	美味しいものは外で食べれる
	体は食べたものでできている
	健康な内は、栄養の大切さを実感できない マイナスなことは、実感するまでわからない
	

Dockerimageをpullする等の作業はおやめください。
OSのアップデートはおやめください
#CookpadTechConf
