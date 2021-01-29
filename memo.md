# slackBotをちょっと遊んだ件
## links
- https://qiita.com/Kontam/items/2de3bf30f8a22af5269c
- [事例集](https://eh-career.com/engineerhub/entry/2017/06/30/110000)
- [DMについて](https://moripro.net/gas-slackapi-bot-send-dm/)
## API
1. Incoming Webhook
2. Outgoing Webhook
3. Events API + Web APIの組み合わせ
4. Real Time Message API
5. [ソケットモード?](https://qiita.com/seratch/items/1a460c08c3e245b56441)
## Incoming Webhook
1. Slackから指定されるエンドポイントに対するHTTPリクエストを送信することでBotユーザーに発言させることができる
2. [メンション飛ばす](https://qiita.com/ryo-yamaoka/items/7677ee4486cf395ce9bc)
3. https://kagaikatsudou.slack.com/services/B01LBEKMPA8?added=1#message_attachments
4. 便利ですね
### 試し
1. button click > slack投稿 => done //incomingWebhook.html
## Outgoing Webhook
## Events API + Web APIの組み合わせ
## Real Time Message API
## ソケットモード
1. slack投稿 > 反応 > bot発言 => done //socketMode.js
