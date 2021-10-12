アプリケーション名
海行こうぜ

アプリケーション概要　このアプリケーションでできること。
サーファー、海好きの人のためのSNS。
波情報などの情報交換のために使用。

URL	デプロイ済みのURLを記述。デプロイが済んでいない場合は、デプロイが完了次第記述すること。


テスト用アカウント　ログイン機能等を実装した場合は、ログインに必要な情報を記述。またBasic認証等を設けている場合は、その
ID/Passも記述すること。

利用方法　このアプリケーションの利用方法。
新規登録し、画像、動画を投稿。
投稿に対してリアクション、コメントできる。
天気予報、天気図、タイトグラフが閲覧できる。

目指した課題解決　このアプリケーションを通じて、どのような人の、どのような課題を解決しようとしているのか。
サーファー向けSNSが少なっかたため。
波情報とSNSを合わせることでよりタイムリーな情報を入手することができる。
ライディングの動画を投稿してもらうことで初心者が参考にできる。


洗い出した要件　スプレッドシートにまとめた要件定義を記述。

機能　　　　　　目的　　　　　　　　　　　　　　　　詳細　　　　　　　　　　　　　　　ストーリー（ユースケース）

ユーザー機能　　ユーザー管理機能　　　　　　　　　　ユーザー管理をする　　　　　　　　新規登録、ログイン、ログアウト
ツイート　　　　投稿するため　　　　　　　　　　　　投稿者が投稿をする　　　　　　　　内容を打ち込み投稿する
コメント　　　　投稿者へのリアクション機能のため　　投稿者へのリアクションをする　　　コメントを打ち込み投稿する
画像投稿　　　　波の状況の投稿のため　　　　　　　　波を可視化する　　　　　　　　　　画像を選択し投稿する
天気予報　　　　天気把握のため　　　　　　　　　　　天気、風向き、風の強さを確認する　閲覧
天気図　　　　　風、気圧の把握のため　　　　　　　　週間的に風や風向き等を確認する　　閲覧
タイトグラフ　　潮回りの把握のため　　　　　　　　　潮回りを確認する　　　　　　　　　閲覧
位置情報　　　　場所把握のため　　　　　　　　　　　どこの波情報かを確認する　　　　　投稿に紐付け場所を把握する。


実装した機能についての画像やGIFおよびその説明	実装した機能について、それぞれどのような特徴があるのかを列挙する形で記述。




画像はGyazoで、GIFはGyazoGIFで撮影すること。




実装予定の機能	洗い出した要件の中から、今後実装予定の機能がある場合は、その機能を記述。




データベース設計	ER図等を添付。





ローカルでの動作方法	git cloneしてから、ローカルで動作をさせるまでに必要なコマンドを記述。この時、アプリケーション開発
に使用した環境を併記することを忘れないこと（パッケージやRubyのバージョンなど）。