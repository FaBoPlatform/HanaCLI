# DBMSのリストを表示

## 設定する環境変数

|変数名|値|
|:--|:--|
|ACCOUNT|アカウント名|
|USER|ユーザ名|
|HOST|hanatrial.ondemand.com|
|PASSWORD|アカウントのパスワード|

## DBMSのリストを表示

```bash
$ neo.sh list-dbms --account ${ACCOUNT} --user ${USER} --host ${HOST} --password ${PASSOWRD} 
```

## 結果

```bash
SAP HANA Cloud Platform Console Client

Shared:
DB Type  DB Version             
  HANA     1.00.97.03.1443520413
  MaxDB    7.8.2.34             
Trial:
DB Type  
  HANAMDC
```

## Reference

* [Console Client Command(list-dbms)](https://help.hana.ondemand.com/help/frameset.htm?1ea177113f694bfab1529214d307edda.html)
* [Creating an SAP HANA Database Using Console Client](https://help.hana.ondemand.com/help/frameset.htm?ee6ae2938cf54c46bd8996745dbc033c.html)
