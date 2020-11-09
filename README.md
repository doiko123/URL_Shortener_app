# URL_Shortener_app

URL短縮サービスです。

【使用する技術スタック】
---
- Python
- Django
- PostgreSQL
- Heroku

【その他】
---
* 独自ドメインはfreenomで取得
* SSL化はCloudflareをプロキシとしてかませて行う
* Heroku無料枠のため、UptimeRobotでスリープ防止

【環境構築について】
---
- 当初WSL2-ubuntu20.04-virtualenv上で制作していたが<br>
エラーなど問題が頻発したため、WSL2-Docker for Windowsで作り直すことに（11/9）
