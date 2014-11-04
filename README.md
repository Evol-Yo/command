command
=======

linux命令源码注释

对linux命令实现感兴趣吗？来吧！我们共同完成这个注释工作吧，哪怕仅仅只是翻译也好，也能从中学到东西。“源码之前，了无秘密”

    编译步骤：
    1、将coreutils-5.0.tar源码包解压
        $tar -xvf coreutils-5.0.tar
    2、进入coreutils-5.0目录
        $cd coreutils-5.0
        （请阅读README和INSTALL文件）
    3、执行./configure
        $./configure
    4、修改Makefile文件，将CFLAGS = -g -O2改为CFLAGS = -g,或者按同样方式修改src/Makefile
    5、在此目录下执行make，或者进入src目录执行make
        $make 或者 $cd src; make
    6、现在可以用gdb对每一个命令进行调试了


将你的工作发布出来吧！
