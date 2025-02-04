# コンセプト

運営会社である株式会社ミクシィ社内には、すでにSlack運用ガイドラインが存在していますが、この社内ガイドラインを前提としつつ、より簡潔で把握しやすい記載であることを心がけています。

# ガイドライン

## 1. オープンなコミュニケーション

* 業務に関わるコミュニケーションは、基本的にPublicチャンネルを利用してオープンに情報を共有しましょう。
* PrivateチャンネルやDirect Messageは、必要であると判断された場合のみ利用するようにしましょう。例えば以下のような場合です。
  * 人事・労務情報や社員の個人情報などのPrivateに共有することが必要な情報を取り扱う場合
* **認証情報などを伝達したい場合は、Direct Messageを利用せず、Password管理ツールを利用しましょう**
* サプライズパーティの準備を行いたい場合は:ok: 盛大にやりましょう:tada: 

### 2. チャンネル運用

* チャンネルの新規作成は誰でも、いつでも可能です。
* チャンネルを作成するときはInviteされる人や入りたい人が把握できるように「説明」にかならずチャンネルの利用目的などを記載しましょう。
* チャンネルへのInvite/Leaveも誰でも、いつでも、何度でも可能です。
  * 長期間発言・コミュニケーションのないチャンネルは積極的にLeave/Archiveしましょう。
  * 今、集中すべき話題に集中しましょう。必要であればまた作成し、Inviteすれば良いのです。
* <span style="color: #d61b09">チャンネルの命名規則は今のところありません。どなたでもご提案ください！ </span>

### 3. メンション

* 個人へのメンションは24時間いつでも行って構いません。
  * その通知を受けるかどうかは、ミュートやおやすみモードを利用し、受け手が調整しましょう。
  * 当然のことですが、受け手はすぐに返答しなければいけないわけではありませんし、発信側は相手からすぐに返答がくることも期待してはいけません。
* 大人数が参加するチャンネルで、  @here/@channel などを利用する場合は、それが本当に必要かをポストする前に熟慮しましょう。
  * 特に営業時間である場合、受け手側の手元の作業が止まる可能性があることを考慮してください！
  * 禁止ではないので、熟慮の結果、必要であれば利用してください。

### 4. その他、注意事項

* Slackのテキストコミュニケーションのみだと、ニュアンスや文脈が欠落することにより、誤った伝わり方をし、感情的になってしまうこともあります。オンラインであっても対面で話ができるビデオ会議ツールも積極的に活用しましょう。
* 対話している相手や、チャンネルに参加しているメンバーの心理状態には十分に配慮し、愛情・リスペクトを持ってコミュニケーションするように常に心がけましょう。

# こんなときはどうするの？

## Slackが障害で停止した場合は？

* 残念ながら、Slackもシステム障害が発生することにより、長時間利用が不可能となる場合があります（これまでに数回経験しています）。
* Slackに繋がりにくい、発言がなかなか行えない、などの不具合を感じたら一度以下のサイトを確認し障害が発生していないか確認してみましょう。

https://status.slack.com/

### 避難場所

障害が発生していると判断された場合には、長時間メンバー同士が連絡できない状態に陥り、業務上の問題となりますので、事前に避難先を決めておきます。

**Google Chat**を使いましょう。

https://chat.google.com/

Slackが障害かもしれないと思ったら、困ったらまずはこちらに避難してきてください。
必要であれば、業務に関連するメンバーのみを誘ってさらに個別にチャンネルを自由に作成してください。

### bot/webhook系の仕組みについて

Slack botやwebhookの通知をに依存している業務は改善するべきです。

* Webhookが失敗しただけで本来期待している処理が続行できない
* botが使えない時に代替手段が存在しない

このような状況が発生ないように注意して、業務設計を行いプログラム実装を行ってください。
