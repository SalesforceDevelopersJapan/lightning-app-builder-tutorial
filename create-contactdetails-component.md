---
layout: module
title: Module 7&#58; モバイルでLightningアプリをテストする
---

このモジュールでは、有効化したLightningアプリケーションをモバイル環境でテストを行います。これはSalesforceの本番環境やテスト環境で、エンドユーザに開発したモバイルアプリケーションがどのように見えるかを確認する際に有用な方法です。基本的にはChromeのデスクトップ版ブラウザのモバイルビューもしくはスマートフォーン内のSalesforce1モバイルアプリを利用しますが、今回はChromeのモバイルビューでテストする方法を説明します。

## 何を学ぶことができるか
- Salesforceの開発において、ChromeブラウザやSalesforce1アプリを利用してどのようにモバイルのテストを行うか。


## ステップ 1: Chromeモバイルビューへスイッチする

1. もしSalesforce環境にログインしていなければ、Choromeブラウザでログインを行います。ブラウザのURLアドレスバーに入力を行います。
2. /one/one.app を現在のSalesforceインスタンスのURLドメインの後ろに追加します。例えばDeveloper Editionがna15にある場合、ログインした際のURLは https://na15.salesforce.com/home/home.jsp　のようになっています。 Salesforce1モバイルアプリの画面を表示するには /home/home.jsp を /one/one.app に変更します。
これでSalesforce1モバイルの画面が表示されます。

3. ブラウザウィンドをリサイズして、モバイルのスクリーンに近いサイズに変更します。


## ステップ 2: 作成したモバイルアプリケーションを表示する
Lightningアプリケーションを有効化する際、Salesforce1ナビゲーションパネルにレイアウトを行いました。

1. サイドバーナビゲーションを開くには画面に左上隅にあるアイコンをクリックします
![](images/mobile1.png)

2. **フィールドセールスアプリケーション**をクリックします

![](images/mobile2.png)

おめでとうございます。これでたった数分で、一行もコードを書くことなくLightningアプリケーションをSalesforce上に作成し、複数のアクションを追加し、モバイルでテストを行うことができました。

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-searchbar-component.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> 戻る</a>
<a href="show-custom.component.html" class="btn btn-default pull-right">次へ <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
