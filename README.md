# ez-firebase-auth

Firebase Authentication を使って Google ログインし、ユーザのアクセストークンを JWT の形式で取得できます。

## 使い方

- `index.html` の `firebaseConfig` に Firebase の設定を記述します。
- `go run main.go` でサーバーを起動します。
- ブラウザから http://localhost:3000 にアクセスします。
- ログインすると、画面にログインしたユーザーのアクセストークンが JWT で表示されます。
