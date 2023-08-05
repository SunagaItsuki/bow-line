# BOW-LINE

## サービス概要
### 短い文章でサービスの概要（提供価値）を説明します。
BOW-LINEは選手・試合の運営者・応援したい人みんなが使える、弓道専用のオンライン試合サポートツールです。

## 想定されるユーザー層
- 普段は一緒に弓を弾けないような相手(遠隔地同士、学生と社会人など)と試合をしたい弓道家
- 現地にはいけないけれど、大会に出場しているお子さんをオンラインで応援したい方
- オンラインでの試合や大会を開催したい団体の方

## サービスコンセプト
私は学生時代、弓道の学生大会の役員を務めていました。
コロナによる行動制限中、オフラインでの大会が実施できなくなったため、Zoomを利用したオンライン全国大会を企画・開催しました。
物理的な距離があり普段一緒に試合できないような人とも、いつもの道場で試合ができることは画期的でした。

<details><summary>弓道におけるオンライン試合とは</summary><div>

弓道で行うオンライン試合は以下のようなものです。
- [こちらの動画](https://www.youtube.com/live/WNSySqMP6iE?feature=share&t=24334)ではオンライン大会の配信の様子が公開されています。
- 上記の動画の様に、対戦会場間でZoomを接続し、互いの競技中の姿を撮影します。
- 競技の進行はZoomによる音声を通して実施します。
- 両者の的中記録はスプレッドシートを用いて記録し、リアルタイムに共有されています。
- 選手交代などの届け出や競技中の連絡はチャットを利用して実施します。(競技中の選手の妨げとならないようにするためです。)
- [こちらの動画](https://youtu.be/C39Q6PR-Zbo)は東京都学生弓道連盟が公開しているオンライン試合のマニュアル動画です。
	- 公式戦用のマニュアルのため、行射前後の的の確認を実施し常に的を撮影し続ける手順とされていますが、練習試合などであれば両者の取り決めによって
- 上記は一般的な方式ですが、試合参加者同士の取り決めにより柔軟な方式変更が可能です。

</div></details>

しかし、オンライン試合を実施するにはZoomやスプレッドシートによる試合環境の整備が必要となり、気軽にオンライン試合を実施するための環境が整っていないという課題があります。

そこで、弓道のオンライン試合を簡単に実施できるサービスを考えました。
ブラウザの1画面で試合に必要な情報を表示し、リアルタイムにやり取りできる機能を実装することでスムーズな試合進行が可能な環境を提供します。

現在は行動制限も解除されオフラインの試合が開催される機会も増えましたが、遠隔地の人同士で気軽に試合ができるなど、今後もオンラインでの試合は有効な場面があると考えられます。
BOW-LINEは日本全国、更には海外の弓道家を繋ぎ、弓道家同士の輪が広がるようなプラットフォームを目指しています。

## 実装を予定している機能
### MVP
* 会員登録
* ログイン
* 試合一覧
* 試合作成
* 試合詳細
* 試合参加申し込み
* 試合実施
	* 的中記録の共有(リアルタイム更新)
	* 的中記録の集計
	* 選手情報登録

### その後の機能
* 試合実施
	* 互いの動画表示
	* チャット機能
	* 選手交代機能
* 試合の公開範囲設定
* 試合相手募集
* 試合検索
* 試合結果エクスポート
* 試合観覧モード
	* ログイン不要
* トーナメント機能

