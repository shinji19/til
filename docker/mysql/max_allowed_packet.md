# 大きいデータを入れる時困るので対応する

    services:
      mysql:
        image: mysql:5.7.20
        command: --max_allowed_packet=32505856 
