# dockerでredashのdbをマイグレーション

    # docker-compose.ymlのredashバージョンをあげる
    docker-compose run --rm server manage db upgrade
