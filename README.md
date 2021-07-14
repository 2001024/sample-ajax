# sample-ajax
授業中のリソース置き場

ajaxのgetを行うためのテンプレート

# jQuery側のjsonオブジェクトの準備
```javascript
formData = {};
```
{}は空のjsonオブジェクト
```javascript
formData["paraml"] = "テスト";
```
formDataのプロパティはFormdata["プロパティ文字列"]に値をセットして作成される。
formDataのプロパティはFormdata.プロパティ文字列と書くこともできます。
```javascript
formData.paraml = "テスト";
```
##jQuery側からサーバへデータを送る
