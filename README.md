# ionic4-firestore-sample2

このページは、[Building a CRUD Ionic application with Firestore](https://javebratt.com/crud-ionic-firestore/)をほぼ写経しながら、ionic4アプリ作成の練習を行っているものです。

src/environments/environment.ts は、ご自身で作成して、ご自身のfirebaseのAPIキーその他をコピペしてください。

```javascript:environment.ts
// <>となっている部分は、自分のapiKeyを入力
export const environment = {
  production: false,
  firebase: {
    apiKey: '<your-key>',
    authDomain: '<your-project-authdomain>',
    databaseURL: '<your-database-URL>',
    projectId: '<your-project-id>',
    storageBucket: '<your-storage-bucket>',
    messagingSenderId: '<your-messaging-sender-id>'
  }
};
```

## インストール方法


`git clone https://github.com/adash333/ionic3-firebase-todo3.git`

modify "src/environments/environment.ts"

Run `npm install`to install all dependencies.

Run `ionic serve`to start the development environment.


作成経過の一部は以下に記載しています。

http://i-doctor.sakura.ne.jp/dokuwiki/doku.php/ionic4%E3%81%A8firestore%E3%81%A7crud#ionic4%E3%81%A8firestore%E3%81%A7crud1



## 開発環境

```
Windows 8.1 Pro
VisualStudioCode
git version 2.16.1.windows.4

Node v8.12.0
npm 6.4.1
Ionic (Ionic CLI) 4.2.0
@ionic/angular 4.0.0-beta.12

firebase@5.5.3
angularfire2@5.0.2
rxjs@6.2.2
(npm list --depth=0 にて確認)
```
