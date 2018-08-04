学了这么久的Linux，整理下

目录：
        1.特殊文件: /dev/null和/dev/tty
        2.简单的命令跟踪
        3.正则表达式基本语法描述
        4.使用cut命令截取字段
        5.wc命令计算行数、字数以及字符数
        6.提取开头或结尾数行
        7.grep、egrep与正则表达式用法总结  (2.txt)
        8.sed   (3.txt)  
        9.awk  （4.txt)
        11.awk编程   (5.txt)
        12.行的排序命令sort
        13.删除重复行的命令uniq
        14.文件压缩解压命令tar
        15.大文件拆分命令split   (6.txt)
        16.文件查找命令find   
        17.xargs命令   (7.txt)     
        18.和系统运行状况相关的Shell命令    (8.txt)
        19.和系统运行进程相关的Shell命令    (9.txt)
        20.通过管道组合Shell命令获取系统运行数据 
        21.通过管道组合Shell命令进行系统管理  (10.txt)
        22.交互式使用Bash Shell      (11.txt)
        23.Bash Shell编程 (12.txt)

有些来自于参考网站
https://github.com/me115/linuxtools_rst/tree/master/



进阶篇：
https://github.com/me115/linuxtools_rst/tree/master/advance
01_program_build 程序构建
02_program_debug 程序调试
03_optimization 性能优化


01_program_build 程序构建
  目录
    配置
    编译
      makefile编写的要点
      makefile中的全局自变量
      更多选择 CMake
      编译依赖的库
      g++编译
    安装
    总结
    
02_program_debug 程序调试
  目录
    进程调试
      gdb 程序交互调试
      pstack 跟踪栈空间
      strace 分析系统调用
    目标文件分析
      nm
      objdump
      readelf
      size 查看程序内存占用
      file 文件类型查询
      strings 查询数据中的文本信息
      fuser 显示文件使用者
      xxd 十六进制显示数据
      od

03_optimization 性能优化
  目录
    分析系统瓶颈
    分析内存瓶颈
    分析IO瓶颈
    分析进程调用
    优化程序代码
      gprof使用步骤
    其它工具


