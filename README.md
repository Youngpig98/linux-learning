# Learning notes for Linux

​	此项目为Linux学习中的知识总结、项目源码等，未完待续。

## 基础篇

* [Linux常用实战脚本](https://blog.csdn.net/ver_mouth__/article/details/128812171)

### 进程管理

- [基本命令](./workspace/lesson6)
- [nohup命令详解](./workspace/lesson4)
- [klill命令](./workspace/lesson3)
- [top命令的数据从哪儿来？](./workspace/lesson9)

### 网络管理

- [基础命令](./workspace/lesson8)
- [Linux网络设置](https://blog.csdn.net/ver_mouth__/article/details/124101310)
- [VMware三种网络模式配置详解](https://blog.csdn.net/m0_61503020/article/details/128215674)
- [NAT与PAT](https://blog.csdn.net/ver_mouth__/article/details/123525355)
- [FTP文件传输协议](https://blog.csdn.net/ver_mouth__/article/details/124179311)
- [SSH远程访问控制](https://blog.csdn.net/ver_mouth__/article/details/124225027)

### 文件管理

- [基础命令](./workspace/lesson13)
- [打包和解压](./workspace/lesson1)
- [⽂件查看和处理](./workspace/lesson2)
- [source命令](./workspace/lesson5)
- [用户和用户组管理](./workspace/lesson10)
- [软件包管理](./workspace/lesson7)

### 磁盘管理

- [基础命令](./workspace/lesson11)
- [磁盘管理与文件系统](https://blog.csdn.net/ver_mouth__/article/details/123819498)
- [LVM的使用](./workspace/lesson12)
- [df和du的使用及区别](https://blog.csdn.net/liuyang9909/article/details/123249917)
- [服务器硬件及RAID配置实战](https://blog.csdn.net/ver_mouth__/article/details/123849048)




## 进阶篇

### 进程管理 

- [进程、线程基础知识](https://xiaolincoding.com/os/4_process/process_base.html) 
- [进程间有哪些通信方式？](https://xiaolincoding.com/os/4_process/process_commu.html) 
- [多线程冲突了怎么办？](https://xiaolincoding.com/os/4_process/multithread_sync.html) 
- [怎么避免死锁？](https://xiaolincoding.com/os/4_process/deadlock.html) 
- [什么是悲观锁、乐观锁？](https://xiaolincoding.com/os/4_process/pessim_and_optimi_lock.html) 
- [一个进程最多可以创建多少个线程？](https://xiaolincoding.com/os/4_process/create_thread_max.html) 
- [线程崩溃了，进程也会崩溃吗？](https://xiaolincoding.com/os/4_process/thread_crash.html)
- [Linux的第一个进程](./workspace/senior/p3)
- [什么是僵尸进程与孤儿进程](https://blog.csdn.net/a745233700/article/details/120715371)
- [strace命令详解](https://www.cnblogs.com/machangwei-8/p/10388883.html)

### 网络管理

- [DNS域名解析服务](https://blog.csdn.net/ver_mouth__/article/details/124155268)
- [PXE高效批量网络装机](https://blog.csdn.net/ver_mouth__/article/details/124299258)

### 文件管理

- [Linux中软连接与硬连接](./workspace/senior/p1)
- [rm删除文件后磁盘仍然占用](https://blog.csdn.net/zwe7616175/article/details/100728273)
- [Find命令查找最近几天修改的文件](https://blog.csdn.net/linux_hua130/article/details/120782534)
- [深入理解Linux文件系统与日志分析](https://blog.csdn.net/ver_mouth__/article/details/124039105)

### Namespace

- [UTS Namespace](./workspace/namespace/uts-namespace)
- [User Namespace](./workspace/namespace/user-namespace)



## Quiz

- [iptables四表五链](https://mp.weixin.qq.com/s/bwK_ECwmL6OAjKHkiqGNpA)
- [Linux中grep|awk|sort|uniq](./workspace/senior/p2)
- [Linux中buffer和cache的区别](https://www.php.cn/linux-489224.html)



## 实战篇

### 项目



## Book



## 杂谈

- [服务器BMC与IPMI基础知识](https://blog.csdn.net/star871016/article/details/112257689)
- [IPMI与iDrac的区别](https://blog.csdn.net/sj349781478/article/details/122276933)

## Blog

- [赐我白日梦](https://www.cnblogs.com/ZhuChangwu/category/1509541.html)
- [糖醋-小排顾](https://blog.csdn.net/ver_mouth__?type=blog)

## Video



## 系统信息和性能查看

| 常用命令                    | 作用                               |
| --------------------------- | ---------------------------------- |
| **uname -a**                | **查看内核/OS/CPU信息**            |
| uname -r                    | 查看内核版本                       |
| uname -m                    | 查看处理器架构                     |
| arch                        | 查看处理器架构                     |
| hostname                    | 查看计算机名                       |
| who                         | 显示当前登录系统的⽤户             |
| who am i                    | 显示登录时的⽤户名                 |
| whoami                      | 显示当前⽤户名                     |
| cat /proc/version           | 查看linux版本信息                  |
| cat /proc/cpuinfo           | 查看CPU信息                        |
| cat /proc/interrupts        | 查看中断                           |
| cat /proc/loadavg           | 查看系统负载                       |
| uptime                      | 查看系统运⾏时间、⽤户数、负载     |
| env                         | 查看系统的环境变量                 |
| lsusb -tv                   | 查看系统USB设备信息                |
| lspci -tv                   | 查看系统PCI设备信息                |
| lsmod                       | 查看已加载的系统模块               |
| grep MemTotal /proc/meminfo | 查看内存总量                       |
| grep MemFree /proc/meminfo  | 查看空闲内存量                     |
| free -m                     | 查看内存⽤量和交换区⽤量           |
| date                        | 显示系统⽇期时间                   |
| cal 2021                    | 显示2021⽇历表                     |
| top                         | 动态显示cpu/内存/进程等情况        |
| vmstat 1 20                 | 每1秒采⼀次系统状态，采20次        |
| iostat                      | 查看io读写/cpu使⽤情况             |
| 查看io读写/cpu使⽤情况      | 查询cpu使⽤情况（1秒⼀次，共10次） |
| sar -d 1 10                 | 查询磁盘性能                       |



## 常⻅系统服务命令



| 常用命令                   | 作用         |
| -------------------------- | ------------ |
| chkconfig --list           | 列出系统服务 |
| service <服务名> status    | 查看某个服务 |
| service <服务名> start     | 启动某个服务 |
| service <服务名> stop      | 终⽌某个服务 |
| service <服务名> restart   | 重启某个服务 |
| systemctl status <服务名>  | 查看某个服务 |
| systemctl start <服务名>   | 启动某个服务 |
| systemctl stop <服务名>    | 终⽌某个服务 |
| systemctl restart <服务名> | 重启某个服务 |
| systemctl enable <服务名>  | 关闭⾃启动   |
| systemctl disable <服务名> | 关闭⾃启动   |

