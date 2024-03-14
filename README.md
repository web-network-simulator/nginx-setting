# nginx-setting
nginxの設定ファイル群

## nginxの設定ファイルの場所と役割
メイン設定ファイル
- /etc/nginx/nginx.conf
Nginxの通信設定や、以下設定ファイルの読み込みを行う

nw-sim.netの設定ファイル
- /etc/nginx/conf.d/http/nw-sim.net.conf
nw-sim.netからwww.nw-sim.netへのリダイレクト設定ファイル

www.nw-sim.netの設定ファイル
- /etc/nginx/conf.d/http/www.nw-sim.net.conf
www.nw-sim.net 内部port 3000へのリダイレクト設定ファイル
nw-sim.net とは違い内部的にポートを変更します