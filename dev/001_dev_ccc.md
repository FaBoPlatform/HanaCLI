# 001 開発環境(CCC)

## 必要なSDK

* [SAP HANA Cloud Platform SDK](https://tools.hana.ondemand.com/#cloud)

## インストール　

Java Webのneo-java-web-sdk-1.###.##.#.zip をダウンロードし、解凍し、

> /Application/Hana/HanaCloud/neo-java-web-sdk-1.111.13.1

に配置。

## 確認

toolsのフォルダにパスを通す

~/.bash_profile

```bash
export PATH=/Applications/HanaCloud/neo-java-web-sdk-1.111.13.1/tools:....
```

```bash
$ source ~/.bash_profile
```

```bash
$ neo version --commands
$ neo version --jars
$ neo version --updates
```
