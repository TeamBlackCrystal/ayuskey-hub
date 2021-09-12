# Ayuskey Hub

[![Documentation Status](https://readthedocs.org/projects/ayuskey-hub/badge/?version=latest)](https://ayuskey-hub.readthedocs.io/ja/latest/?badge=latest)

## 概要

Ayuskey HubではAyuskeyの開発者2人が大事だと思うことや説明、お願い事などを書くサイトです。

## 動かし方

環境構築にはvenvを推奨します

### Windowsの場合

```bash

git clone https://github.com/TeamBlackCrystal/ayuskey-hub.git

python -m venv venv

# Windowsの場合のみ記載
.\venv\Scripts\Activate.ps1

pip install -r .\docs\requirements.txt

mkdocs serve
```