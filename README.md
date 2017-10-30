# memo-2017-10-30

## URL

* Concourse URL: https://35-200-104-177.sslip.io (Github認証)
* Nexus URL: https://nexus.ik.am (ユーザー名/パスワードは口頭で伝えます)

## Fly CLIダウンロード

* Mac: https://35-200-104-177.sslip.io/api/v1/cli?arch=amd64&platform=darwin
* Windows: https://35-200-104-177.sslip.io/api/v1/cli?arch=amd64&platform=windows
* Linux: https://35-200-104-177.sslip.io/api/v1/cli?arch=amd64&platform=linux

ダウンロードしてファイルを`fly`にrenameし、`PATH`の通ったディレクトリにコピーしてください。

## Concourseへのログイン方法

```
fly -t ws login -c https://35-200-104-177.sslip.io -n ws-(githubアカウント名)
```

コマンドを実行すると

```
logging in to team 'ws-pivot-tmaki'

navigate to the following URL in your browser:

    https://35-200-104-177.sslip.io/auth/github?team_name=ws-pivot-tmaki&fly_local_port=59400

or enter token manually: 
```

というメッセージが出ます。表示されているリンクをコピーしてブラウザでアクセスし、Githubにログインしてください。
