# アップデートのお願い

以下のバージョンをご利用の方は早急にアップデートをお願いいたします。

|バージョン|脆弱性内容|アドバイザリー|
|---|---|---|
|<5.15.0|Webクライアントのdialogで悪意の文字列を表示させることでアクセストークンを奪取される恐れがある|[Advisories](https://github.com/TeamBlackCrystal/misskey/security/advisories/GHSA-669q-w6qc-75h3)|
|<5.15.1|URLからアップロード及びリモート添付ファイルの処理にServer-Side Request Forgeryの脆弱性が発生し、内部ネットワーク内の非公開情報が漏洩する可能性がある|[Advisories](https://github.com/TeamBlackCrystal/misskey/security/advisories/GHSA-x9q4-5jhg-9mpf)|

## アップデートの際の注意事項

脆弱性修正後にバージョンが更新されていない場合があります。そういった際に[Join Misskey](https://join.misskey.page/ja/)
等といったインスタンス一覧で脆弱性等を把握しているサイトの場合表示対象から外れる場合があります。そのため、不安な方は`tools/test-build.sh`を使用してビルドを行うようにしてください。

!!! warning
v11-lts以外の実験的な機能を使う場合は`package.json`の`version`項目を変更しないと、キャッシュが残り正常に動作しない場合があります。
!!!

!!! danger
git pull等を行わず、Join Misskey等での回避だけを行う行為は一種の迷惑行為なのでお控えください。あたなはインスタンスの管理者であり、使用しているユーザーを守る義務があります。インスタンスを公開する際はその点に注意して定期的な更新を行うようにしてください。
!!!
