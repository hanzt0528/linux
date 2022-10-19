# linux

1. 使用ls -l /bin/sh命令，查看sh的实际链接指向

$ ls -l /bin/sh
lrwxrwxrwx 1 root root 4 10月 15 21:25 /bin/sh -> dash

2. 执行sudo dpkg-reconfigure dash命令，在弹出信息中选择No，将命令解析器换回bash
