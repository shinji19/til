# データベースバックアップ・復元

     pg_dumpall -Htarget.host -Uuser > dump.sql
     psql -f dump.sql -Uuser
