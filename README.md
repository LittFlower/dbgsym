一个根据指定 libc 获取调试信息的小工具。

很大程度上参考了[这个项目](https://github.com/veritas501/dl_dbgsym/blob/master/dl_dbgsym.py) 和 ltfa1l 师傅的 exp

这个工具可以根据你给定的 libc.so，在 ubuntu 官网下载对应版本的 deb 包，然后将 ld.so 放到当前目录，并把 libc.so 和 ld.so 的调试信息放到对应的 /usr/lib/debug/.debug-id 里。

自用脚本，欢迎各位师傅测试 Pr。
