# アップデートのお願い

以下のバージョンをご利用の方は早急にアップデートをお願いいたします。

|バージョン|脆弱性内容|アドバイザリー|
|---|---|---|
|<5.15.0|Webクライアントのdialogで悪意の文字列を表示させることでアクセストークンを奪取される恐れがある|[Advisories](https://github.com/TeamBlackCrystal/misskey/security/advisories/GHSA-669q-w6qc-75h3)|
|<5.15.1|URLからアップロード及びリモート添付ファイルの処理にServer-Side Request Forgeryの脆弱性が発生し、内部ネットワーク内の非公開情報が漏洩する可能性がある|[Advisories](https://github.com/TeamBlackCrystal/misskey/security/advisories/GHSA-x9q4-5jhg-9mpf)|

## アップデートの際の注意事項

脆弱性修正後にバージョンが更新されていない場合があります。そういった際に[Join Misskey](https://join.misskey.page/ja/)
等といったインスタンス一覧で脆弱性等を把握しているサイトの場合表示対象から外れる場合があります。そのため、不安な方は`packages.json`のversionに`-p1`
等を付けてパッチが当たっている等といった表記をすることで回避することができます。
