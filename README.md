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

1. [全般](../../wiki/UnitTest-Tips-General)
 * [テストメソッドの命名](../../wiki/UnitTest-Tips-General#wiki-method_naming)
 * [テストメソッドの整理](../../wiki/UnitTest-Tips-General#wiki-organize_test_methods)
 * [テストクラスの整理](../../wiki/UnitTest-Tips-General#wiki-organize_test_classes)
 * [privateフィールドの検証](../../wiki/UnitTest-Tips-General#wiki-verify_private_fields)
 * [privateメソッドのテスト](../../wiki/UnitTest-Tips-General#wiki-test_private_methods)
 * [void型メソッドのテスト](../../wiki/UnitTest-Tips-General#wiki-test_void_methods)
 * [パラメータ化テスト](../../wiki/UnitTest-Tips-General#wiki-parameterized_test)
 * [パラメータ化テストの整理](../../wiki/UnitTest-Tips-General#wiki-organize_parameterized_test)
 * [定数の変更](../../wiki/UnitTest-Tips-General#wiki-change_constants)
1. [例外](#todo)
1. [通信](../../wiki/UnitTest-Tips-Connection)
 * [通信状態の変更](../../wiki/UnitTest-Tips-Connection#wiki-change_connection_state)
 * [HTTP通信の外部依存排除](../../wiki/UnitTest-Tips-Connection#wiki-stub_http_connection)
1. [データベース](#todo)
1. [非同期処理](../../wiki/UnitTest-Tips-Asynchronous)
 * [非同期処理の完了を待つ](../../wiki/UnitTest-Tips-Asynchronous#wiki-await_async_process)
 * [メインスレッドで実行する](../../wiki/UnitTest-Tips-Asynchronous#wiki-run_on_main_thread)
1. [ログ](../../wiki/UnitTest-Tips-Log)
 * [ログ出力先の変更](../../wiki/UnitTest-Tips-Log#wiki-change_log_output)
 * [ログ出力の検証](../../wiki/UnitTest-Tips-Log#wiki-verify_log_output)
 * [LogItemのアサーション](../../wiki/UnitTest-Tips-Log#wiki-assert_log_item)
1. [Activity](../../wiki/UnitTest-Tips-Activity)
 * [Activityライフサイクルの制御](../../wiki/UnitTest-Tips-Activity#wiki-activity_lifecycle)
 * [Activityの起動検証](../../wiki/UnitTest-Tips-Activity#wiki-verify_starting_activity)
1. [Widget](../../wiki/UnitTest-Tips-Widget)
 * [ウィジェットの生成](../../wiki/UnitTest-Tips-Widget#create_app_widget)

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
