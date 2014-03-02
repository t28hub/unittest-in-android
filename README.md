# 概要
AndroidアプリケーションプロジェクトにRobolectricを利用したユニットテストの導入方法をまとめます。

## はじめに
ユニットテスト初学者がまとめた内容のため、誤った解釈など不備があるかも知れません。  
加筆・修正は適宜行う予定です。   

## ツール
ユニットテストで導入したツールについてまとめます。

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
1. [EclEmma](#todo)
 * []()

## Tips
あくまで個人的なユニットテストに関するTipsです。

1. [全般](../../wiki/Tips-General)
 1. [テストメソッドの命名](../../wiki/Tips-General#wiki-method_naming)
 1. [テストメソッドの整理](../../wiki/Tips-General#wiki-organize_test_methods)
 1. [テストクラスの整理](../../wiki/Tips-General#wiki-organize_test_classes)
 1. [privateフィールドの検証](../../wiki/Tips-General#wiki-verify_private_fields)
 1. [privateメソッドのテスト](../../wiki/Tips-General#wiki-test_private_methods)
 1. [パラメータ化テスト](../../wiki/Tips-General#wiki-parameterized_test)
1. [例外](#todo)
1. [通信](#todo)
1. [データベース](#todo)
1. [非同期処理](#todo)
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
