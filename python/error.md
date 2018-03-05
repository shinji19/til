# エラーを標準出力にだす

    import logging

    logger = logging.getLogger()
    logger.setLevel(logging.DEBUG)

    # ログ出力を標準出力へ
    ch = logging.StreamHandler(sys.stdout)
    ch.setLevel(logging.DEBUG)

    formatter = logging.Formatter('%(levelname)s - %(asctime)s - %(name)s - %(funcName)s - %(message)s')
    ch.setFormatter(formatter)
    logger.addHandler(ch)
