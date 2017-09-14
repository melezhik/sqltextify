# SYNOPSIS

Wrapper for [sqltextify.pl](https://metacpan.org/pod/distribution/Sql-Textify/script/sqltextify.pl)

# INSTALL

    $ sparrow plg install sqltextify

# USAGE

    $ sparrow project create databases
    $ sparrow task create databases users sqltextify
    $ sparrow task ini databases/users

    ---
      sql: select * from users
      args:
        - conn: dbi:mysql:users
        - username: admin
        - password: test

    $ sparrow task run databases/users

# Plugin maintainer

Alexey Melezhik

