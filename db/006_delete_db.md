# 006 Databaseを削除

## 設定する環境変数

|変数名|値|
|:--|:--|
|ACCOUNT|アカウント名|
|USER|ユーザ名|
|HOST|hanatrial.ondemand.com|
|PASSWORD|アカウントのパスワード|
|DATABASE_ID|DatabaseのID|

## DBMSのリストを表示

```bash
$ neo.sh delete-db-hana --account ${ACCOUNT} --user ${USER} --id ${DATABASE_ID} --host ${HOST} --password ${PASSWORD} 
```

## 結果

```bash
SAP HANA Cloud Platform Console Client


Are you sure you want to permanently delete the HANA database '#####'? This operation cannot be reverted. (yes/no) 
yes
```

## Reference

* [Console Client Command(delete-db-hana)](https://help.hana.ondemand.com/help/frameset.htm?628ae80589f247f59b227e63f9b0d02e.html)
