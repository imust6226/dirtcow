# dirtcow
脏牛Linux本地提权漏洞复现(CVE-2016-5195)
0、使用命令 uname -a 命令查看linux内核信息
1、下载EXP到本地/服务器
2、使用 gcc -pthread dirty.c -o dirty -lcrypt 命令对dirty.c进行编译，生成一个dirty的可执行文件
3、执行 ./dirty pass ，即可进行提权，pass为设置的密码

