zabbix 用 SSL 有効期限 確認スクリプト
======================================

* コレは何？

  * ZABBIX で SSL の有効期限の日数を確かめるためのスクリプトです。
  * 残日数を表示します。
  * ZABBIX の動作確認バージョンは 2.0 です。1.8 とかでも動くとは思いますが保証はしません。


* 使い方


```
  cd  /path/to/zabbix/alertscripts  
  git clone https://github.com/moobay9/zabbix-ssl-certificate-expire-check.git
  chmod +x zabbix-ssl-certificate-expire-check/checker
```
  1. git からクローンする  
    * 上記コマンドを参照




