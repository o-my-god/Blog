软件开发知识汇总
========

### 订阅
点击本页面右上角的 Watch 在弹出框中点击 Watching 订阅本博客，这样本博客的所有文章更新和评论都会在github首页出现。

当前互联网上的知识太多，并且杂乱，此博客对软件开发经典文章进行汇总分类，帮助开发者可以快速的学习。

## Posts
* [性能调优相关文章](#性能调优相关文章)<br>
     * [性能监视跟踪工具](#性能监视跟踪工具)<br>
     * [性能调优知识](#性能调优知识)<br>
* [网络服务器编程](#网络服务器编程)<br>
     * [不为人知的网络编程](#不为人知的网络编程)<br>
* [操作系统相关知识](#操作系统相关知识)<br>
     * [内存](#内存)<br>
* [中间件相关知识](#中间件相关知识)<br>
     * [redis](#redis)<br>
* [分布式相关知识](#分布式相关知识)<br>

### 网络服务开发三俩儿事系列

- [什么是并发](https://github.com/o-my-god/Blog/wiki/什么是并发)

- [为什么使用并发](https://github.com/o-my-god/Blog/wiki/为什么使用并发)

- [并发的基本挑战](https://github.com/o-my-god/Blog/wiki/并发的基本挑战)

- [并发问题的根源](https://github.com/o-my-god/Blog/wiki/并发问题的根源)

- [并发与操作系统](https://github.com/o-my-god/Blog/wiki/并发和操作系统)

- [如何评估锁的实现](https://github.com/o-my-god/Blog/wiki/如何评估锁的实现)

### 性能调优相关文章
**brendan gregg大神Linux观测工具**
![brendan gregg大神Linux观测工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_observability_tools.png "brendan gregg大神Linux观测工具")
**brendan gregg大神Linux观测工具**
![brendan gregg大神Linux基准测试工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_benchmarking_tools.png)
**brendan gregg大神Linux调优工具**
![brendan gregg大神Linux调优工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_tuning_tools.png)
**brendan gregg大神sar工具**
![brendan gregg大神Linux调优工具](https://github.com/o-my-god/Blog/blob/master/resource/linux_observability_sar.png)

#### 性能监视、跟踪工具
- [uptime系统负载监测] https://linux.cn/article-2334-1.html 
- [top、htop、mpstat CPU使用率监测] https://linuxconfig.org/how-to-check-and-monitor-cpu-utilization-on-linux
- [深入探究Linux Kprobe机制] https://mp.weixin.qq.com/s/5OKwGxwh6qwui7JdaJ82VA

#### 性能调优知识
- [CPU Utilization is Wrong] http://www.brendangregg.com/blog/2017-05-09/cpu-utilization-is-wrong.html
- [The PMCs of EC2: Measuring IPC] http://www.brendangregg.com/blog/2017-05-04/the-pmcs-of-ec2.html
- [Off-CPU Analysis] http://www.brendangregg.com/offcpuanalysis.html
- [利用perf功能检测false sharing问题] https://easyperf.net/blog/2019/12/17/Detecting-false-sharing-using-perf
- [Run Queue Latency案例] https://mp.weixin.qq.com/s/AzcB1DwqRCoiofOOI88T9Q
- [理解 %IOWAIT (%WIO)] https://www.linuxprobe.com/understand-iowait.html
- [Iowait的成因、对系统影响及对策] https://cloud.tencent.com/developer/article/1071025
- [perf sched for Linux CPU scheduler analysis] http://www.brendangregg.com/blog/2017-03-16/perf-sched.html
- [perf example] http://www.brendangregg.com/perf.html#SchedulerAnalysis

### 网络服务器编程
#### 不为人知的网络编程
- [不为人知的网络编程(一)：浅析TCP协议中的疑难杂症(上篇)] http://www.52im.net/thread-1003-1-1.html
- [不为人知的网络编程(二)：浅析TCP协议中的疑难杂症(下篇)] http://www.52im.net/thread-1004-1-1.html
- [不为人知的网络编程(三)：关闭TCP连接时为什么会TIME_WAIT、CLOSE_WAIT] http://www.52im.net/thread-1007-1-1.html
- [不为人知的网络编程(四)：深入研究分析TCP的异常关闭] http://www.52im.net/thread-1014-1-1.html
- [不为人知的网络编程(五)：UDP的连接性和负载均衡] http://www.52im.net/thread-1018-1-1.html
- [不为人知的网络编程(六)：深入地理解UDP协议并用好它] http://www.52im.net/thread-1024-1-1.html
- [不为人知的网络编程(七)：如何让不可靠的UDP变的可靠？] http://www.52im.net/thread-1293-1-1.html
- [不为人知的网络编程(八)：从数据传输层深度解密HTTP] http://www.52im.net/thread-2456-1-1.html
- [不为人知的网络编程(九)：理论联系实际，全方位深入理解DNS] http://www.52im.net/thread-2740-1-1.html
- [不为人知的网络编程(十)：深入操作系统，从内核理解网络包的接收过程(Linux篇)] http://www.52im.net/thread-3247-1-1.html
- [不为人知的网络编程(十一)：从底层入手，深度分析TCP连接耗时的秘密] http://www.52im.net/thread-3265-1-1.html

- []
### 操作系统相关知识
#### 内存
- [带你深入理解内存对齐最底层原理] https://mp.weixin.qq.com/s/F0NTfz-3x3UxQeF-GSavRg

### 中间件相关知识
#### redis
- [Redis persistence demystified] http://oldblog.antirez.com/post/redis-persistence-demystified.html

### 分布式相关知识
- [如何优雅的重试] https://mp.weixin.qq.com/s/6IkTnUbBlHjM3GM_bT35tA

## 关于作者
- QQ：740016830
