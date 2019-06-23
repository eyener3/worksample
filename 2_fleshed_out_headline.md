# Ruby on Railsの基礎

## このテキストのゴール

Ruby on Railsとは何か、またRuby on Railsの基礎知識と基礎概念を把握・理解する

---

### Ruby on Rails とは

RubyでのWebアプリケーション開発の助けとなるフレームワークである

「プログラマの幸福度を最適化する」というのを目標に形作られている

コーディングの効率化・多機能の実現化を目指している

---

### なぜRails on Railsを使用するのか

必要となる作業やリソースを事前に準備してくれるフルスタックなフレームワーク

コマンド一つで必要なファイルを一斉に作成してくれる等

短いコーディングでの実装が可能でありながら多くの機能を実現できる

機能追加、削除にかかる時間やコストが少ないため仕様変更に対応しやすい

---

### フレームワークとは

開発に必要なプログラムのひな形である

さまざまなシステム開発を効率化してくれる機能群

ソフトウェアの骨組みまでを用意してくれているため少ないコードで意図する機能やデザインが実現できる


フレームワークにはルールが定められているため、そのルールに沿って実装を進めていくことが求められる

---

### フレームワークの利点

汎用的な機能があらかじめ用意されている

書き方にルールが用意されているため、開発において統一化しやすい

コーディングの効率化がしやすい

---

### Ruby on Railsの基本理念

#### MVCアーキテクチャ（Model・View・Controller）

- Model：データを扱う箇所
    - ①Controllerから「データを取り出して」という命令を受け取る

    - ②データベースへ、あるデータを取り出す指示を出す

    - ③データベースから受け取ったデータをControllerへ返す

- View：ユーザーが直接目にする箇所

    - ①Controllerから値を渡される

    - ②それを受け取り見た目（HTML）を生成しControllerへ返す

- Controller：ModelとViewの連携を行う箇所

    - ①ブラウザから「このページをください」とリクエストをもらう

    - ②ModelやViewとやり取りを行う

    - ③やり取りを行なって受け取った情報をブラウザへ返す

#### DRY（Don’t Repeat Yourself）

一度自分でやった作業を繰り返さない

同じようなソースコードを繰り返し書かなくてはいけないような開発は非効率であるため大事な概念となる

#### COC（Convention over Configuration）

設定よりも規約を重視

ここでいう規約とは初期状態、設定とは初期状態を変更することである

規則を重視することで、開発者が自ら設定しなくてはいけない事項を最低限にできる

---

### Railsを活用したサービス事例

- [Hulu](https://www.happyon.jp/?cmp=10011&utm_media=cpc&utm_source=google&utm_content=brand&utm_term=search&utm_campaign=JP_DM&waad=P0Juqdc0&gclid=CjwKCAjw3azoBRAXEiwA-_64Og5cpjIM-V0gDI0UWEWlKV3_n3v5pSuPiNJfSyGqXXCMeg_-Sm1KMRoC3oMQAvD_BwE
) - 動画視聴サイト

- [食べログ](https://tabelog.com/) - お店やレストランを探せる口コミサイト

- [CrowdWorks](https://crowdworks.jp/) - お仕事マッチングサイト

- [freee](https://www.freee.co.jp/?referral=aw_freee&gclid=CjwKCAjw3azoBRAXEiwA-_64OhkaKaK54Fc9rXnl7AZDBXOLZSI2jX7pRLfnxOMjfYL5qlLnPPCBDxoC8lIQAvD_BwE
) - クラウド会計ソフト

- [Wantedly](https://www.wantedly.com/) - 求人マッチングサイト
