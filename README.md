# fileprotected
Java版的文件目录保护程序，设定备份目录以及被保护目录，就可以在目标目录内文件、目录被删除、修改的时候，自动恢复，实现了目录内容的保护。
在CTF-AWD模式比赛中，可用于保护WEB目录不被删除、修改，out文件夹内含有已编译生成的jar可执行文件。

使用方法：

1.先cp备份目标保护目录到某位置

2.执行jar程序，java -jar fileprotected.jar /备份镜像目录 /被保护目录
