# sdsqlite

NOTE: sdsqlite for bjsdwl commlibs library, DO NOT DELETE IT!

## 1. 下载地址：
https://www.sqlite.org/2024/sqlite-autoconf-3460100.tar.gz

## 2. 编译静态库：
```c
打开 x64 Native Tools Command Prompt for VS 2022 控制台:

1. cl -Os -O2 -D_USRDLL -DSQLITE_ENABLE_FTS5 -DSQLITE_ENABLE_RTREE -DSQLITE_ENABLE_COLUMN_METADATA -DSQLITE_ENABLE_UNLOCK_NOTIFY shell.c sqlite3.c -Fesqlite3.exe

2. lib sqlite3.obj