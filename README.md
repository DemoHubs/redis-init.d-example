# redis-init.d-example

* 不同的linux发行版写法有偏差


** 使用源码安装后，用于制作init.d文件 方便管理redis进程


cd redis-xx.xx.xx

make && make install

将会把redis-server、redis-cli、redis-benchmark、redis-check-aof、redis-check-dump 五个文件复制到 /usr/local/bin/下
