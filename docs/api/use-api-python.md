# Pythonを使ったAPIの使い方

詳しいAPIドキュメントは公式インスタンスである [AkariNe](https://ne.akarinext.org/api-doc) や [OrangeKr](https://kr.akirin.xyz/api-doc)
をご参照ください。

## ノートの投稿

`requests` パッケージを使用してayuskeyに`Welcome to Ayuskey`とノートを投稿してみましょう。
`i`変数にはご自分のアクセストークンを入れてください。

```python
import requests
import json

i = 'my token'

data = json.dumps({'i': i, 'text': 'Welcome to Ayuskey'}, ensure_ascii=false)

res = requests.post('http://localhost:3300/api/notes/create', data=data)
print(res.json())

>>> response内容
```

## リプライ

`requests`パッケージを使用して、`note_id`変数にあるidを元にノートにリプライを送りましょう。

```python
import requests
import json

i = 'my token'
note_id = 'xxxxxxxx'

data = json.dumps({'i': i, 'text': 'Welcome to Ayuskey', 'replyId': note_id}, ensure_ascii=false)

res = requests.post('http://localhost:3300/api/notes/create')

print(res.json())
>>> response内容
```
