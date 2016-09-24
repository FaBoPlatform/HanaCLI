# Destinationを調べる

## 設定する環境変数

|変数名|値|
|:--|:--|
|ACCOUNT|アカウント名|
|USER|ユーザ名|
|HOST|hanatrial.ondemand.com|

## Destinationを調べる

```bash
$ export ACCOUNT="##################"
$ export USER="P################"
$ export HOST="hanatrial.ondemand.com"
$ neo.sh get-destination --account ${ACCOUNT} --user ${USER} --host ${HOST}
```

## 結果

```bash
SAP HANA Cloud Platform Console Client

Requesting get-destination for a specified account:
   account    : p################
   host       : https://configapi.hanatrial.ondemand.com/configuration/api/rest
   SDK version: 1.111.13.1
   user       : P###########

Password for your user: 


Operation get-destination finished successfully.
```

## Reference

* [Console Client Command(get-destination)](https://help.hana.ondemand.com/help/frameset.htm?bc623358916d47b48077b0e25b626a62.html)
