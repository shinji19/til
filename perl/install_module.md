# install_module

## モジュールを探す
[CPAN](http://search.cpan.org/)というサイトにまとまっているのでそこで検索


## ライブラリ導入(centos)
    # cpanコマンドを利用すると簡単
    yum install -y cpan
    export PERL_AUTOINSTALL='--defaultdeps'
    cpan
    cpan -i Log::Log4perl Class::Load YAML

#### DBD::Pg DBD::mysqlの導入

    # mysql-devel,postgresql-develがないとインストールできない
    yum install -y mysql-devel postgresql-devel
    cpan -i DBD::mysql DBD::Pg

