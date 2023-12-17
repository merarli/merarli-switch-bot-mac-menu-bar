# Nature Remo Mac Menu Bar

## 概要
SwitchBot APIを使って温度、湿度、絶対湿度Macのメニューバーに表示します。

<img width="269" alt="スクリーンショット 2021-10-06 15 40 19" src="https://user-images.githubusercontent.com/32351460/136152826-8d7ca325-bc01-48cb-9f7a-591d8a9a83a3.png">

## TOKEN、DEVICE_IDの取得方法
https://massa4649.com/switchbot-api-v1p0/

## セットアップ
.envファイルを作成後
```
$ touch .env 
```

.envファイルにSwitch BotのTOKENとDEVICE_IDを入力してください。
```
TOKEN=hogehoge
DEVICE_ID=hugahuga
```

必要なライブラリをインストールします。
```
$ npm install
```

## 実行

```
$ npm run start
```

## ビルド
```
$ npm run build
```


## Links

- [参考にしたリポジトリ](https://github.com/Neos21/practice-electron-tray-app)
