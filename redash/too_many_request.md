# ログイン画面でtoo many requestが出てログインできなくなった場合

    # 対処療法。環境変数にある制限をあげる
    REDASH_THROTTLE_LOGIN_PATTERN=50/hour
