# redashでgoogle oauthを使ってhoge.com、fuga.comドメインのログインを許可する

    bin/run ./manage.py org set_google_apps_domains hoge.com,fuga.com
    # 別解(環境変数に次を入れる)
    IS_PUBLIC=true
    
    # 確認
    bin/run ./manage.py org show_google_apps_domains
