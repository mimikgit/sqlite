# sqlcipher

## https://github.com/sqlcipher/sqlcipher.git

The following instructions is to get and generate unified source code from sqlciper to use at edge and suppose copy files to ~/sqlite.

```shell
git clone https://github.com/sqlcipher/sqlcipher.git
cd sqlcipher
sh configure
make sqlite3.c
cp shell.c sqlite3.c sqlite3.h sqlite3ext.h ~/sqlite
```

