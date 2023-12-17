# Switch Bot Mac Menu Bar

## 概要
SwitchBot APIを使って温度、湿度、絶対湿度Macのメニューバーに表示します。

<img width="269" alt="スクリーンショット 2021-10-06 15 40 19" src="https://github.com/merarli/merarli-switch-bot-mac-menu-bar/assets/32351460/6da64190-98a7-4a97-b664-deacc6eeac1b">

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
