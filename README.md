<p align="center">
  <a href="https://ayuskey-hub.readthedocs.io/"><img src="https://s3.akarinext.org/assets/*/ayuskey-desk-4.png" alt="Ayuskey"></a>
</p>

# Ayuskey Hub

[![][document-badge]][document-link]
[![][e2e-badge]][e2e-link]

[![][fork-of-badge]][fork-of-link]
[![][summaly-badge]][summaly-link]
[![][mfmjs-badge]][mfmjs-link]

## 概要

Ayuskey HubではAyuskeyの開発者2人が大事だと思うことや説明、お願い事などを書くサイトです。

## スクリーンショット

<p align="center">
  <a href="https://ayuskey-hub.readthedocs.io/"><img src="https://s3.akarinext.org/assets/*/ayuskey-desk-3.png" alt="Ayuskey"></a>
</p>

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

[document-badge]: https://readthedocs.org/projects/ayuskey-hub/badge/?version=latest

[document-link]: https://ayuskey-hub.readthedocs.io/ja/latest/?badge=latest


[e2e-link]:      https://github.com/TeamBlackCrystal/misskey/actions/workflows/e2e.yml

[e2e-badge]:     https://img.shields.io/github/workflow/status/TeamBlackCrystal/misskey/Ayuskey%20E2E%20Test?label=E2E%20Test&style=flat-square

[fork-of-link]:  https://github.com/syuilo/misskey/tree/v11

[fork-of-badge]: https://img.shields.io/badge/fork%20of-misskey--dev%2Fmisskey-important.svg?style=flat-square

[summaly-link]:  https://www.npmjs.com/package/@ayuskey/summaly

[summaly-badge]: https://img.shields.io/badge/summaly-%40ayuskey%2Fsummaly-blue.svg?style=flat-square

[mfmjs-link]:    https://github.com/TeamBlackCrystal/misskey/issues/222

[mfmjs-badge]:   https://img.shields.io/badge/mfm.js-none(%23222)-blue.svg?style=flat-square