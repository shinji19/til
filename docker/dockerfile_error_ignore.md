# DockerfileのRUNコマンドでエラーを無視したい時
## ; exit 0　をつける
    FROM centos:7
    # 途中でエラーになるがexit 0で握りつぶす
    RUN ls && exit 1; exit 0 && ps 
    
