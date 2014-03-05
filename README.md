# 概要
AndroidアプリケーションプロジェクトにRobolectricを利用したユニットテストの導入方法をまとめます。

## はじめに
ユニットテスト初学者がまとめた内容のため、誤った解釈など不備があるかも知れません。  
加筆・修正は適宜行う予定です。   

## コンテンツ

1. [環境構築](#environment)
1. [ライブラリ](#library)
1. [Tips](#tips)

<a name="environment"></a>
### 環境構築
環境構築の方法についてまとめます。各種ライブラリについては[後述](#library)します。

1. [プロジェクトの作成](../../wiki/Environment/#wiki-create_project)
1. [ライブラリの追加](../../wiki/Environment#wiki-add_library)
1. [実行構成の設定](../../wiki/Environment#wiki-run_configuration)
1. [テストの作成と実行](../../wiki/Environment#wiki-write_unit_test)

<a name="library"></a>
### ライブラリ
ユニットテストで導入したライブラリについてまとめます。

1. [Robolectric](../../wiki/Robolectric)
 * [ユニットテストの課題](../../wiki/Robolectric#wiki-problem_with_unit_test)
 * [AndroidTestCaseとの比較](../../wiki/Robolectric#wiki-comparison_tools)
 * [Robolectricの例](../../wiki/Robolectric#wiki-example)
 * [Shadowオブジェクト](../../wiki/Robolectric#wiki-shadow_object)
 * [カスタムShadow](../../wiki/Robolectric#wiki-custom_shadow)
1. [FEST](../../wiki/FEST)
 * [アサーションとは](../../wiki/FEST#wiki-assertion)
 * [アサーションの比較](../../wiki/FEST#wiki-comparison)
 * [Android FEST](../../wiki/FEST#wiki-fest_android)
 * [カスタムアサーション](../../wiki/FEST#wiki-custom_assertion)
1. [Mockito](../../wiki/Mockito)
 * [テストダブルとは](../../wiki/Mockito#wiki-test_double)
 * [出来ないこと](../../wiki/Mockito#wiki-impossible_things)
 * [簡単な例](../../wiki/Mockito#wiki-simple_example)
 * [便利な機能](../../wiki/Mockito#wiki-useful_features)

<a name="tips"></a>
### Tips
あくまで個人的なユニットテストに関するTipsです。

1. [全般](../../wiki/Tips:全般)
 * [テストメソッドの命名](../../wiki/Tips:全般#wiki-method_naming)
 * [テストメソッドの整理](../../wiki/Tips:全般#wiki-organize_test_methods)
 * [テストクラスの整理](../../wiki/Tips:全般#wiki-organize_test_classes)
 * [privateフィールドの検証](../../wiki/Tips:全般#wiki-verify_private_fields)
 * [privateメソッドのテスト](../../wiki/Tips:全般#wiki-test_private_methods)
 * [パラメータ化テスト](../../wiki/Tips:全般#wiki-parameterized_test)
1. [例外](#todo)
1. [通信](../../wiki/Tips:通信)
 * [通信状態の変更](../../wiki/Tips:Connection#wiki-change_connection_state)
 * [HttpClientの制御](../../wiki/Tips:Connection#wiki-stub_http_client)
 * [HttpURLConnectionの制御](../../wiki/Tips:Connection#wiki-stub_http_url_connection)
1. [データベース](#todo)
1. [非同期処理](../../wiki/Tips:Asynchronous)
 * [非同期処理の検証](../../wiki/Tips:Asynchronous#wiki-verify_async_process)
1. [Android](#todo)

## 参考資料
参考にさせて頂いた資料の一覧です。  

1. [JUnit実践入門](http://www.amazon.co.jp/dp/477415377X)  
JUnitの基本から実践的な内容まで初学者にも理解しやすい内容です。  
1. [JUnit in Action](http://www.amazon.co.jp/dp/1935182021)  
JUnit実践入門に記載されていない内容を補うことが出来ます。  
1. [xUnitPatterns](http://xunitpatterns.com)  
説明不要ですが、xUnitにおけるテストパターンが書かれています。  
1. [JUnit実践入門 xUnitTestPatternsで学ぶユニットテスト](http://www.slideshare.net/shuji_w6e/junit-xunittestpatterns)  
ユニットテストに関する基礎がわかりやすく解説されています。  
1. [xUnit Test PatternsのTest Doubleパターン](http://goyoki.hatenablog.com/entry/20120301/1330608789)  
テストダブルについてわかりやすく解説されています。

<a name="todo"></a>
## TODO
そのうち書きます。  
