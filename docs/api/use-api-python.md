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

res = requests.post(data=data)
print(res.json())

>>> response内容
```