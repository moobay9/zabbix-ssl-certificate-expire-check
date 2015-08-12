zabbix 用 SSL 有効期限 確認スクリプト
======================================

* コレは何？

  * ZABBIX で SSL の有効期限の日数を確かめるためのスクリプトです。
  * 残日数を表示します。
  * ZABBIX の動作確認バージョンは 2.0 です。1.8 とかでも動くとは思いますが保証はしません。


* 使い方


```
  cd  /path/to/zabbix/externalscripts/  
  git clone https://github.com/moobay9/zabbix-ssl-certificate-expire-check.git
  chmod +x zabbix-ssl-certificate-expire-check/ssl_checker
  mv ssl_checker ssl_checker
```
  1. git からクローンする  
    * 上記コマンドを参照


  2. アイテムへの追加

  - 外部チェック
  - ssl_checker["{$URL}"] のような形で設定する

