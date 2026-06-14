# Linux
## UNIX
- UNIX：1969发明第一个通用的操作系统，与C语言共生，B语言是c语言的前身
- BSD：出现了TCP/IP
- AIX系统 IBM一般银行之类大型机构使用
- UX 惠普
- Mac OS
- Linux
## FSF 自由软件基金会 GNU
- 重写一个操作系统：
    - 编译器：GNU C Compiler-GCC
    - 编辑器：emacs：Vi（编辑器之神），emacs（神的编辑器）
    - 软件许可GPL（自由软件、开源软件）
    - 库
    - 内核（Linux）
## Linux 发行版
- Rad Hat（美国版本，主要做企业）
    - centOS
    - 龙蜥
    - 欧拉EulerOS（华为服务器版本）
    - ...
- SUSE（德国版本，主要做企业）
- ubuntu（桌面运用的多）
- 红旗
- 麒麟
- 统信
- android 
### 操作系统
- kernel内核（汽车发动机）
- shell(壳-通过一个程序可以访问内核)
    - CLI command line interface 命令行
    - GUI graph user interface 人机交互界面
- 工具
## UNIX/Linux 目录结构
- 相对路径：无起始位置，cd abc、cd ../abc，~/abc，‘~’用户目录
- 绝对路径：cd /var、cd /etc/mysql
---
- '/' 
- '/bin'-binary程序,一些像ls等命令，以及可执行文件
- '/boot'-启动、引导程序bootloader
- '/root'-根用户，管理员的用户目录
- '/home'-用户目录，/home/bob
- '/dev'-设备的投影
- '/proc'-进程的投影
- '/sys'-系统投影
- '/etc'-配置信息（注册表）
- '/mnt'-mount挂载设备（U盘插入就会先挂载）
- '/cdrom'光盘
- '/media'媒体，自动挂载
- '/var'-可变的，例如日志，临时文件
- '/tmp'-临时目录
- '/usr'-unix system resouce含有include等头文件
- '/opt'-可选，手动安装的软件资源
- '/lib'-库目录:OpenCV,MySQL
- '/lib64'
- '/'

sudo 一管理员身份执行指令
sudo su 直接切换到root身份
exit 退出当前身份

## 作业
1. UNIX与c语言的关系
2. UNIX的主要发行版
3. GNU与Linux的关系
4. Linux的主要发行版
5. Linux目录结构
6. 什么是shell