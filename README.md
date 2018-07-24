## 準備
Firebase CLIインストール
```
npm i -g firebase
```

Firebase CLIでログイン
```
firebase login
```

.firebaserc
```
cp .firebaserc_sample .firebaserc
```
and edit it.

## 使い方
ローカルサーバー
```
firebase serve --only functions
```
デプロイ
```
firebase deploy --only functions
```
