# defender-for-cloud-dast-demo
Microsoft Defender for Cloud で DAST を実行するデモ用リポジトリです。
[juice-shop](https://github.com/juice-shop/juice-shop) はセキュアではないサンプル Web アプリケーションで、以下のコマンドによりクローンしてきています。

```bash
git clone https://github.com/juice-shop/juice-shop.git --depth 1
```

## 前提条件
- [StackHawk の無料試用版をアクティブ化](https://auth.stackhawk.com/signup) が行われていること
- GitHub コードスキャンが有効になっていること
- DevOps 環境 (GitHub, Azure DevOps) が Defender for Cloud に接続されていること

## 参考ドキュメント
- StackHawk テクニカルオンボードガイド
https://learn.microsoft.com/ja-jp/azure/defender-for-cloud/onboarding-guide-stackhawk
