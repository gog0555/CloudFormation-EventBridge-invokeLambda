# 【CloudFormation】定時にLambda関数を起動するEventBridgeルール

## 概要
以前ClientVPNエンドポイントのサブネット関連付け・解除をするLambda関数を作成した。

管理コスト軽減・解除忘れによる課金を防ぐことを目的にEventBridgeで自動化した。

## 参考
EventBridgeにコンソールで作成したルールをCloudFormationのコードにしてくれる機能があったため、それを利用した。

https://docs.aws.amazon.com/ja_jp/eventbridge/latest/userguide/rule-generate-template.html
