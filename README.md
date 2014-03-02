# 概要
AndroidアプリケーションプロジェクトにRobolectricを利用したユニットテストの導入方法をまとめます。

## はじめに
ユニットテスト初学者がまとめた内容のため、誤った解釈など不備があるかも知れません。  
加筆・修正は適宜行う予定です。   

<a name="outline"></a>
## アウトライン
1. [ツール](#tools)
1. [Tips](#tips)

<a name="tools"></a>
### ツール
ユニットテストで導入したツールについてまとめます。

1. [Robolectric](#robolectric)
 * [ユニットテストの課題](../../wiki/Robolectric#wiki-problem_with_unit_test)
 * [AndroidTestCaseとの比較](../../wiki/Robolectric#wiki-comparison_tools)
 * [Robolectricの例](../../wiki/Robolectric#wiki-example)
 * [Shadowオブジェクト](../../wiki/Robolectric#wiki-shadow_object)
 * [カスタムShadow](../../wiki/Robolectric#wiki-custom_shadow)
1. [Mockito](#mockito)
 * []()
1. [FEST](#fest)
 * []()
1. [EclEmma](#eclemma)
 * []()
 
<a name="tips"></a>
### Tips
あくまで個人的なユニットテストに関するTipsです。

1. [全般](#todo)
 1. [テストメソッドの命名](#todo)
 1. [テストメソッドの整理](#todo)
 1. [テストクラスの整理](#todo)
 1. [privateフィールドの検証](#todo)
 1. [privateメソッドのテスト](#todo)
 1. [パラメータ化テスト](#todo)
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
