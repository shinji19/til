# datetimeのフォーマットを変更

## 2.0.x 系 (未検証)

HH:mmと決め打ちになっているのでこれを置換する
https://github.com/getredash/redash/blob/release/2.0.x/redash/settings.py#L260

    sed -i".bak" "s/HH:mm/HH:mm:ss/g" settings.py
    
## 3.0.x 系 (未検証)

2.0.xと同じ

https://github.com/getredash/redash/blob/release/3.0.x/redash/settings.py#L285

## 4系(2018-02-16時点) (未検証)

2.0.xと同じ（なぜかhandlers/authenticationに移動)

https://github.com/getredash/redash/blob/master/redash/handlers/authentication.py#L177
