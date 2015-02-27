---
layout: module
title: モジュール 6&#58; アクションの追加と有効化
---

このモジュールでは、Salesforce1モバイルアプリのナビゲーションからアクセスし、営業担当者が活動の記録やケースの作成、Leadの新規追加、タスクの設定などを簡単に行えるようにアプリケーションにアクションを追加し、アプリケーションを有効化します。

## 何を学ぶことができるか

- Lightningページにグローバルアクションを追加する方法
- LightningページをSalesforce1モバイルアプリに追加する

## ステップ 1: アクションの追加

アクションにはSalesforce1モバイルアプリ上でユーザが簡単にデータを作成したり編集するためのショートカットが用意されています。ユーザが一般的な営業活動をする際に有効な、標準で用意されているいくつかのアクションを利用します。

1. 右側のサイイドバーにある **ページ** をクリックします。. アプリケーションの設定可能なプロパティが表示されます。
![](images/pageclick.png)

2. 右側サイドバーの下部のアクションにある、 **選択...** をクリックします。
![](images/action1.png)

3. **利用可** リストより、 **活動の記録**, **新規ケース**、 **新規リード** 、**新規ToDo** のクイックアクションを**洗濯済み** リストへ移動します。

    ![Select New Actions](images/actions2.png)

4. **Ok** をクリックし、アクションをLightningページに追加します。

5. アプリケーションビルダーの右上にある**保存**ボタンをクリックします。

> 右側サイドバー最下部にある **アクション** プロパティ には`LogACall`, `NewCase`,`NewLead` , `NewTask` のアクションが表示さているはずです。

## ステップ 2: アプリケーションの有効化

> **有効化** 機能はアプリケーションビルダーから離れることなくLightningページをアプリケーションに組み込むための機能です。この機能を利用すると、通常はSalesforceタブの設定方法である _設定 > 作成 > タブ > Lightning Page タブ_ に自動的にタブが追加され、モバイルナビゲーションの設定方法である _設定 > モバイル管理 > モバイルナビゲーション_ にも設定がおこなわれます。

1. **有効化** をクリックし、Salesforce1モバイルナビゲーションへ追加します。

2. **タブの表示ラベル** には`フィールドセールス`を入力します。

3. 次に **タブアイコン** の **変更...**をクリックします。

4. 好きなアイコン選択します。 アイコンを選択してウィンドウを閉じると、現在のウィンドウにもアイコンの変更が反映されます。

5. 右側のSalesforce1ナビゲーション位置パネルで、 **フィールドセールス** のSalesforce1ナビゲーション上の位置を設定します。ここでは **Today** タブの下に移動します。

   ![Nav Items List](images/navposition.png)

6. **有効化**をクリックします。

これでアプリケーションはテスト可能になりました。


<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-contactlist-component.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> 戻る</a>
<a href="create-contactdetails-component.html" class="btn btn-default pull-right">進む <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
