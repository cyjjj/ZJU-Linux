编写shell脚本，统计指定目录下的普通文件、子目录及执行文件的数目，统计该目录下所有普通文件字节数总和，目录的路径名字由参数传入。  
* 命令输入格式：  
  ```countfile [pathname]```
  传入参数至多1个，为统计的指定目录，当参数缺省（即传入参数为0个）时，默认统计当前工作目录。
* 输出结果：  
  输出显示的结果为该目录下的普通文件、子目录及可执行文件（包括普通文件、目录文件等各类文件）的数目，以及该目录下所以普通文件字节数总和。
