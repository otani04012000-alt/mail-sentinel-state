# mail-sentinel-state

メール監視通知（Mail Sentinel）の表示用状態ファイルだけを置く公開リポジトリです。

- `state.json` には、対象メールの件名・送信元・受信日時・最終確認時刻のみが入ります。
- メール本文、パスワード、OAuthのクライアントID/シークレット、アクセストークンは一切含まれません。
- 更新は、ユーザーのMac上で動く常駐監視プログラム（`mail-sentinel-agent`、非公開リポジトリ）からのみ行われます。
- 表示は https://mail-sentinel-weld.vercel.app/ で行われます。
