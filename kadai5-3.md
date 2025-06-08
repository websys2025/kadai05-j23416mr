## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* エンドポイント:https://zipcloud.ibsnet.co.jp/api/search
  機能:日本の郵便番号から住所情報を取得するためのWeb API。
* リクエストとレスポンスのフォーマット
* リクエストのフォーマット:GETリクエスト　例：https://zipcloud.ibsnet.co.jp/api/search?zipcode=1000001
* レスポンスのフォーマット:JOSN形式　例：{"message": null,"results": [{"zipcode": "1000001","prefcode": "13","address1": "東京都","address2": "千代田区","address3": "千代田","kana1": "ﾄｳｷｮｳﾄ","kana2": "ﾁﾖﾀﾞｸ","kana3": "ﾁﾖﾀﾞ"}],"status": 200}
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* 名称：WorldTimeAPI、URL：https://worldtimeapi.org/
* エンドポイントと機能
* エンドポイント：https://worldtimeapi.org/api/timezone/{timezone}
* 機能:国の時刻を取得することができる。
* リクエストとレスポンスのフォーマット
*リクエストのフォーマット：GETリクエスト GET https://worldtimeapi.org/api/timezone/Asia/Tokyo
レスポンスのフォーマット:JOSN形式　{"abbreviation": "JST","datetime": "2025-06-08T14:31:29.123456+09:00","timezone": "Asia/Tokyo","utc_offset": "+09:00"}
### Q3-3. 感想
* 今回の課題で苦労したこと
* APIがよくわからなく何していいかわからなくなったこと
* 演習を通して理解できたこと
* APIの使い方やレスポンスの動き
* Web APIの利便性や課題など
* セキュリティが安全かどうか
