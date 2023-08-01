# 最初に

この研修では、チームでクライアントアプリケーション開発をVueでするためのハンズオン形式の研修です。

ハンズオンで作っていただくアプリケーションは社員の管理アプリになります。こちらのアプリ作成を通してVue開発の手法を学んでいきたいと思います。

基本的にはこのリポジトリをGitHubからフォークしていただき、個々で開発を行ってください。

ベースとなるリポジトリに答え合わせとなるブランチを用意しておきますので、分からないポイントや書き方がわからないことがある場合 `doc` フォルダのドキュメントを参照するか、答え合わせブランチを参照してください。

本研修のアプリは以下のような構成になっています。

```
.vscode
client
server
doc
```

**client** - クライアントアプリケーションフォルダになります。ほとんどこちらでの開発をお願いします。

**server** - 本アプリのサーバーがおいてあります。APIのパスがわからない場合など参照してください。

**doc** - この研修の資料が載っています。個々を参照し、順々に開発を行ってください。

それぞれのフォルダでアプリの起動方法に関するREADME.mdがありますのでご参照ください。

サーバー、クライアントともに`npm install`実行後は、こちらのディレクトリから`npm run dev`を実行しますと、サーバーとクライアントを同時に起動できます。