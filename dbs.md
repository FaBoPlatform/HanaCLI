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
$ neo.sh list-dbs --account ${ACCOUNT} --user ${USER} --host ${HOST} --password ${PASSOWRD} 
```

## 結果

```bash
SAP HANA Cloud Platform Console Client

Database ID
  test2
```

## Reference

* [Console Client Command(list-dbs)](https://help.hana.ondemand.com/help/frameset.htm?f94d5a21f99049f5985a9ecfd73e8f46.html)
* [Creating an SAP HANA Database Using Console Client](https://help.hana.ondemand.com/help/frameset.htm?ee6ae2938cf54c46bd8996745dbc033c.html)
