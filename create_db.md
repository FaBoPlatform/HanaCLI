# Databaseを削除

## 設定する環境変数

|変数名|値|
|:--|:--|
|ACCOUNT|アカウント名|
|USER|ユーザ名|
|HOST|hanatrial.ondemand.com|
|PASSWORD|アカウントのパスワード|
|DATABASE_ID|DatabaseのID|
|DBSYSTEM|-trial|

## Databaseを作成

```bash
$ export DBSYSTEM="-trial-"
$ export DATABASE_ID="mydatabase"
$ neo.sh create-db-hana --account ${ACCOUNT} --user ${USER} --host ${HOST} --password ${PASSWORD} --dbsystem ${DBSYSTEM} --id=${DATABASE_ID}
```

## 結果

```bash
SAP HANA Cloud Platform Console Client


Password for HANA database SYSTEM user: 
Repeat password for HANA database SYSTEM user: 

Request to create HANA tenant database '#######' as part of a HANA trial system is accepted. The request should be processed within next 10-20 minutes. To check the status of this request you may use display-db-info command.
```

## Reference

* [Console Client Command(create-db-hana)](https://help.hana.ondemand.com/help/frameset.htm?f64390e250cc4dcf8d9046192957d26a.html)
