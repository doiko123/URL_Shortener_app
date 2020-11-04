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

【参考サイト】
---
>・日経XTECH 短縮URLサービスの仕組み
>ユーザーが短縮URLサービスで短縮URLを作成すると、同サービスには元のURLと短縮URLをマッチングするデータベースができる。
>自分のTwitterに短縮URLを張り付け、それに誰かがアクセスしたとする。
>短縮URLのリンク先は短縮URLサービスのデータベースだ。
>データベースはその短縮URLアドレスに合致する元のURLを、アクセスしてきたWebブラウザーに返す。
>Webブラウザーは元のURLにリダイレクトされ、Webページが表示されるという仕組みだ。
>ただしセキュリティ上保護されているWebページにはリダイレクトできない。
https://xtech.nikkei.com/it/article/Keyword/20100309/345549/#:~:text=%E7%9F%AD%E7%B8%AEURL%E3%81%A8%E3%81%AF%E3%80%81Web,%E7%9F%AD%E3%81%8F%E5%A4%89%E6%8F%9B%E3%81%97%E3%81%9F%E3%82%82%E3%81%AE%E3%81%AE%E3%81%93%E3%81%A8%E3%80%82&text=%E7%9F%AD%E7%B8%AEURL%E3%81%AE%E3%83%AA%E3%83%B3%E3%82%AF%E5%85%88,%E3%81%95%E3%82%8C%E3%82%8B%E3%81%A8%E3%81%84%E3%81%86%E4%BB%95%E7%B5%84%E3%81%BF%E3%81%A0%E3%80%82
