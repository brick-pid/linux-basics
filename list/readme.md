### 介绍
该项目是对 Linux ls 命令的简单实现

### 参数
实现自定义选项 r,a,l,h,m 以及 --
- r 递归方式列出子目录（每项要含路径，类似find的-print输出风
格，需要设计递归程序）
- a 列出文件名第一个字符为圆点的普通文件（默认情况下不列出文
件名首字符为圆点的文件）
- l 后跟一整数，限定文件大小的最小值（字节）
- h 后跟一整数，限定文件大小的最大值（字节）
- m 后跟一整数n，限定文件的最近修改时间必须在n天内
- -- 显式地终止命令选项分析