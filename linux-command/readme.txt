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
        10.

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


