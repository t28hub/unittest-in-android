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
### 1. 環境構築
環境構築の方法についてまとめます。各種ライブラリについては[後述](#library)します。

#### [1.1. プロジェクトの作成](../../wiki/Environment/#wiki-create_project)
#### [1.2. ライブラリの追加](../../wiki/Environment#wiki-add_library)
#### [1.3. 実行構成の設定](../../wiki/Environment#wiki-run_configuration)
#### [1.4. テストの作成と実行](../../wiki/Environment#wiki-write_unit_test)

<a name="library"></a>
### 2. ライブラリ
ユニットテストで導入したライブラリやプラグインについてまとめます。

#### [2.1. Robolectric](../../wiki/2.1.-Robolectric)
* [ユニットテストの課題](../../wiki/2.1.-Robolectric#wiki-problem_with_unit_test)
* [AndroidTestCaseとの比較](../../wiki/2.1.-Robolectric#wiki-comparison_tools)
* [Robolectricの例](../../wiki/2.1.-Robolectric#wiki-example)
* [Shadowオブジェクト](../../wiki/2.1.-Robolectric#wiki-shadow_object)
* [カスタムShadow](../../wiki/2.1.-Robolectric#wiki-custom_shadow)

#### [2.2. FEST](../../wiki/2.2.-FEST)
 * [アサーションとは](../../wiki/2.2.-FEST#wiki-assertion)
 * [アサーションの比較](../../wiki/2.2.-FEST#wiki-comparison)
 * [Android FEST](../../wiki/2.2.-FEST#wiki-fest_android)
 * [カスタムアサーション](../../wiki/2.2.-FEST#wiki-custom_assertion)

#### [2.3. Mockito](../../wiki/2.3.-Mockito)
 * [テストダブルとは](../../wiki/2.3.-Mockito#wiki-test_double)
 * [出来ないこと](../../wiki/2.3.-Mockito#wiki-impossible_things)
 * [簡単な例](../../wiki/2.3.-Mockito#wiki-simple_example)
 * [便利な機能](../../wiki/2.3.-Mockito#wiki-useful_features)

<a name="tips"></a>
### 3. Tips
あくまで個人的なユニットテストに関するTipsです。

#### [3.1. 全般](../../wiki/3.1.-全般)
* [テストメソッドの命名](../../wiki/3.1.-全般#wiki-method_naming)
* [テストメソッドの整理](../../wiki/3.1.-全般#wiki-organize_test_methods)
* [テストクラスの整理](../../wiki/3.1.-全般#wiki-organize_test_classes)
* [privateフィールドの検証](../../wiki/3.1.-全般#wiki-verify_private_fields)
* [privateメソッドのテスト](../../wiki/3.1.-全般#wiki-test_private_methods)
* [void型メソッドのテスト](../../wiki/3.1.-全般#wiki-test_void_methods)
* [パラメータ化テスト](../../wiki/3.1.-全般#wiki-parameterized_test)
* [パラメータ化テストの整理](../../wiki/3.1.-全般#wiki-organize_parameterized_test)
* [定数の変更](../../wiki/3.1.-全般#wiki-change_constants)

#### [3.2. 例外](../../wiki/3.2.-例外)


#### [3.3. 通信](../../wiki/3.3.-通信)
 * [通信状態の変更](../../wiki/3.3.-通信#wiki-change_connection_state)
 * [HTTP通信の外部依存排除](../../wiki/3.3.-通信#wiki-stub_http_connection)

#### [3.4. データベース](../../wiki/3.4.-データベース)


#### [3.5. 非同期処理](../../wiki/3.5.-非同期処理)
* [非同期処理の完了を待つ](../../wiki/3.5.-非同期処理#wiki-await_async_process)
* [メインスレッドで実行する](../../wiki/3.5.-非同期処理#wiki-run_on_main_thread)
 
#### [3.6. ログ](../../wiki/3.6.-ログ)
* [ログ出力先の変更](../../wiki/3.6.-ログ#wiki-change_log_output)
* [ログ出力の検証](../../wiki/3.6.-ログ#wiki-verify_log_output)
* [LogItemのアサーション](../../wiki/3.6.-ログ#wiki-assert_log_item)

#### [3.7. Activity](../../wiki/3.7.-Activity)
* [Activityライフサイクルの制御](../../wiki/3.7.-Activity#wiki-activity_lifecycle)
* [Activityの起動検証](../../wiki/3.7.-Activity#wiki-verify_starting_activity)

#### [3.8. Widget](../../wiki/3.8.-Widget)
* [ウィジェットの生成](../../wiki/3.8.-Widget#create_app_widget)

#### [3.9. Service](../../wiki/3.9.-Service)                                       
* [Serviceライフサイクルの制御](../../wiki/3.9.-Service#wiki-service_lifecycle) 
* [Serviceの起動検証](../../wiki/3.9.-Service#wiki-verify_starting_service)        
* [Serviceの停止検証](../../wiki/3.9.-Service#wiki-verify_stopping_service)        
                                                                                   
#### [3.10. ContentProvider](../../wiki/3.10.-ContentProvider)                     
* [ContentProviderの登録](../../wiki/3.10.-ContentProvider#wiki-register_content_provider)
* [ステートメントの取得](../../wiki/3.10.-ContentProvider#wiki-get_statements)  
* [changeNotifyの検証](../../wiki/3.10.-ContentProvider#wiki-verify_changes)       
                                                                                   
#### [3.11. BroadcastReceiver](../../wiki/3.11.-BroadcastReceiver)                 
* [BroadcastReceiverの登録確認](../../wiki/3.11.-BroadcastReceiver#wiki-verify_registered)
* [特定のBroadcastReceiverの取得](../../wiki/3.11.-BroadcastReceiver#wiki-get_receiver)
* [Intentの受け取り](../../wiki/3.11.-BroadcastReceiver#wiki-receive_intents)   

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
1. [C0/C1/C2](http://blogs.wankuma.com/episteme/archive/2009/03/10/169420.aspx)
ユニットテストのカバレッジ(C0/C1/C2)についてわかりやすく解説されています。
