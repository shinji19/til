# dockerでredashを立ち上げる際に初回実行するべきコマンド
redashを起動して初期化する際、postgresとredisが動作している状態でないとcreate_dbできない

    docker-compose up -d postgres redis
    # postgresが落ち着くまで待機
    docker-compose run --rm server create_db
    docker-compose up -d

  
