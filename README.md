## Directory listing for httpd
Apache HTTP Serverのディレクトリ一覧表示を改善するためのhtmlとcssとhtaccessファイルです。  
MUIを使用しています。(参考: https://www.muicss.com/ )  

### Usage
リポジトリをクローンしてApacheのパブリックアクセスが可能なディレクトリに設置してください。  
htaccess.txtをコピーしてルートディレクトリに.htaccessを設置します。  
pathtolistを設置したパスに適宜書き換えてください。  

Ubuntu22.04とCentOS7で動作確認済み
```
Ubuntu 22.04
$ apache2 -v
Server version: Apache/2.4.52 (Ubuntu)
Server built:   2023-01-23T18:34:42

CentOS7
$ httpd -v
Server version: Apache/2.4.6 (CentOS)
Server built:   May 30 2023 14:01:11
```
