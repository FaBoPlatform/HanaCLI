# 004 Databaseの情報を表示

## 設定する環境変数

|変数名|値|
|:--|:--|
|ACCOUNT|アカウント名|
|USER|ユーザ名|
|HOST|hanatrial.ondemand.com|
|PASSWORD|アカウントのパスワード|
|DATABASE_ID|DatabaseのID|

## Databaseを作成

```bash
$ export DBSYSTEM="-trial-"
$ export DATABASE_ID="mydatabase"
$ neo.sh display-db-info --account ${ACCOUNT} --user ${USER} --host ${HOST} --password ${PASSWORD} --dbsystem ${DBSYSTEM} --id=${DATABASE_ID}
```

## 結果

```bash
SAP HANA Cloud Platform Console Client

Database '########' properties:
  DB State:       STARTED
  DB Type:        hanamdc
  DB System:      <trial>
  DB Version:     1.00.112.04.1467296086
  Parameters
    Web Access:     ENABLED
    XS Engine Mode: EMBEDDED
  Bindings
    Application  Data Source  DB User

```

## Reference

* [Console Client Command(create-db-hana)](https://help.hana.ondemand.com/help/frameset.htm?064d3013cf584a3b8be59d396e027929.html)
