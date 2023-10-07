# ez-firebase-auth

Firebase Authentication を使って Google ログインし、ユーザのアクセストークンを JWT の形式で取得できます。

## 使い方

- `index.html` の `firebaseConfig` に Firebase の設定を記述します。
- `go run main.go` でサーバーを起動します。
- ブラウザから http://localhost:3000 にアクセスします。
- ログインすると、画面にログインしたユーザーのアクセストークンが JWT で表示されます。

## その他

- トークンの検証: https://jwt.io
- kid に紐づく公開鍵の取得先 :https://www.googleapis.com/robot/v1/metadata/x509/securetoken@system.gserviceaccount.com
