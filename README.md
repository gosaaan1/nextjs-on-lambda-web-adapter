# Next.js on Lambda Web Adapter

Next.js(14)をLambda Web Adapterで動かすCodeCatalystのブループリントです。

TypeScriptで開発が進められるように`crete-next-app`しています。

## CodeCatalystのセットアップ

- [Amazon CodeCatalyst Workshop](https://catalog.workshops.aws/integrated-devops/ja-JP)を参考にセットアップしておいてください。

## 使い方

1. CodeCatalystを開きます。
2. "Create project"をクリックします。
3. "Bring your own code"を選択します。
4. "GitHub repository"に`https://github.com/gosaaan1/nextjs-on-lambda-web-adapter.git`のコードが含まれたリポジトリを選択します。
5. CI/CD > Environments を開き、 Create environment をクリックします。
6. Environment detailsで Environment name `prd` を作ります。

## 参考

examples/nextjs(JavaScript)がベースになっています。

- [AWS Lambda Web Adapter](https://github.com/awslabs/aws-lambda-web-adapter)
